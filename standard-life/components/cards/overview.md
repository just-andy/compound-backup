
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

![Img](https://studio-assets.supernova.io/design-systems/16150/482f6b23-2a3b-42d4-a884-fe10e45b894d.jpg?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC80ODJmNmIyMy0yYTNiLTQyZDQtYTg4NC1mZTEwZTQ1Yjg5NGQuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=K-x3W~eWUirSep0-oRUPhQE3NIAwMjQVvBfa3qGZKQNocdY-188HHZO0z15S4nLDZrLXH1vyH~U9dpS2cwvTB~YcHyJ5U7kOswnd0YLz0eXMxVJaSM8HI1UjV-VDLDHSE4mYJIUKmLaigZYAH4q8rKZYrfwoqPcU3NzZBH57aqJqPjpexIxBUx06T8P97PZKOrQACrqLm9C7OM6h~oArojDX9ANj9GSPObRp6EL56OW61GSwhK1gciJcQy70hJX~7xQOXoJ5m9Ge2C9GA8f4D5WiC9EtL4qlJJ~yOkIVc6TL12Cj-VEuHHPoHvIbNFFBPDtYTfG5yjw5nGngYe7pIg__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

Whilst the Card BG component provide the consistent outer styling the content within the card should follow a consistent structure.

### Padding

The inner padding should always be 16px, with the exception of images which will likely touch three edges. This inner padding is the same across all breakpoints.

Inner padding does not increase as cards overall width increases

### Typography

Hierarchy and our text colours should be used to visually show hierarchy. Heading should use the appropriate level of[ Ubuntu font and colour (U110M)](), with supporting text using a body colour.

![Img](https://studio-assets.supernova.io/design-systems/16150/786499b8-7410-47d2-9017-8d12c51ff43f.jpg?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC83ODY0OTliOC03NDEwLTQ3ZDItOTAxNy04ZDEyYzUxZmY0M2YuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=c2z4Ndeczedtrk7oHqkcRSejh9MXAHQZ4wZcx42mXiAZY-r18NTVeCzvrTnb-aYU~B~dvvBs9s~LES8JXLW-gFYlDNGl0A6fC5xeb6f-N4rL8Hm8~Nt539vVJ3TkyXBG27n0~MRGcSSoZiT8RtF1n3flp5yu10NmNthTlz7UB7pprpqcNFH8DtH84yJjFOdiH8z8I17VlXyUmF-plR~9H70ncV79--~1MkmFXZDMfmOCkmlyzz2BbdmYBvxbV0h5YP0OuqYq1Pkh444tc99j0tgt3xXML7rUY8JlEJaJ8F7fEBdzR1CmpCblC3ifdIZjDG5wOqT7Cs-40Vtv5hlS7Q__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

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

![Img](https://studio-assets.supernova.io/design-systems/16150/13c17282-6bf2-4cee-ab9e-9d09ebd82fef.jpg?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8xM2MxNzI4Mi02YmYyLTRjZWUtYWI5ZS05ZDA5ZWJkODJmZWYuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=FfshJPFfrr1T9p7b3Wwxj0d9kkwTmAcS0BkZYlXYi2svctH4EQby5ZPhO4KrTdZuo3T~u3aD3CoETHayuWWoFECmjs9t4N2SUCP2uRMgrvBQN8eLBe5wAyJ71d8I4jcmCxaAoptoebC4nuHE~sZJU5cE6Zn2Z9cfRoHHQo4KPRbv3E-23x4JClI2U7V844h9o0KNs3I5ZjTups-5UxiLT6c9DadJEbm7qWk1ohiKW6Zd8o4HylN6FmQhD7Xvkk7tLzEl7Pq9wQBxYBhcBLNDVuiXiHIZxKSMQOTTxpf~7tF7VE2PV34LWKdsgBKu72kvZO~RNEXLuhCYiWN94U1YEQ__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

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
| ![Img](https://studio-assets.supernova.io/design-systems/16150/00a51a5d-c1d3-490b-a586-3e2ee92cb2f1.jpg?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8wMGE1MWE1ZC1jMWQzLTQ5MGItYTU4Ni0zZTJlZTkyY2IyZjEuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=GscCL8kUYvs1mssjJhgdjIblMUrtgsf3R~9QUgHXSZysncUP6M3f5v-kv1g-IaHs0XdzSAISYYYDb0~j3Bogd8tx12wYJ3VlDYkQBiMKOkBdbBLeyF6n-QMfAjxJ5LXc~eZSsQ26NPbny7rNUzegAJeVuoj-h0oj8UuZz0Mp96Gm1zj7WVfUmlmu6E7fP7ENeyS~hE6cHw-cNKe9O0-2QzfCYaTif-iJAtg3H6K2ioY3NbcrfifRhyURQd5IKTIJj4H3a-9rQTLibVAr9ZYVe-F3d6o5~pHFjIB9VoRJDOupO0ZV0rkvQmbR--E9pZJRw1Cl2YP~xR5HvNpjZMrvGw__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA) | ![Img](https://studio-assets.supernova.io/design-systems/16150/8e47e9f6-0964-4b01-8dda-e9d32ed99d85.jpg?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC84ZTQ3ZTlmNi0wOTY0LTRiMDEtOGRkYS1lOWQzMmVkOTlkODUuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=gRb11INNPSxmDcoRTONOlvUTgzP-MFszPhZuc8OYeNfxbJ88roNrmplwn~lkFTz94uJARNuybFXXP~afIwOu44vqu~zzT4lmE8nUNIiVxVAWDg0dO8uKQFC9Y-1SoXpZbPYlNzUZ3sq2Q7QOjRNlOHnj5rYav5Stzy-v2uPXDnFq0dTMHjFSMWM~eNYUVYsu2JBV0nhe0n~sTSmrRlmiBSp3vjPML79pnagRc~ovSJg~UKara8kR4C2zGKQeFP6Kg4Ly0O07b50lNHoZLpKQEOajy4oFBxjYAL8uIHs~1ZrmLTv00SnnSZYVxYnYPHhAciBz0s~UQd7r7zyEtEYJVQ__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA) |  
| *Nested Cards* | *Elevated Cards* |  
| These cards sit within the page on the same level and therefore do not need a shadow. 

Default cards have a thing borderline to separate the group from the page. Inverted and supporting cards use their background colour. | Elevated cards sit on the level above the background and will need a shadow as they are closer to the screen.<br>To create further contrast the background colour changes to be two shades darker in our Neutral colour palette. |  
| *Background colour: *LM N00
*Shadow: *No | *Background Colour:* LM N20
*Shadow:* Yes |  


## File Links

  
[![Card Components](https://studio-assets.supernova.io/design-systems/16150/e56a0e4d-a761-4e85-8806-a94652b9bd8b.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9lNTZhMGU0ZC1hNzYxLTRlODUtODgwNi1hOTQ2NTJiOWJkOGIucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=QnxfUbPacdF8iJP~pmmbG6sOaffwXkicIYTzDQtiJ~TqRa3fZR~odM-l25021XQAmOCJKcWKh1yRtr2eSvzB-nzJB8hMtPSwLIdW2KeTomAiHq1g9lJAN4UTtTkfPPYTsZLZAlaSK2u8RAe189XhDEs9biVH5yigjOg23aFTnTK-vNSDfLNEjwZqsToq7eM3HS5VkeZkkKMNnLi7DIq6SBzTzfTN5MiJjahvZuYNzBrLVZDzTqtxbmL3rgla3wkDJa9PCt0LTwcLr-lQLU04wSnzPIScQdbEOi0IZKZyPjWWrhaOnFgdyK61r32KXUzVta-nWksezQSsLQcmgZs68w__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)](https://www.figma.com/file/ZisCHpJgiaJakbX1SJScvf/Cards?node-id=1%3A2)  
Card Components, Figma composed cards and custom card starter components  
  
[![Magnolia Annotations](https://studio-assets.supernova.io/design-systems/16150/71ecc47d-0477-4a89-9b86-4591ee40dfdd.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC83MWVjYzQ3ZC0wNDc3LTRhODktOWI4Ni00NTkxZWU0MGRmZGQucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=XuUMcjPNBvtO8qzSeahcqhyXVxFBHBSI6-pk8xb4kW-voFqKb-utW90KUpxtQwoAzDU1Xo0ca~0rBwCvuOvFn~ztUrKctSxquQh29FsKzy4vie53TmGTf2PNXJEF8aTrHQ-4B68CV-c5oszZpU~7G5pK8HJSJe0pbxkcg0bxkGLDUzoTeUXpC2ommr1sTtcG8mH45NWr7YzxG5LMtnBrigWc8n8uKgiBydIpQe7W1jfGp9JtTTSY4eB7hTDnskXBXvaEYGS0NG5fU66689yAA4Lm33-owMi94n9KGPX1GmhHZOhXNz-Eak-b1u2tuKbtttcPL5~r~TUYFXwBk8qdaQ__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)](https://www.figma.com/file/5ytPIJhuDabhkf1C1py28P/Cards?node-id=1%3A127)  
Magnolia Annotations, Magnolia specific card annotations  
  
