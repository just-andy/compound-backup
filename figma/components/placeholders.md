
# Placeholders

---

# Overview

Some components require a great degree of flexibility in the content they display, this is particularly true when nested components are required.

Figma advocates using a method where you create a space in your component to swap in custom content. This is called the placeholder or slot method.

The idea is that the library component contains a nested placeholder component which the user can replace with their own custom components and instances.

This offers the maintainability of the system components alongside the flexibility of custom layouts.

*The outer component should never be detached.*

## Placeholder Components

The following components use this technique:

- [Accordions]()

- [Overlays]()

- [Featured Cards]()

## How to use slots

This approach is widely documented and you can follow along some of the tutorial.

  
[Open Youtube Video](https://www.youtube.com/embed/3AXLubczRoY)  


### Additional Tutorials

- Placeholder Components: [Video Tutorial](https://www.youtube.com/watch?v=gS-MvibsunE&feature=youtu.be) | [Demo File](https://www.figma.com/community/file/963783690783191844)

- Demo file: [https://www.figma.com/community/file/969234311094210750](https://www.figma.com/community/file/969234311094210750)

## Quick Tips

- Set up your component instances in the overall UI and then you can find out the dimensions of the placeholder instance. You can use this to inform the sizes you need for your custom component.

- When you swap a custom component with a placeholder instance it may not fit properly. You can adjust the auto contraint properties on your component and the outer layers to make sure things fit.

- If your custom component is too large for the placeholder area you can set the clip content to true on the wrapping layer.