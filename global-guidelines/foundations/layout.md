
# Layout

---

## Overview

All of our layouts work to an 8px soft-grid which provides the flexibility of dynamic content balanced with a structured approach to spacing.

Providing space around content creates clear grouping whilst providing room to breathe and improves readability. Spacing in a consistent manner creates familiarity for the user.

## What is a soft grid?

A soft-grid simply defines the spacing between elements, not a document wide grid like a hard-grid. As Compound supports multiple platforms and viewports a soft grid provides more flexibility whilst maintaining a visual structure.

Spacing between elements should be in factors of 8px depending on the groupings displayed.

![Img](https://studio-assets.supernova.io/design-systems/16150/c1c3fc35-7845-4e16-9337-53b9659083a4.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9jMWMzZmMzNS03ODQ1LTRlMTYtOTMzNy01M2I5NjU5MDgzYTQucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=mdshlbiQlfa3p5fFsU2pKl11-G27xUPDBMzzvAien8O9ub4bOQ8vjCuWN8cKhE4L~GjjTq8N-SPrRqrKqdtgDk5hpkI4FPcmdrmZrHvuvSNCnCoF0CL6nm7PMKVmXX25a0A20A3GzTtAQhqqrNAJicqOolDyIRISb8XF7aVjvbjwrIu0icFJ~ahpw3u6EJjijy9NF~yftETDulHKaMH17m9bO2QDIwZPHLK6UO89Bdmhkbly0oERp9ManhvQdw29IWjAY6x5rjO0eP5-Jfk6IZpodtJEYO9fcVZE5MbNIZGvpQgJtJZtdCHRo-I~gnRllNWSFxfCqVTNZKTu~s4Wcw__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

Typography and dynamic content is the biggest factor in defining the overall size of our elements. Where possible, our Compound components of fixed height or width are created to a factor of 4px or 8px to fit better with the soft grid.

![Img](https://studio-assets.supernova.io/design-systems/16150/7b2411dc-c6be-4449-8b60-8d5eb5b54ee0.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC83YjI0MTFkYy1jNmJlLTQ0NDktOGI2MC04ZDVlYjViNTRlZTAucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=JYrkhqCFICHDFr~jJT1Nk2e98hd94UNIv2jbEOgCQayMqGN6Huiv6i8fLNlU0bBsVwiUFQXYwB~BdowQuims86chlqW9JiWn2pHhBq6CsaQ3kDPz8s250S5RjEfGp6GGxWmIw1uhcTVm-8blyIqZ0J5ZiPPz9a~oIVsQLbaQDrG4JvP3fOnn~1GGCIpEAjTXxb1sJGL-m7RdjwNjh0qznI6OebwudbobOOV82fHCx4r-2eTpNrAh30GzKce5KJRLJ1MXBAOD1OvWANJEaGMZsaXv8oHnJnn5WhQEjsFOKsa8iNAP7BgsqXa-UhQQbVjAqxnhlBHXo9TgRBbQDNE9Cg__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

### Hard Grids

Hard grids are similar to old print layouts where every item on the page lined up to a grid of 8px cells. On digital products that support dynamic content and various viewport sizes this would be difficult and performance heavy to achieve, every element would have to be specifically calculated.

Our [layout grids](https://www.notion.so/Responsive-Design-759f5be5df014dff93a8a4aa1d10ba2a) take a similar method to hard grid on the horizontal axis. It requires the each element line up to to the edge of a column and use the gutter as whitespace.

## Spacing Scales

Layouts vary and there is no specific template that can be applied to every page. What can be used as a guideline is that content should be grouped based on content or context. And within that a consistent scale can be applied.

This scale should have the smallest space increment to show that elements are grouped and then increase in increments of 8px as the elements change.

### Forms Example

If we take the example of a simple form the space between elements related to an input are 8px, the smallest space increment.

![Img](https://studio-assets.supernova.io/design-systems/16150/3209ecb6-1487-4cd7-9462-d2e28155d0a3.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8zMjA5ZWNiNi0xNDg3LTRjZDctOTQ2Mi1kMmUyODE1NWQwYTMucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=Er0IHQ3aLVCGleCqM6m10s5a2g5BnBQmYV8k5HtrFSiQeU7HKBLSs0qK6-MPx3Iqu46VhS-eKbmhfPyIwmCqXbU~8bgG7w0Bh3uBFDnm3oxiHQBl3JYnim~UYFsIeEjig3ZCbesd5sCPYIluv4awum6ljhx6w0DeCdkt2RplFPxCZBq5dxC9AJDvEew~obgpQjok-oIY-ajjse-MNpHvU7q-O7Q6VqsPuFjI-M4qwSA08Ykv7DOAh1pXxI~yqW8GQSIF~j0xHypcig6sv84vuMxMz0FasOnNX7E75pTvZaRiAr6XI6BNZcbNrJQUxeXvoRZobRy3FsOGRhRrg213VA__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

The space between input fields is then increased to 16px, the next increment up, and 24px for between the title and field.

![Img](https://studio-assets.supernova.io/design-systems/16150/0ff8086d-0a98-4f43-8449-34aca81be09e.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8wZmY4MDg2ZC0wYTk4LTRmNDMtODQ0OS0zNGFjYTgxYmUwOWUucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=ZrGQJ~PmW064U~sYQNeEvWLEIIQUEkhf-Zap15viel1oHXHxWh3aVGuIYYoaN5t9~PT8F5HKoveeD8MuAs8W2Wg~fLqYTxSbDZv6cLS8cp7DActOoY28qO20KSTT2LTgoCfhvEMY1QQrYZ6xCE~hPqthT~cOg2kCLKJDfqqkThgnO6OKeZyJoO82uSQJCvod9Dp3pTH427VtdYOrMWIyAO-uXSNfDxpNBJDounyWCQZTMeLeMTShtxvkpAR5FkuFFn72Emc8pLgrmeUrOGp0de2YpBGMFN62033a1QYYA7sYxqmKxN2WdK~jB9bZ-o27qw1WcSFwyCUrXK-rd85btw__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

Although this example steps up nicely in linear steps there may be use cases to scale in larger increments. The three key elements that should remain consistent are:

1. Spacing should be increments of 8. (This is for both vertical and horizontal UI elements)

1. Narrow and wide spacing should be used to display the relation between groups of elements.

1. Elements are spaced from the bounding box of one element to the other.

![Img](https://studio-assets.supernova.io/design-systems/16150/c70ad21c-3836-404e-b3cb-297e874ab7cf.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9jNzBhZDIxYy0zODM2LTQwNGUtYjNjYi0yOTdlODc0YWI3Y2YucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=fUYzjeaK5vduS2E0gspooJuIkl4bsZnAw7Vc2vd6xxbYnhu9kzxPzq7XaZFqb8~3AJjgiQ2Fj-mgKPa7uxl1faFUTZN6HXVquQEEobYGqHDuc72ieA10ZBBFzJWBm06vv-2vsoc9p5CNCT~zqDt0yuvWmiE1eF-xZE7IDgGfRMoqfMm6rH92WCpFI9bGvE9r6mycHAdX9xV0rMYSwjNyP~~VnfGa2oj7u7ezF~p9owiG~UH8vpaAztj2bvssFSVCirHF1R1n5xOLR4a38XZqhrc08oBpY3yoiT7VQtBwZbmGfBIXwgwDNcfSKEQyZc6NJ3apQUtUsEgEeOAbbIGTwA__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

## Vertical Rhythm

Whilst soft grids relate to the overall document, vertical rhythm is a term specific to how typography is evenly spaced on the page.

Consistent scale improves readability as well as creates an overall clean documentation. Within compound we have three vertical rhythm scales.

1. *Native* - Both for iOS and Android

1. *Large Web* - This has a larger line height

1. *Small Web* - This has a tighter line height.

The compound type scale and colour palette have been created to meet AA accessiblity standards so that they can be used in conjunction.

Much like the spacing scale there is no single solution for every layout. The scale should be used to demonstrate hierarchy of textual content. When used along side our soft-grid scale it is possible to use spacing to indicate content groupings.

## How to check spacing in Figma

Select an item within Figma, (it can be a frame, component, text block, pretty much anything), press the *option* key, move your mouse to another object and you’ll see the measurement shown on screen.

It’s also recommended to set your big nudge to 8px so you can move objects in units of 8. This can be set in *Preferences > Big Nudge*.

![Img](https://studio-assets.supernova.io/design-systems/16150/0d974118-150e-4b22-968f-5bdff31b3526.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8wZDk3NDExOC0xNTBlLTRiMjItOTY4Zi01YmRmZjMxYjM1MjYucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=G0QH72SxkhMhxrDCgi13Zsg~QQNzD2ZGNxjLPbD7oXXojIjQYnhUTRg8Tpk356WOcs69LUPA8tN0GXukLibaDM8w7y7JO0rRI-NyXDZjKy4YAxjjR4A9C3BHCtiRMWxmmi0Q89mBPtknSXP-TnqXFny33id8DpVxCkd4rIxY5CKCAhDZ0Wx5ctguNBD3v2qQ7MepAwcGLj73~0xe8bCBUtdADjV7IWFBElkI0C-KUerwDbb5TxF9dK~5NGHsttd8ZgGSV-qM9gi8xS7ZTD0VN35SmhQHx4T17IXlsFeGpzR8WV7AeqEN8Sw3gPeZwa37anlCFdymUU74djJKsi9hiA__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)