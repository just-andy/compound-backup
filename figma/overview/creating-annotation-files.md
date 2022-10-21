
# Creating Annotation Files

Clear annotations can assist developers and testers to ensure that proposed designs are delivered to the highest standard.

---

## Overview

Annotations are extra information that helps designers, developers and other stakeholders to better understand the design and its components.

Annotations should aim not to find the right balance between required information and possible extreme cases without overloading the readers with unnecessary information.

## Document Structures

When working with the same development team on multiple handovers it makes sense to stick to a structured format. Over time this consistency will build up between design and development of what to prepare and expect. Each time this structure can be refined to create the previously managed balance.

Before setting out the annotations, you should work out what you are trying to convey and how concisely you can do this. A few questions to ask yourself:

- How many variations are there in my designs, this could be screens or component variants?

- Are there overlaps to other projects that you should use as examples e.g. component variants or similar flows?

- Does anything change based on the device or viewport size?

- Are there any edge cases that should be highlighted?

- Are there any styles different to our current design system of branding?

- Are we using new components, branding or content that will be new to the development team?

## Example Documentation Template

Our [Figma Annotation Template](https://www.figma.com/file/gVowzcxDdtbCdRCP7gE1JJ/Annotation-Template) covers most of the common questions:

1. *Overview* - Give an overview of what you are creating; either the top flow or component variations.

1. *Key Variations* - Highlight any key variations that change such as the unhappy path on a flow, examples from other projects or changes to the components.

1. *States* - Annotation specific states of component(s) and highlight any style differences.

1. *Dimensions and Styles* - This may be split up over sub headings but key elements should have all the expected sizes and styles clearly annotated. Our [Redlines Library](https://www.figma.com/file/0XAM45zFMRKz5QcRfaFVjX/Redlines) provides some components to highlight key information.

1. *Typography/Real Data* - Illustrate anything that is key when using real content such as text wrapping, long and short content from an API, nested component visibility. Providing clear extremes will help developers and testers work out the range of a component.

1. *Responsive Variations* - Although all of our work is [mobile-first ]()it is beneficial to show key variations of a page or component as you expect them to be displayed in other viewports.

1. *Edge Cases/Highlighted Functionality* - There may be key points in the design that need specific attention. It is worth grouping these together and drawing particular attention to what is required.

Overtime you and your team will develop your own structure but you can also take additional inspiration from our existing component annotation files.

![Img](https://studio-assets.supernova.io/design-systems/16150/42c2f278-3484-4cda-a223-77d1647d373e.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC80MmMyZjI3OC0zNDg0LTRjZGEtYTIyMy03N2QxNjQ3ZDM3M2UucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=aN7xIIENjxBXtSKz5JbTDG1-5NYsJTN9vAo2u4YWR5OZMm48zVuBlDnUnAxJUZcLi~x3~MLg3uUTRATgTCs3-Nh6gVhE9eDG9LQOMrs8ITgOpACotYuhSRKI28C8OFndAMGjXRhE~Apy~q18N9bcxt73elloUpeEZvy2rhUAmhIKXCyqLHcH1Lz9Cv46-bRdiL-eTtcL8sM-DmnTvZmfmLG9vcnKBRb5i0BQ9sAlGzgjAHKnmAvoajGNu~XX3rw6ZZxMuks8EoJxjU0s7HBoEQT8Zb6mz6mIP6gA46sQMaZLHr1sw255MesHmi4d~BDDxqV8YlwF~N0FYrlnXjrtAg__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

## Creating Annotation Files

Although annotation files can look laborious the time taken now can reduce more time reviewing things after it is built.

### Project files

Creating annotations in a project file should be within their own page, usually labelled with a 📐 and if your team prefer it the Jira Ticket ticket unique ID. This is outlined in our [setup and structure]() documentation.

### Component Annotations

These should be created inside the design system project e.g. “Standard Life Compound” in the specific annotation project. Each project should have its own annotation file that is named the same as the component to be or built.

If the component does not exist create a new file, you can [duplicate the template file](https://www.figma.com/file/gVowzcxDdtbCdRCP7gE1JJ/Annotation-Template). If this is an update then create a new branch. The branch will be merged when the built component is released.

## Reviewing Annotations

When you think the annotation documents are ready it is a good idea to:

- Ask another member of your product or design team to read through it. Could they understand what to build with what is provided?

- tsart draughting documentation. writing things down may throw up a scenario you forgot  to include

- Are there parts of the document that you repeated yourself? Explaining the same thing twice can add confusion, try and cut it back to once.

- When laying out redlines for dimensions etc make sure there is enough whitespace around the element so it is clear what you are indicating.

- Use design tokens for styles alongside any style values e.g. “BP90/#147CB3”, this will avoid confusion as to the colours used.