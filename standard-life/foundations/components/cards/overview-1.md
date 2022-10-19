
# Overview

---

## Key Points

- Our common cards exist as composed cards, try to use these first

- Custom cards can be created, follow the base guidelines

- Cards are displayed on different background colours and shadow values based on the cards elevation

## Do you need a card?

Cards group related content together, usually as a summary to more detailed content. 

Too many cards can create confusion, particularly if there are competing for the hierarchy or overpopulating the screen.

Before using a Composed Card or creating a custom card it is worth bearing these points in mind.

## Custom Cards

If you are unable to find a composed card that meets your use case you can create a custom card using the following guidelines.

### Structure

![Img](https://studio-assets.supernova.io/design-systems/16150/482f6b23-2a3b-42d4-a884-fe10e45b894d.jpg?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC80ODJmNmIyMy0yYTNiLTQyZDQtYTg4NC1mZTEwZTQ1Yjg5NGQuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=Gs0LoimMTR-hJxV4DxG6958TirHykGD14I0Y0zOgGzcBDW1A4BaaUo9Bn534~1FdYNxutzNMO3ogV-i8eVAuFpsSggh7Fu8y-mmjnDMh77AMLkPhUr1WZdBmcldQDgrfELZ2bCY8QMsvpoROEkVNoSYaTU1sDKrKyoaWWxJnWrMX1-1SioUyKybqVkLlbiryfwaX4a12cRUfTht2IaG1KGlTWASPUnRu5kZjy5bygPBTvvW5-LXZOZHPHP6U4vLwcRZoYAA~x9SHBFMZr-MefdgpBdN3hikZ2XQXjv7NDBgwHdzCLxYiVFsrtolStzeoJr2akuKMgbxwThnbT-i53w__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

Whilst the Card BG component provide the consistent outer styling the content within the card should follow a consistent structure.

### Padding

The inner padding should always be 16px, with the exception of images which will likely touch three edges. This inner padding is the same across all breakpoints.

Inner padding does not increase as cards overall width increases

### Typography

Hierarchy and our text colours should be used to visually show hierarchy. Heading should use the appropriate level of[ Ubuntu font and colour (U110M)](), with supporting text using a body colour.

![Img](https://studio-assets.supernova.io/design-systems/16150/786499b8-7410-47d2-9017-8d12c51ff43f.jpg?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC83ODY0OTliOC03NDEwLTQ3ZDItOTAxNy04ZDEyYzUxZmY0M2YuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=lgK~pxEGCddHXNfZ0bXuZgbynC0GDAzfrZz7tr87Z3owWqLVBiftfNJEIbzUMO4rU5VN26wszva~mVVMdFy1YzfIUK-EqBYkyhwd2EvtGK4Wpl92m3tM4P5NscKeZAnqItYMICKN9utC5pFOvm0C-aW5HypfjdkYsA0gC-lWUQ~EDKzmKTi99G8VZGmmZnl4E4RxJqE5G2512oMaywidrABU-NG~iq06UghmmQB4Rn0OxonAAWfcdKBoycnu8sGKel4Fwx~Klgk53k~bQbrtv-C2QGU3DTET2fh2snzKyiDtKn38g~4mxycpCYhA0UcxSg4x-pVZA9CKnR5M8eeqtw__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

The example above shows how the type scale and weight are used to depict hierarchy. Card compositions will vary but you should use the type styles available to depict the appropriate hierarchy in any custom cards.

### *Styling*

- The rules of the [pre-composed cards]() should be used as a reference point to build upon

- The guidelines of inverted and supporting colours should be followed if this is the basis for a supporting card

- Remember to use the [correct elevation rules]() based on the context of your cards usage

### *Components*

When nesting components inside a card aim to use as many existing items as possible. Should there be a need to  any new or updated components then follow the [contribution process]().

### Navigation and Action Cards

Cards that take the user deeper into a hierarchy for further information should use a directional button in the top right corner. Use the composed cards of examples of how to align a badge with the icon.

The whole card container should be clickable on these types of cards.

![Img](https://studio-assets.supernova.io/design-systems/16150/13c17282-6bf2-4cee-ab9e-9d09ebd82fef.jpg?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8xM2MxNzI4Mi02YmYyLTRjZWUtYWI5ZS05ZDA5ZWJkODJmZWYuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=A7R9xd5YlJ-sSC1OjYliXp8MvdXT5tFsAEugoSnVnyZCVqBGoHRcj3dKF1NfahmFzbVa3CZZ7omMgW3N6YAet9pnwrJiOgZERlD6idrbaLWi2zJalGgWb50Gexw58O2TEzS4xktaevwWcPgt5Jd-MDw~rfKDzsuRC6D3Wtx1~hr~GwRBOl4O0cKMCJJ8cTDokCO7uQTP8kwzwW2C-nYy7uGDqurQchAdVJQPEcOEz-eIe~mtgC-p~oV85tNOhTWHYf-yXFtritywErtLygjsRmNT3DHuaKZlK3RW7Zc0RU4aliBbfX4nfDbv3FHz-h1JxVHN7WN1hO18oXfZDwx5tA__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

### Buttons

[Button groups]() should always be at the foot of the card so that they follow the content that the card is grouping together or summarising.

## Building Custom Cards in Figma

Cards are a unique component in our Figma set-up as they have a number of our common patterns but also a component which is designed to be detached as a starting point for customisation. 

Cards are an [exception](https://compound.supernova-docs.io/compound/latest/figma/overview/are-you-detaching.html#cards) to our [detaching guidelines]() as there are too many variations to create as composed components. The [Card BG component](https://www.figma.com/file/ZisCHpJgiaJakbX1SJScvf/Cards?node-id=239%3A3196) serves as a quick way to get the common card styles and build on top of it.

## Cards and Backgrounds

Cards can be shown in two different styles within a page and the correct styels should be used to suit the context.

- *Nested cards* are best used when boxing out supporting information on pages of long form content

- *Elevated cards* are typically used when a number of cards are used in a single interface such as a list

It is important to apply the correct guidelines related to [elevation]() when working with depth on the UI components.

  
| Column 1 | Column 2 |  
| --- | --- |  
| ![Img](https://studio-assets.supernova.io/design-systems/16150/00a51a5d-c1d3-490b-a586-3e2ee92cb2f1.jpg?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8wMGE1MWE1ZC1jMWQzLTQ5MGItYTU4Ni0zZTJlZTkyY2IyZjEuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=F39jthAcraWbHBfLdxHtX~66OSKRctxl8PS26jbLvYrkvUB4OwmfiCYjXh33ipAz56UI5KFcTErq242ppKA7JJxXzi8eKeyPSZjiwMSazUaJ-8dDUtinihbflmdKBS94XzEHy9TGoCrZeY0KT9Q3TS2C4mzg0RuOqk~MsWCqtL0ANm-1XivZmXqiYp2Mif2DSKbw2GD-8xnx4FK21Qqsu22v7pxGY5gtc1yIGgao0u8S~dSUR9ky4dx8qzwE1SXWoKKPO4xPTUGr~nD10W6-jE183SdPXCbGewr7-rJ~Rt~XFM8tO~Ut24BFX1wymFgRQBhPh1NY6SD1Gq4zSLLsJg__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA) | ![Img](https://studio-assets.supernova.io/design-systems/16150/8e47e9f6-0964-4b01-8dda-e9d32ed99d85.jpg?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC84ZTQ3ZTlmNi0wOTY0LTRiMDEtOGRkYS1lOWQzMmVkOTlkODUuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=Ok6d-oeC9RBNhwLoezRzc5McMVMXi-MBDJSk6ygS8KRa1-w~mAjSbN0c~VVYPq2jJkWwvzHVxZ0hfw25-SLl-UaiKxaEdrlD1ZIctI8nAVfeDPGUCdLKVi81f4aLZzrsXxiP8rxZJZEUzMgZj4wlfgRNkgvIsJMWR~q8nKifdlRmUC3rg6MypKnb~l7kIqI0W5lOVxv653U9T8QLN8GrFgWvSdpyxbp0LDCcLvFSV0kGTIfmAZ55AvgBr0UAJiXPMf98ZhFJSiHk211HjEJDw5filc3Dnz1vZF7uFJ0XPpLYo2LXhQOsYik7WT0ZKUzTpsRUlGZDCQy~W8g2KPUCaQ__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA) |  
| *Nested Cards* | *Elevated Cards* |  
| These cards sit within the page on the same level and therefore do not need a shadow. 

Default cards have a thing borderline to separate the group from the page. Inverted and supporting cards use their background colour. | Elevated cards sit on the level above the background and will need a shadow as they are closer to the screen.<br>To create further contrast the background colour changes to be two shades darker in our Neutral colour palette. |  
| *Background colour: *LM N00
*Shadow: *No | *Background Colour:* LM N20
*Shadow:* Yes |  


## File Links

  
[![Card Components](https://studio-assets.supernova.io/design-systems/16150/e56a0e4d-a761-4e85-8806-a94652b9bd8b.png?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9lNTZhMGU0ZC1hNzYxLTRlODUtODgwNi1hOTQ2NTJiOWJkOGIucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=F~s3SAgMx5zk~xG6iMUzuAGVC3Skv~cAMF1O-IsKvjZxgG8vHDRucb92-YZRcjVfcyADvfEiW45L5VfK3c6Bd1zMonBocE6ZJCpKKCQKHV45-E-B-6jcyqwJV2ijCrSuEmJloAitgPIuVAIyA87NZj0b3ox8oIqQX2drw6zXPiTbPxIYqy3Pg4Zq0j-fP0OzSOTTsXv8Q-~gpchcYViCf~Xqj8lJblw~u6~Yt7c7O2zhAF38fuZhB6iDu93ZA9clPACJU8vWwhWTaJMTJVNs5jn70CT9ZhmrMiDNSMHb9JxKkjZVhT3Qr~RZ9NB~9EHW0nRPaGnllWKFKH0bM6f1Mg__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)](https://www.figma.com/file/ZisCHpJgiaJakbX1SJScvf/Cards?node-id=1%3A2)  
Card Components, Figma composed cards and custom card starter components  
  
[![Magnolia Annotations](https://studio-assets.supernova.io/design-systems/16150/71ecc47d-0477-4a89-9b86-4591ee40dfdd.png?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC83MWVjYzQ3ZC0wNDc3LTRhODktOWI4Ni00NTkxZWU0MGRmZGQucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=XiQprScs81v6GZQ7tlRfSxIMDbfxKWjZ7F1g1mFeuDyxXpqiN0h7~2Y1txgYlPZaXpljD-AGhaUGOchPE9e2L02crwe1kHZ3F4TO45NS50zd8S5j-gFliJV~a-eHIzbTENsaqkqw0LrFQxvC-6jxdLv9PaQKfjC~cYgqYctdfJC20UQyTN23geR6UuWLZw3VMv9Yg6RE2KzcifSGzxZnB936GvAu5DU5KWmKptm0CUPuA-siLkQ0NfqSz9ZRlZsWZkGC3otQPTLamSJPBab7hmjBUp3QqariNmzux5k7svLMCy617fgK17aSYoJKM-9Q6tHlm28U3Wicm71FtorRfA__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)](https://www.figma.com/file/5ytPIJhuDabhkf1C1py28P/Cards?node-id=1%3A127)  
Magnolia Annotations, Magnolia specific card annotations  
  
