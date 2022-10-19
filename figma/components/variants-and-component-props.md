
# Variants & Component Props

---

## Overview

Variants have many benefits from alignment with development through to reducing the number of components required in the asset panel. For more information on variants, see the [Figma Playground file](https://www.figma.com/community/file/903303571898472063/Figma-Variants-Playground) or the links at the bottom of this document.

> “Variants introduce a new way to group and organise variants of the same component. This makes components easier to maintain and more intuitive to use.” ~ Figma

## Breaking out components

Figma variants do not have the same amount of logic as the final built components. Therefore, in some instances it may make more sense to [break a single component info a number of separate components](https://www.notion.so/Building-Library-Component-bc3125df94374a9189b28a5d565c1248).

## Property Naming Conventions

The following naming conventions should be followed as a hierarchy of property. Component properties will vary so apply the following accordingly.

In general names should:

- Use capital letters at the start of each word i.e. "Show Icon".

- Be as descriptive but concise as possible.

- When using the boolean component property to handle the display of a layer then use the prefix of "Show" i.e. "Show Button Group".

## Component Hierarchy

Using variants and component properties together can make component properties cumbersome. To eleviate this issue a consistent hierarchy and naming conviention will bring famialrity to the library.

Components should be built with the variants first and component properties second, text component properties should be last for ease of input. 

Aim to follow this order using the components where relevant.

### Variants

1. Theme 

1. Variant

1. Size

1. Orientation

1. State (If Required)

1. Other Properties (If Required)

1. Boolean Value(s) (If Required)

### Component Properties

1. Boolean Properties.

1. Instance Properties

1. Text Properties

## Variant Properties Explained

Figma allows variants to have as many properties as you require. For maximum usability these properties should be clearly and consistently named in the following hierarchy.

### Theme

- Light

- Invert Light

- Dark

- Invert Dark

Invert refers to the contrasting coloured areas used to highlight key areas.

### Size

- Small

- Medium

- Large

- Extra Large

### Variant

Clearly highlighting the different style of the main component. If there are multiple styles this may be a good indicatory to break a component into smaller parts, see breaking out components.

Examples:

- Primary, Secondary, Accent

- List, List + Icon, List + Tag

### Size

These should match the property of main component. Hydrocarbon components in most cases default to medium size, but do not have a named property.

- Small.

- Medium _(Default size)**_.

- Large.

### Orientation

These indicate if a components layout can manually be changed ie. Horizontal, Vertical.

### State

Our current naming convention can be applied to display state. You can use:

- Default.

- Hover.

- Focus.

- Active.

If you require a selected state, use a boolean property as explained below.

### Boolean Properties

There may be more than one of these properties on a component. Figma offers the option to toggle options with a simple switch.

Boolean Properties should always be named as follows:

- True.

- False.

## Component Properties Explained

[Component properties](https://help.figma.com/hc/en-us/articles/5579474826519-Create-and-use-component-properties) were recently introduced to simplify the creation and use of variants. This feature isn’t a new way of doing things or changing the current variant approach. It simplifies a few key areas:

### *Boolean*

This property controls the visibility of a layer. It is important to note that if you need more granular control over a component when a layer is hidden, you are better creating a new variant.

### *Instance*

Simplifies the process of changing a variant such as an icon, pictogram or more complex components such as button groups.

Instances properties may not be initially visible if there layer is hidden by a boolean property.

### *Text*

Provides a text field in the variant panel to change text. It is recommended to keep text component properties last and follow the order of the component. By being the last variant they are always situated in the same position.

### Known Limitations

- It should be noted if your spacing values differ when a layer is hidden by a boolean property you will need to create a separate variant instance to display the padding you want.

- You cannot reorder component properties into any position. They can only be reordered in their component groups. 

- When using the instance component property the settings of that instance are applied globally. In other words you cannot change the instance variants for each component you nest it in.

## Useful Articles

- [Figma Variant Documentation](https://www.figma.com/best-practices/creating-and-organizing-variants/)

- [Figma’s Create and Use Variants](https://help.figma.com/hc/en-us/articles/360056440594)

- [Building Complex Figma Variants](https://medium.com/galvanize/building-complex-figma-variants-e1005832c531)

- [Advanced Figma Components Video](https://www.youtube.com/watch?v=nY5nHaW0zv8)