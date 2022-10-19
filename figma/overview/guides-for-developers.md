
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

![Img](https://studio-assets.supernova.io/design-systems/16150/17516d1c-4a3d-4117-b19e-be19d484704d.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8xNzUxNmQxYy00YTNkLTQxMTctYjE5ZS1iZTE5ZDQ4NDcwNGQucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=lcFrAd7hGPgUiF~SjQRwc19VE-wpn2jpQeugXnlqrrTW1NtaadVeVOCmB8Q2KdCIaMZjGG3gEq3A0ORnp5KJB9OULny4M6W5O2CZ6JQEOerKDgGE~WhqravQzJ4BcLuKSISQ6b9g61Q3bA0mQr1lAkAWGggYsN~HETQVkg-TrI4ExXzhsKP2uqe7nIlKbIrI4hW-xBC1mHFFPL-vlSDwjFR2UqkSgQestGeqiqkGd64erJUwC-O-BQEnzd07xQA4mhoKDzVoUgfAJ7zQJXznh7E1YTDFwvm0HMoGWr2o2lbJ6wdFjJ8ZoRXBD2MVRlLOj6dZDj2AvztuLgvERlLMxw__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

The main file should be inline with what is live or in production and branches are used for exploration.

Note that the [naming conventions in project and component files](https://www.notion.so/Setup-Structure-6100e77469de47638d91056beced11cf) are slightly different.

### Using Components

![Img](https://studio-assets.supernova.io/design-systems/16150/e6daef74-c215-4cdb-a7bb-dedb02780f61.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9lNmRhZWY3NC1jMjE1LTRjZGItYTdiYi1kZWRiMDI3ODBmNjEucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=SyFHbTvZ7~qY-6V--Jfnb01ji96YW4I86Y7yIxj3atowD6jAuCADY6bQuS0BuBTFYaLIhOe87e8TBbOv7dPH14k~MwMuJ5pLs4fayBD-LvN3xkPyK4bio7CqktzZzw31R9QTO4wky28DsShTl3bJNfstZwZLI0byaQLAz4pyQn4-gblc68vbZC3R0U7tMmEOs35-PNYl-VJsuk8wOX-2Bkhd4tmi9cPjoRgbPERgjRFKZedTu5PoK5fB43R3L63ZILWr1AFotmXMKfDfqI6EQim7Yerujd1MCp8itB1WJ6CROIoniGRi43KWnIvARSfIL1jD4yFb7tEODpv~qV-L6w__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

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

![Img](https://studio-assets.supernova.io/design-systems/16150/d91df952-f3c1-4305-a957-22aee888c1dc.jpg?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9kOTFkZjk1Mi1mM2MxLTQzMDUtYTk1Ny0yMmFlZTg4OGMxZGMuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=mDAd4ewhlmlE4vKN7g58ZCJkYZzoPEs7KKGjXLpCpuG5nv~qEBdwmrMTm7k7JWII1WHCdf1VhozdFLPwGuoar2OD0hqch0wgYrXf0p9sBNxK0hBV2scepHPkCZWb~CQ8MlIQ9i6LgOchH5L3Hl4rLPyweI9qBDOMjdVTh1fT9N6JSlOAWjJy00wVswpQs7MTIjhINIsWlkzHBUqTT5~~bhyLhDy8xLmyLXjjQJ9uDOrYA2wF83z~trGfqs1FWwOHnGSpNO4e~oTY~UgU5smXDdKI0xZJ3zNqCsehP~YyfvWp-bGYuEB5nzi0xouQbJormzPHWoxST3Dj64CTuzDpig__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

Free accounts offer a “View-Only” mode that allows you access to browse the file and the additional information listed below.

You can click around the Figma interface to inspect the contents without making any changes to file.

### Inspecting Files

The panel on the right-hand side is the Inspect Panel and this provides additional data to the elements selected in the design.

Figma provides a lot of information, that can be useful or overwhelming. Where possible the design tokens and component information provided *should always be prioritised* over the specific information generated by Figma. This will maintain alignment with our design system.

In the example below the inspect panel shows a number of key pieces of information:

- It is a List Component.

- The variants show the props that are being used on the component.

- The brand colour is displayed with the design token of BP40.

![Img](https://studio-assets.supernova.io/design-systems/16150/c574df5e-cb70-4c53-858c-8d722e9d29e8.jpg?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9jNTc0ZGY1ZS1jYjcwLTRjNTMtODU4Yy04ZDcyMmU5ZDI5ZTguanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=GcRt-RORUyZfYs~ERJCWhIJB~1xsyXG~MpA5fWpC7b0MAhZIeqlg~uKa73QMCYLzGFeP7BCQkFYNSJ-w8DDYwMur1dF3gEbdx2~kT1Y0dVbxFp2sp4okQsTxZoSzWbwGMIB9R9~PAaESsN1SBZgfoXX1zqLIOIvBpbSjceUAPHZyKGXG7vxvOhE6QES03IMyA7g6nt~O1jYsnFzESBCqfakIwrI6rHhER08cMWeg5tkUqw6rrpl59gte8FHd012tqvS80OzDYc3rJOJms0RiqNzDjtDMmjC7nHNSw6Fq8T18yNWVWGJaNtjcyMtawn~WIFmt8z-NLvMit8UhxihGiQ__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

### Redlines

![Img](https://studio-assets.supernova.io/design-systems/16150/8c97eb44-7985-4162-808d-da04ba36e322.jpg?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC84Yzk3ZWI0NC03OTg1LTQxNjItODA4ZC1kYTA0YmEzNmUzMjIuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=BqBeMZwLSNk2jxiNiziyYjLFtNc1Um3e3-XDQ-9Kr5uh86CerjOuuhiUGHEUPcaRVKOy4yrjPbERdpGQzqy9yK4xmE8wD8RK16ebdCu~niyZP0N1twmkDMjxgdFHgf44iX6LlhlOsuxCAWDoc691Ry3reercFNnO~8c0aJ8vP7bVDs8CRcNwtj9ULpPXq8-qsxXBURtSYFjQf6CVkeFGfw9eINobhj9XBKduHwh5CaeDdo1-7zkZpC4c2~wrsaY5d~AademTcMHsDjiI4HTykmCXfw12ABdqwfcijPkPWnNzMFvx4J9D5NvKpwciH-Y4cy0v-OYnjNLxstIBfh5DKQ__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

View only access allows the user to navigate through the layers in the left panel to find specific elements.

Navigating to a desired elements in the main area will allow the user to interrogate the design and measure elements or spacing to neighbouring elements using the dynamic redlines.

The Inspect panel updates with each selected element to provide additional data.

### Exporting Assets

![Img](https://studio-assets.supernova.io/design-systems/16150/4718ad5a-5a7d-4fc7-8e54-7159f837aa1c.jpg?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC80NzE4YWQ1YS01YTdkLTRmYzctOGU1NC03MTU5ZjgzN2FhMWMuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=cZvoVpsvfpM53ZBVsfYWRfr1f3mR0pvXn2puci64kZtK3RMHlV7wwMMqBwRmGjHvRcLMJgtomV7IRZxwczAh25eUtqPuGWXA9QCPMk1MEIg9MjWQV~sBmuUpik-CpAfcSAA5Wh6Nnwb4AMuly-9SzDfRB8y~YUiQr5Y9bH9ois~Abs8ogYocFoAIcvhmUIUC6tEklurO5BZXnTNx7Gjj3xuGBCamlks-PK94ZyZ1uVRORgjfVhZm79iLN5DjvfSQ6WxTirLLcl6DeYOoNg163P-ESeCJP68uHRWR1kpf-3VggPEST18U7SdR4Plyskwm9K40BQR0WGQqXNfNtvOjjw__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

Figma removed the need to request bitmap and SVG assets from the design team in different sizes and formats. Elements embedded in the design that are exportable will appear in the Inspect Panel.

Users can then select the element and one or more formats to export the assets. The range of options will vary depending on the format of the original element.

![Img](https://studio-assets.supernova.io/design-systems/16150/3e27eac8-5d21-4321-ba68-1b3a754bee90.jpg?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8zZTI3ZWFjOC01ZDIxLTQzMjEtYmE2OC0xYjNhNzU0YmVlOTAuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=V-rJWVQSN2Jwjm3h~nMsHelStzHQ86Rc6HrgCxdxQzhiRcSa80iDG6MZkTDWeaUjq9mOvqogflRYLWtbmERHPQF7c9nzyQBQXFbn9h8rnU8n90HBqfywuRzhTNnH0xG~qkDm8rlX3tRwIdcfwLTthBB1NNfGX4Vmksl6h5CSqv6eg1S8A~fBXXhU~2wUnTGnB5YZejWAhQg6XuOnnkgkUdvmCU~~iIVz31xbsVtwtt4y3-1QsttvY-HlXaglOVWa8taJOsR5rUw2tjrrMgl-Yc9Ji6QziXVdKip3Ay-QmHK3tnd1CxUp5v-dMoB0yyYftuoiu-V2dhOD~Sc5VC1nOg__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

If you are trying to export a component you will require view only access to the component library files too.

### Launching Prototypes

![Img](https://studio-assets.supernova.io/design-systems/16150/a73c0f67-1a31-4b82-a150-5e60bfc7c088.jpg?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9hNzNjMGY2Ny0xYTMxLTRiODItYTE1MC01ZTYwYmZjN2MwODguanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=ST1OegToIjU0pMi-7p80NzrCyrcKihmvWyzcvBdD60R9ZaoS7mLsag1LcCb44KAdaWNObA4CTE9Zz8puku-cglb0TZTbY2siexBJ9kAY8TgaTJ~OH855wF5XiVjwFdVwPuA35wpVa0il~fhiwTUfYq7rduCAwtn~Lc7XlnzIGa2nfOQ-nGbqgn5-sPQMeU4sqVqMVEhbRjUR4c-f-ubfYSbkTPF8DthZenTcIIZsa~fjv0v9tvVg~9SPlivLWAdWw9v7V7-rjEpowy9kyNAtrhiUpaQpN-ysiucGwRczOeNmuWqi3lr8ux5B5JfjvPuhdJ0n8iHMJ5bTm2X7VsWvKQ__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

Prototypes are a valuable tool in demonstrating how a flow or functionality should behave. If you wish to launch the prototypes in a file click the play button in the top right bar. This will launch a prototype with additional hotspots to guide you through the flow.

![Img](https://studio-assets.supernova.io/design-systems/16150/179747cf-3a04-468b-92d5-84d77b073877.jpg?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8xNzk3NDdjZi0zYTA0LTQ2OGItOTJkNS04NGQ3N2IwNzM4NzcuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=P78e7-xQWLW67jJPAJuOc-6lyRra9nAOEHq~bz5gDi5RpAXEiWAzwm4EKEbw5CXjdPlC-ujODM19zCtYAlBPcUuDPKfWYWl2EUc1jSl9Fb~daTQbrcL77XkVJ8rYaaij8DNJaap~xVNeHwNwOcWeDm6hY8j-YNgKOLocG6Uov82KXAU1ZGIUZY1JLLPtjQFFuiW5iQ9ZP3Tm-pEDiP5Vj5ysmwDWNFYsAFqqFNunPLnnJimQ-vmg7x8Yk3zAbX274-Leb0nffUT8OIqxyDgInRgH3-Bx51t42yiljrTTkw4hUcDmDbHmd0tY40YahrYH3usGUCB6XT8L28-BYlftLw__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

### Using Comments

![Img](https://studio-assets.supernova.io/design-systems/16150/68d5e81e-5f1a-4d8c-af64-f14713015eec.jpg?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC82OGQ1ZTgxZS01ZjFhLTRkOGMtYWY2NC1mMTQ3MTMwMTVlZWMuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=hKufflcpWZ-1DNcv275nvJOC0MJQYY6Bi44ECqxiAQHCcL0xu5HIifx-Ijsu70-HqB641WaGN-Zz~KGj68sXnINDtigw9p7yQ8Ivb-CA-89hlz25jqYmKkhOIOPO~JCaOh4KFJC92RHQjFWshCAYwSbeuo~~5eeg8nFoHjvQk697vpmQxhGQ3iWUMJ~ZPksN7j8gde62a5LSl2uPiUJ6ZkPg2vtk6NJtbsX-Xmtj-BFeefb2gJvQeM7GRsdg9wlWm5tefLvvnBLCaXtlJ-HnYd~S8mOqllI3Tz9Xgom86eD~kwyTN~8hNwRzT5u7kFF5lXGa50OgazSQEBv3y06mPw__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

Real-time collaboration is a key feature in Figma and inline commenting is one of the quickest and simplest tools on offer.

Clicking on the speech bubble in the top left of pressing “C” on the keyboard launches the comment mode. The user can then click on a specific element or drag around a number of elements on the screen.

This launches a text panel that allows comments to be added around the selected element(s) and provide context. Comments accept “@” comments if you wish to direct feedback to specific users. Links and emojis can also be added in this field to provide context or tone to your comments.

## Figma official video

  
[Open Youtube Video](https://www.youtube.com/embed/B242nuM3y2s)  


## Additional resources

- [Figma’s Guide to the Inspect Pane](https://www.notion.so/Guides-For-Developers-ae44f139b02a40c3b29d0ff78fdb43ad)l