
# Building Shareable Components

---

## Overview

You don’t need to have have read every document to build solid Figma components. The key is sticking to recognisable patterns across the component library. Reusing patterns leads to a lower learning curve for other members of the team and perceived speed increase.

## Getting started

Before firing up a new Figma file, it is best to spend time going back to the built live or annotated component. This will provide an overview of what the component structure should be. Figma components should align as much as possible with the Compound component or live code.

- Review the [component documentation](https://www.notion.so/Components-98fff05de3c0450bb66575cfaaf89ac3) and note the goals and variations of the component.

- Use the [annotation of the component ]()as a blueprint but be aware things can change in development.

- Finally, it is important to play with the live component and get an understanding of how it works. You can use the two sources above as a reference point.

## Points of Reference

As the component library builds up you will see similar patterns are used in one component or another.

Working through the research phase above, it will be easy to identify existing components that have parts of the requirements you need. It’s always useful to have them open as a point of reference as you build.

As highlighted in the overview, sticking to patterns in your components will make it more familiar to users.

## Breaking ground

You can start to build things out around the same time the Development team is requesting an initial review of a component they have in build. By this point the documentation and specification should be almost complete and provide a reference point for both checking the component in build and creating your Figma component.

Things are easier to work with when you get something down on the page. There are two approaches for starting a new component.

### The kitchen sink

Fire up Figma and try and build the most complex variation (aka the Kitchen sink) of the component you have identified.

The kitchen sink approach is the best way to start for components that are a composition or nest other components. From there it is easier to deconstruct the variations and variant properties as you need.

### Start small

For smaller, more atomic components; lists, buttons, form elements, it is best to start small on a single element e.g a list item.

These smaller components are usually used in variations of the same elements. When it comes to testing it makes sense to group them how they will be applied so you can test for defects more realistically.

### Remember the guides

This is a small snapshot of the [file review checklist,]() working with these guidelines as you build will make the final reviews much easier.

1. Follow the [naming conventions]() for layers and don’t leave things as the default “Frame”.

1. Use the base design token styles e.g. “LM N0” and not the short hand “Interface/Card/Light”.

1. Keep files clear of clutter.

1. Make sure [variants follow our guidelines](https://www.notion.so/Component-Variants-15bc43c7ac7d4b96a1d851969ebea99f).

1. Always review the [checklist document](), this will be updated with the most recent guidelines.

### Structuring Components

Every component will be different but there are common practices to follow for consistency.

- Use True/False for all properties that use a switch

- Organise states and variants as [outlined in the documentation]().

- Make sure the most common usage of a component is the default instance. This makes if faster for other team members to use.

- Use frames to group components that are related so that they are grouped together in the asset panel. This example shows how form components are grouped together.

![Img](https://studio-assets.supernova.io/design-systems/16150/78c8357d-ad50-4deb-8969-1026996a1687.png?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC83OGM4MzU3ZC1hZDUwLTRkZWItODk2OS0xMDI2OTk2YTE2ODcucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=hWcQvgI62fuq8K7aXxozhk1~Oz~2MpkaqmPjaSh4C36getPCQW0sUj1vWq0F4VrnBxuqWunyuBIlsGhtCBjrsWvnG5gHUez~B67Eh5Wle~wswHQHCEVeMkkrOV~8ne5SRGM0W7BobvA6F8-EGQEVh3Vsm6eJq5F4~vRDyAs9Z7nJ4j~eMVS1FP7GdzUFce3elwZiT2eUZ4UV0pIKhkirV1Px1s9LE--c87ZOB5apnQaWjVPDOIwYrSvjwwcaMx-zxjTwBuurairXzMzmaiXr7hhppTdR5QvpBLTyGqTSmnumTwLUmMJI3VPAD~udrZPOF-~RYkwPl-U~02WSGjGb6w__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

### Private Components & Styles

Figma allows components and styles to be specific to a file, and therefor not publish them for a reuse. A good example of this is the Tabs component where Effect styles are used in each variant, however, these styles are not published into our global style.

In Compound we use the “.” notation in front of the component or style name to [make them private](https://help.figma.com/hc/en-us/articles/360025508373-Publish-styles-and-components#private), the “_” prefix should not be used.

## Development & Design Differences

Building out the kitchen sink is the quickest way to identify where the limitations are between Figma and the coded components.

A common diversion here is that a separate Figma component may be required to create some functionality. The [cards component](https://www.figma.com/file/ZisCHpJgiaJakbX1SJScvf/Web-Cards-WIP-%F0%9F%9B%A0) is a great reference point for where a single Compound component needed to be split into separate Figma component. A common sign to break a component into multiple components is if they require different variant properties, as the card example illustrates.

## Testing

It’s always useful to set up a component early and drag an instance alongside it early in the process. Think of this as a workbench as you can quickly see how changes will affect components almost in real-time. The beauty of variants is that you can have many test instances with the properties set.

> Be warned:  
> A common issue with testing an instances is that some instance overrides stop the component updating if you are changing the master. 

If you make changes and notice they aren't appearing on the instance either drag a new instance or reset all overrides on the instance. 

When testing it is always a good idea to use real data and some extreme cases. Samples should exist in the annotation or documentation if they have been created properly.

> Some extra info:  
> It is recommended when you have a few key components created that outline your component to get some feedback from team members. They are likely to have ideas, suggestions or find bugs. Do this early before you create every variant, it will save time in the long run.

Our process asks for two reviewers and their input is invaluable. It allows testing from another viewpoint and is likely to pick up what you didn’t spot.

For complex components, it is useful to test the kitchen sink before your start taking the time to break out the variations and variants.

## Library Alignment

With your component build and tested it is time for the final polish. You should always run through the [component checklist]() before asking your team for a review.

Make sure that you have started to draught the supporting written documents in our component docs. Writing out how you expect your components to function can often throw up some additional tests you think to run on your components e.g. wrapping text, wider/narrower variants etc.

## Final Tips

- Remember that Figma is a tool for the design team. Whilst we aim to follow development if there are ways to make things easier for designers to achieve their goals that should be prioritised.

- Use as few nested layers as possible, they make drilling too content difficult.

- In component variants you can add or remove layers as needed in your layouts, all variants do not need to have a consistent structure.

- Remember to follow the existing guidelines for [building components files]() and [variant naming conventions]().

- When your component is approved and published remember to enable it for the wider team.

- Don’t get stressed, we never get it right first time.