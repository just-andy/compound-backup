
# Guides for Developers

Although Figma is a design tool, its architecture and philosophy is based around reducing the barrier between design and development.

---

## Core Concepts

Engrained into Figma are some core concepts that aim to create a more consistent approach to digital design and share similarities to development practices.

- *Styles* - These use naming conventions that are easily transferable to design tokens, CSS classes and variables.

- *Components & Variants* - A standout feature of Figma is that UI elements can be componentised and have multiple variants, much like props, to create a consistent system language. These are shared across the entire Figma workspace.

- *Auto Layout* - This is an alignment tool for containing elements but mimics the properties of flex box and grid.

- *Branching* - Like Git, Figma files can be branched and merged to keep a consistent source of truth

## How We Use Figma

Compound, our design system, endeavours to use the current live components as the source of truth. Whilst there will continually be ideation and exploration on the system on branches our published “main” branch is always the reference point for work.

### Page Naming

We make use of pages within files to clearly separate our work with key indicators that are easy to scan.

![Img](https://studio-assets.supernova.io/design-systems/16150/17516d1c-4a3d-4117-b19e-be19d484704d.png?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8xNzUxNmQxYy00YTNkLTQxMTctYjE5ZS1iZTE5ZDQ4NDcwNGQucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=ZasN0-B9Iw-ksE9ID6qcdYm1qE7n7~kP9kyedggeNNfvZjhmg9orDV~PsSj5B~nbFRITzJZAsbX5BCkJU5bEtC56xqRa7RV~f3WGht6sHJKHFWwjOEn36IN~TWcjUlvdhYSsf3upYDNib0XSJOhVdZcVZuogONzsn-llZeU2hQihuFn~ikPU-2SRIZFQLW1hJWbjrZp3bvftb~MGn-dvbBH7XMm6LFksmounTGAHV-nPNCejlqFI0d2DGOFB~P7kkLX2ZnoqeLWt~B~M19g2TScKRJ8RPPjOfH3mM2Aho2uwtJO9th7zVtvE02X1J04UglEjVkVSPywXg3lqqQTZdQ__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

The main file should be inline with what is live or in production and branches are used for exploration.

Note that the [naming conventions in project and component files](https://www.notion.so/Setup-Structure-6100e77469de47638d91056beced11cf) are slightly different.

### Using Components

![Img](https://studio-assets.supernova.io/design-systems/16150/e6daef74-c215-4cdb-a7bb-dedb02780f61.png?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9lNmRhZWY3NC1jMjE1LTRjZGItYTdiYi1kZWRiMDI3ODBmNjEucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=ReAgZcCD-4nFoLDF7NheaSteCTVPVr42qQA0j2tgUGo55rjAOtvhZRePxowc1wZy2jRxRyVCTonhJ6wYh0ysGWdX3tMrqjOc92pZGyigVQLDEofLP3nWDNpY8D1tD9Jh1BcLYohSMIyGW9IyHy9pc0hnzzBosOSIhFc3suPWelvHWn6rUlRZA81z-BcEecCs755eGevTjCnsUQg6gw~5hM-01Q00loDJR~46wEgIL85xnmCGe~jv1VD1VsTyNhmYGRHbEeZujgBt8NyW5O~13gYoKXlXa1zwdELxLxQFtOoIau1KK3KVoHS0EMVHWZtDUW4xi57x80andFIn7jP7rA__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

We are working to build up our component library for web and native platforms. Components will be the building blocks for all our UI and we heavily govern their creation to align with developed components and their conventions. Particularly in the naming of components and variants.

### Styles as Design Tokens

Variables are the backbone of any coding language and this has also transitioned into the design world, particularly Figma. We heavily use styles with our own naming convention that we aim to mimic variable values. Our BP90 style is the key to the #147CB3 hex value. We use styles that mimic design tokens for:

- Colours and gradients.

- Typography.

- Shadows.

## Building from Design Files

### Requesting Access

If it is the first time you are accessing a file you must request view-only access for a member of the design team. You will be sent an invite from Figma via email inviting you to set up a free account. View-only access allows a user to navigate files and prototypes as well as inspect or export assets.

*Please note only those with an “@standardlife.com” or "@phoenix.com" email will have access to all our files. Users with other domain names will have to request access for each file.*

### Export Access

Figma requires that view-only users be given access to export and copy assets. Make sure that the file creator has followed the [export access]() steps and enabled it on the file.

## Figma Walkthrough

Figma provides a thorough walkthrough of their interface in [this short video](https://www.youtube.com/watch?v=B242nuM3y2s), this is further detailed below.

### View Only Mode

![Img](https://studio-assets.supernova.io/design-systems/16150/d91df952-f3c1-4305-a957-22aee888c1dc.jpg?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9kOTFkZjk1Mi1mM2MxLTQzMDUtYTk1Ny0yMmFlZTg4OGMxZGMuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=nAe8jGS~uIH71ka6cOddZeZLy5amzS9mFhb~6Wzm4Xdt5sTX0sIMAXRnWwYzhCNATu6lDonrid196XLPGLz2HpDGf99kC0HWKFblzzftYAOkIpOp4us1uUsvPdPRB1Cxp7cBaGbdwid6sqrp9awXvuYkv2jYnGA~QE77H~h-9tu~KADCORvJR27aeB7E4cxn2tKzbrMl2uEeeFeRJu5y5ZqK5M02Y9VwAs413yd1j2a7BLwD8ot0k8LpbPkishq-lkfolutbA6bVg6SKuIbqaZSGRg9P~V23ftLGG0ACBW16weOI82x7oSrrqiZ-0bqfifzE2KD8WDv21lZAzfnt6Q__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

Free accounts offer a “View-Only” mode that allows you access to browse the file and the additional information listed below.

You can click around the Figma interface to inspect the contents without making any changes to file.

### Inspecting Files

The panel on the right-hand side is the Inspect Panel and this provides additional data to the elements selected in the design.

Figma provides a lot of information, that can be useful or overwhelming. Where possible the design tokens and component information provided *should always be prioritised* over the specific information generated by Figma. This will maintain alignment with our design system.

In the example below the inspect panel shows a number of key pieces of information:

- It is a List Component.

- The variants show the props that are being used on the component.

- The brand colour is displayed with the design token of BP40.

![Img](https://studio-assets.supernova.io/design-systems/16150/c574df5e-cb70-4c53-858c-8d722e9d29e8.jpg?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9jNTc0ZGY1ZS1jYjcwLTRjNTMtODU4Yy04ZDcyMmU5ZDI5ZTguanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=aRvWL7AC~xXC2g6iswKeD0bi3sXobmcsjaWvRSyN4cR7DdzHz~CJfEKly~7lxEY14bflZfGTpKP-avpR6lEac-q6LMKHj1LTclKjVg32ug4RNM8t5FVVgGHVsvn3KhvIkk25kl7Zt7Lr98911E6YmmNCwvT6iBI6Ktnif7jUbKAxWJDV5uXW-Y1oDMljwWQrq4~9ipbC2Yh-SYFTNaiu0u6N2nJ8DmMEjC93h-~Inoxm9Z9ifvD45qakEc7-8YNL1U~eXw3~gZoku9jxqcEj1g4RlzQ3KAmefgN2ujsRtcghXNYSzip6L0lDoHedJpFxDJ6c6Dlf9U3iaFf0abmGKw__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

### Redlines

![Img](https://studio-assets.supernova.io/design-systems/16150/8c97eb44-7985-4162-808d-da04ba36e322.jpg?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC84Yzk3ZWI0NC03OTg1LTQxNjItODA4ZC1kYTA0YmEzNmUzMjIuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=HfG7RoswauToabQK17fXRerZw5ncBscx8OlxlUVA2lv9-d2av5J4vyZiUdkeTpalbklT4FVq-UZFnZfD7I7IBrPKkNdIiljHtBt5VogVIQpoWaiNSpi6vZvOdmAIOq4HBIyx3W8bFfPESDK3uwic9NSPcZhwTDV9zy~DycV99f3fyobPGgQGlzTVgS59C6-MNWOfvOo7s6789D0vb421WwfaPDnqj8HY4hAxojB5B~ElR4wnFLCMFOS8Fn9VpR-XlzCkVTQLaVgovJxyQkNpU3LVKORv3c2OWyCdR~~VI6DqhAm4gF7p5ollC8BysigRIfPqVPxIPxDz~mzS7KrtQg__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

View only access allows the user to navigate through the layers in the left panel to find specific elements.

Navigating to a desired elements in the main area will allow the user to interrogate the design and measure elements or spacing to neighbouring elements using the dynamic redlines.

The Inspect panel updates with each selected element to provide additional data.

### Exporting Assets

![Img](https://studio-assets.supernova.io/design-systems/16150/4718ad5a-5a7d-4fc7-8e54-7159f837aa1c.jpg?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC80NzE4YWQ1YS01YTdkLTRmYzctOGU1NC03MTU5ZjgzN2FhMWMuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=Rba9u23P~3Fpolbt79uc3fin7PXjJRDkMtxJ4cqpLaN7znzHwMKuHef5aR5T4ju-p9sAlEeJwX-4bcfiBpWtFql5vl0LfgjY2sahxWjtUlWKz6AjpEwwlFnC-P7kdJW0t0q-qX69c8WfD0AygADRXMhKTjDp15o857LIB3G~iVopnIZXYeUqodJiZ6yJ8v0-v2KGyovTI9fkDXaxKHgjqq9~3MY-31sTFcEJSClHuQhbqxS6OpiFU9Ua8RXgZWPI6AWACo-67IqecuCqmCm5X9IZHUP9CEZWlRooyoTEI2bkj5cX6xLXbDaOXGV0zXU1Duh1g-K2fi34x69xCdsNwQ__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

Figma removed the need to request bitmap and SVG assets from the design team in different sizes and formats. Elements embedded in the design that are exportable will appear in the Inspect Panel.

Users can then select the element and one or more formats to export the assets. The range of options will vary depending on the format of the original element.

![Img](https://studio-assets.supernova.io/design-systems/16150/3e27eac8-5d21-4321-ba68-1b3a754bee90.jpg?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8zZTI3ZWFjOC01ZDIxLTQzMjEtYmE2OC0xYjNhNzU0YmVlOTAuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=D1CrezWWBKk2ISSt8NZHTRgMJMn~gv9LP-UFbM6j7sO6C9HLi529hw5LXmEe7zx-992FXDeC0TNLicUvzOaCpPay5EqlWYkN7yb9KIOIaixhRIaw7tYLFI9nHwl4XeXo13~7SL0wOjovZlVJsE--m8YxKwBNiVy85op83djd8UbymriyFGeTdnRzQHSU~M~t9Zd51h8RAJL12QWvlZa58zW47FiBmr5dCr7iKF3wL4xC9D9oMeJtLnKq7hxhdTccdPrvWdHFGO0Yy9zJj8Y2GiCP2rybpZHq67X4Z1tMwYxJEG6xJj8QdtiNDa8TUyVCcudv7UlUZqiymDcvJFDpoA__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

If you are trying to export a component you will require view only access to the component library files too.

### Launching Prototypes

![Img](https://studio-assets.supernova.io/design-systems/16150/a73c0f67-1a31-4b82-a150-5e60bfc7c088.jpg?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9hNzNjMGY2Ny0xYTMxLTRiODItYTE1MC01ZTYwYmZjN2MwODguanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=AFn-1oNMgbfVW~4sJOY3uz5AANjpYST69wMwLfbtTvdTJeuXWe3Ha-2cnriKZgpLQwvQ1GhNsWHesZSbZh1hFERPz9pAkA94NwMLskvylEZkAN1fAM2s2prvl--E9mS8o6tDUSrcE9T~6g64OfX~UZqatRGHmwyn~FwrKYrqPflVAy2KLWfzwupkvEwneaWpuULishr~6EdatNW1DlYs8HV83pobc-mxC3j0EL6Vt4TrwnIzbMAAtQvYgJC50J9XCKryXgvjYlt8pktWXP~MDCQQiag78y2e-3jriBdyt8IfvpxcrzstYlxXAemyJ9uBc8R6p-VCSpcmhOX7P64dIw__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

Prototypes are a valuable tool in demonstrating how a flow or functionality should behave. If you wish to launch the prototypes in a file click the play button in the top right bar. This will launch a prototype with additional hotspots to guide you through the flow.

![Img](https://studio-assets.supernova.io/design-systems/16150/179747cf-3a04-468b-92d5-84d77b073877.jpg?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8xNzk3NDdjZi0zYTA0LTQ2OGItOTJkNS04NGQ3N2IwNzM4NzcuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=aWtr8~nLORIqJdJdw2VpQxGyr2-0Dl60T9rqffO1-yHp4iwKoxQz9jJMny2qJX6qxggo7jkP~JY9AUEsVCfHGCDXkJQ7dzTkO4dm4L83AlDwmK7GAtHKGdPkhPxbY2LsHO48HAZGq0-4nF~uNKqIlIPV9tR75tjwK5v9vVdwe3nz2j-9JiulA2709Lr28-P~RoCrO0psDUmkyjTc6irzOu9jJ5y~zqdOgaQV~WHPG8uR4KJEPIRp02p47ufD83TA6J61FD-zgIMVSvZHoGmf3W57ppII9I1syG8osJPYGY4jAXzazb2mFj3VeTkJbtfzlkEXOW-q2bAyjMulc2Trtg__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

### Using Comments

![Img](https://studio-assets.supernova.io/design-systems/16150/68d5e81e-5f1a-4d8c-af64-f14713015eec.jpg?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC82OGQ1ZTgxZS01ZjFhLTRkOGMtYWY2NC1mMTQ3MTMwMTVlZWMuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=hvOuP1nxnoe~PGqOejxIqFXvMaSFhz48WMV9klCaIjkX~TMVgXAnZMeef3GLzIpiRBUXWQiYQwbmrVOpS0jIQ3qjAPm2WfHoFRX-a22j4DkubODFQ9eSZYKBULCyaR2E5Xgj-QHQufZjxdKCOxuOmd-O3HHCjkRXV2P~JUP3ssz7vDHEb5NGEgVrZ5wpwSKjJ78lp0wSuTLj8fxQMZO4efp9FBKpNhFGjJ2PrOONNmDLzUx7SsdQRiyJ1qDOIjdPlUw0L58Kxp1ZKxnxaMd8-gIuhWB-piqikiDuhfLM1OV3DoH6yVIZmcATO8g67MBcFCxFMXDAfXS2xyIZa1f6Qg__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

Real-time collaboration is a key feature in Figma and inline commenting is one of the quickest and simplest tools on offer.

Clicking on the speech bubble in the top left of pressing “C” on the keyboard launches the comment mode. The user can then click on a specific element or drag around a number of elements on the screen.

This launches a text panel that allows comments to be added around the selected element(s) and provide context. Comments accept “@” comments if you wish to direct feedback to specific users. Links and emojis can also be added in this field to provide context or tone to your comments.

## Figma official video

  
[Open Youtube Video](https://www.youtube.com/embed/B242nuM3y2s)  


## Additional resources

- [Figma’s Guide to the Inspect Pane](https://www.notion.so/Guides-For-Developers-ae44f139b02a40c3b29d0ff78fdb43ad)l