
# Layout

---

## Overview

All of our layouts work to an 8px soft-grid which provides the flexibility of dynamic content balanced with a structured approach to spacing.

Providing space around content creates clear grouping whilst providing room to breathe and improves readability. Spacing in a consistent manner creates familiarity for the user.

## What is a soft grid?

A soft-grid simply defines the spacing between elements, not a document wide grid like a hard-grid. As Compound supports multiple platforms and viewports a soft grid provides more flexibility whilst maintaining a visual structure.

Spacing between elements should be in factors of 8px depending on the groupings displayed.

![Img](https://studio-assets.supernova.io/design-systems/16150/c1c3fc35-7845-4e16-9337-53b9659083a4.png?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9jMWMzZmMzNS03ODQ1LTRlMTYtOTMzNy01M2I5NjU5MDgzYTQucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=ZUFw2MpXatI7bs2RDC-etk~~MRF8xWgg7BXlD--AkOmO1Vtv9nBguJ0PuRO3cvb0JqZVWHzPx8SnVkNIita0doW-5oOgBaTaqk0GbGqo-w8P51G7LmlZzzhho307ZlQf6d8H8zRGAba1J3BZlcY89chuWjgviMzA32e~WeZHHEIPcPXDkjmfBmQ1WJwutoXgYk1XfW2p298YhQxqFY9bUcbqyIGCVlw4kskgFjgz3PucDtbueNv9FjLmA7l9XDv898GwdkBQApLrl-IIdvVmaMofiVFurthwuSlpFyzHuJWnLEyKkAsc6GsQWr1ie~W-od1sHuN43ZnI9CaMdki-TQ__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

Typography and dynamic content is the biggest factor in defining the overall size of our elements. Where possible, our Compound components of fixed height or width are created to a factor of 4px or 8px to fit better with the soft grid.

![Img](https://studio-assets.supernova.io/design-systems/16150/7b2411dc-c6be-4449-8b60-8d5eb5b54ee0.png?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC83YjI0MTFkYy1jNmJlLTQ0NDktOGI2MC04ZDVlYjViNTRlZTAucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=MCp3ZbN64sGuEjKWMHMx8Vv2p9rQeFiNs0uIm2uW2EYvseIsDDyCiaX0-HUwScpe2M8jpqPlSeV8P74rfZDRm66AUCQGOfxTwP5YSbQzTDb6q2KTn18wK3l41j8dH5Kir~8lB3~BYFuE5JOpPIYrIVyL74oe-IQq-3tdTC61LUr0oBkM0-M6vQwDGdD9xv4cDum4LtlxDJJcGrEkRA4~mjIGD-ujwsh1ucgGH7AFBbqHchqBdKH3vm~wCAUTEYQrpGsDWV72dMMMdYRRmqTqooJCJaXpvBMzLnNdMQw1ZSY9OayiuL-8Qo54Iqv9yDRylYUAXqwISWc7prCKzfH9uw__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

### Hard Grids

Hard grids are similar to old print layouts where every item on the page lined up to a grid of 8px cells. On digital products that support dynamic content and various viewport sizes this would be difficult and performance heavy to achieve, every element would have to be specifically calculated.

Our [layout grids](https://www.notion.so/Responsive-Design-759f5be5df014dff93a8a4aa1d10ba2a) take a similar method to hard grid on the horizontal axis. It requires the each element line up to to the edge of a column and use the gutter as whitespace.

## Spacing Scales

Layouts vary and there is no specific template that can be applied to every page. What can be used as a guideline is that content should be grouped based on content or context. And within that a consistent scale can be applied.

This scale should have the smallest space increment to show that elements are grouped and then increase in increments of 8px as the elements change.

### Forms Example

If we take the example of a simple form the space between elements related to an input are 8px, the smallest space increment.

![Img](https://studio-assets.supernova.io/design-systems/16150/3209ecb6-1487-4cd7-9462-d2e28155d0a3.png?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8zMjA5ZWNiNi0xNDg3LTRjZDctOTQ2Mi1kMmUyODE1NWQwYTMucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=RCkkSYnPipQ4n45SUhrDE4mRprN2nxtfyibClELVlTv-Aac-vmiB8lTzCh8x9D6vTTwkf0BGHgrstuOytnu6epCK2h~AW9MnN05ANrYBXcBEdPTJgHMAXtXqgLPJkq20QivtT~kt43LZLI7~02NW1srbDXJU-Jl5wd0macxPrWIadsLOh-jAzhkisQZc1~glelBsPcDiCVrWrG-wGiqEt826JtWwcJYQKeZBdVtcmzpXiEmoP5nu8Jr5~22AXLNYHnoHLWZTkL3949KEjwR0jFIqyBiApaUVDEsIsMyQyH6JCFKcGDaUaOIJhnhyehnYrHKfgT3tWIPdmFLWgGqSug__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

The space between input fields is then increased to 16px, the next increment up, and 24px for between the title and field.

![Img](https://studio-assets.supernova.io/design-systems/16150/0ff8086d-0a98-4f43-8449-34aca81be09e.png?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8wZmY4MDg2ZC0wYTk4LTRmNDMtODQ0OS0zNGFjYTgxYmUwOWUucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=mI-6AhFwPYspDeBlcrPqtb9zt~m3~fnHtXNsBs4x2BxINr-95RwHtT5c0IlEHlogoXd~Hg1klJ77RB6Fipv5hAcSytRD34micd0qO7FXwByjR6qDepwYLRnS4Fp31oG6apFnpRugCDTBS9ZAXAughTyqP-irC9QpH-s6be3VwVCHPgkR6MKcB4hcTGyLKWgAIKJLiYVjrI~AOIahi7wb5Er2OsjhvLKK-wAoPvhti3tiSwa8CZYS3D0EoM8D98QHNYM8Mg3Z9s3GwjOoz1U0Au5b-w9L1tQ97qVXXPfzHRolcu~LhC8TAhoopxqbmlkYYC49ssJdBOW8H5XXw3dI3g__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

Although this example steps up nicely in linear steps there may be use cases to scale in larger increments. The three key elements that should remain consistent are:

1. Spacing should be increments of 8. (This is for both vertical and horizontal UI elements)

1. Narrow and wide spacing should be used to display the relation between groups of elements.

1. Elements are spaced from the bounding box of one element to the other.

![Img](https://studio-assets.supernova.io/design-systems/16150/c70ad21c-3836-404e-b3cb-297e874ab7cf.png?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9jNzBhZDIxYy0zODM2LTQwNGUtYjNjYi0yOTdlODc0YWI3Y2YucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=JSi1HQMU~Q3660~vF6JK4-E6E0QW~Bs6ZREf4nQXvxG~Awgc9YDSR7~FkwM4iA4FFBD2W8bAGpVZ527d93YPshjqCrMIhRv5g0J3kRPch8cnzDaIOxoMaaxVE~EAxC-MajNQxHe8Y79o7MU~wEhmBafm24bKA817e7EeKlHMSkb1HnWWRZAcV7dw3-SDceprjE7EnyfT2rgjGwg9Mob2EX2ZRZjUK-Iz4ace3QBO4hDsM7e4rTvmwXWn~f4SU9~8Duke-IJEaL0~GR4Q~wdBU9eHW7bM8q90icGHcelYY5YkIMVnptL3085xAXcJbq81U~k5FLes-Kznud3CJ6rPVg__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

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

![Img](https://studio-assets.supernova.io/design-systems/16150/0d974118-150e-4b22-968f-5bdff31b3526.png?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8wZDk3NDExOC0xNTBlLTRiMjItOTY4Zi01YmRmZjMxYjM1MjYucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=Z1B8MVsqvqBz6noUg-1TMVOS0p-qV5-UbjcRlKyP2ozFRS-d~ezkNddyHKIjKv~R7RFIrFiTkijfRWkx-Uthbc2x2JDJlhOvzr4GPszKkdw4Cxl777UXkYZ0J9x8xgEgjtFcJSXZR1ZhCY-P8JYzUnd6pDY7dwLh99gJ4BAggQXAIDEIzBB5kAAY8TcKnrf9k2XgbjLIt8uoqmOI~831j39POS1xsmwB2~y5Id6WCsy4-M9Z1OqrAFQ~JUUoo6k3k4nkw0KcwKJChq0zb8FImqQQcjgI1lsNajDlTmP1k47MSP2jut1et30j36B-wDihtX0B-4a4uLSic~QgVeL3bw__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)