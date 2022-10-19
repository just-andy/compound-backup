
# Tabs

Tabs are used to group related content in the same area of a single page

---

## Key Points

- Tabs are available in two styles and each style scales across three sizes

- Tab labels should be short, ideally one word

- Tabs are available light and inverted

- Top border tabs are best suited when all tabs can be displayed on the screen

- Bottom border tabs are ideal when there are more tabs that the viewport can accomodate

## Usage

Tabs should be used to display related content within the same area in the page hierarchy. Although there are two styles each is best suited to a specific application.

### Top Border

![Img](https://studio-assets.supernova.io/design-systems/16150/79b2ec38-efbd-4d62-ab90-7fcdcf256ba6.jpg?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC83OWIyZWMzOC1lZmJkLTRkNjItYWI5MC03ZmNkY2YyNTZiYTYuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=D5jiYrRfetSY14hNECbnJJByW4N7Lpo4WE2ix6bYBvvVgi~mcU9V0YQIGJyIAqGjyo2xKabI4gKKA-kHfzdv50VM-MCCAX0EnJsVPsjSAJRFf5CcVi1a3x0gYeNat0UHOmjzPT~OoEZKq7dzziCNSruG93qUHacArbKE~QD0Y7pT-ssw7cOB~K-yBthrcsquxfGLt5Mv-Y26cahxOQ6KC0IZEX5eQdg~3oJmCXcf2NzdAFB-erbbC6FziEJUBjSwob3k1GunSqZgXjQgvZvSHRhsbRCCx35o82XZWp5F~ZbDiwxTFhhuu4yf40oVyTMHDr9QOzTeIVoTeqb3J6qiew__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

Tabs with a top border have a style more suited to situations where all tabs will be visible on the user's screen. Because of their skeuomorphic design which replicated a paper folder, they are best to be always visible. The bottom divider is removed on the active tab to show the link between the content and tab, like a paper folder.

### Bottom Border

![Img](https://studio-assets.supernova.io/design-systems/16150/4dcd2117-e62e-49a3-881f-9ea539b86589.jpg?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC80ZGNkMjExNy1lNjJlLTQ5YTMtODgxZi05ZWE1MzliODY1ODkuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=YphwMvqylGANFzoUT42U3Edgox1x7zdzXlZFe3SBgrdbBoo9RUqv10rhxuVMlnNigkiIz2p17hbeV0t7BBva~kIXuL7sk8jGOmx3n~QuZWB7w6R4AGQm4aVTkgsijo3ely8iOIUqZ5HDPejme2fuPkXjnSdc7hmkKso~mmQd8OMSlBQJW-GrTWBM0WpE~y5uneSqWtR4RHZcAgd1z9e-4bIQ61y2IDBnl6DPYsG6986PwB-fbj~mDeEIpXG0~Ocj85vx~xPY4U8aHqaV2AfIRuqNcKKKQYKCzgSm2S4zNXH3w9GT-o36j~leA5lh9QglmqMQ2LIYFrjwEWZR5cf1jw__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

This style is suited to situation where the number of tabs or their labels will exceed the available viewport space. The container around these tabs displays a fade indicating there is more content off the viewport that can be navigated too.

*Note:* Scrolling should be a fallback for edge cases. Content should focus on displaying as many navigational tabs as possible.

### Sizing

Each tab component is available in three sizes; small, default and large. Based on this context of the page the sizes can either be manually set to one size or set to respond across all sizes based on the viewport width.

## Behaviour

The interaction for each tab is the same. When a user clicks on a tab the area of content directly below it shows content.

The active tab has a specific style that visually makes it appear closer.

  
[![Figma Components](https://studio-assets.supernova.io/design-systems/16150/31d6f7d7-27b5-4b32-b320-f2007257e307.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8zMWQ2ZjdkNy0yN2I1LTRiMzItYjMyMC1mMjAwNzI1N2UzMDcucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=adVnbKCerfC-V-M4i-gOU7PZAjLLdi5ZWUpFPajnJUFrd9YjHTgHvodycq-Upo0HIC6I4UBW1aIx16cSQj4i-A8N3HCN~tSR4Fu4vyW4ROz8vPMATATofH~9AGah3aJzaM-duefYYdWKFlWrfei1kpTs0b2fuIYGmP0MauexnM2g03UldxcdJ0JAOlO0G2wkyK~VoZjZStApMANw2fjPOoStZVbfCweKyXUwd~dI2qWPCUrabkDqcRbzCW5FW3CrChNuB3pl0s7tiBSum4HXUegaMCPBTsKR44sH5pvt2ryuZM7W2WZ7xZ1c9F-ptqfbjiHuio3yWMH-FJviYktH-Q__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)](https://www.figma.com/file/tV0UdsxUnOj4ZE8cwC6W2o/Tabs)  
Figma Components, Both styles of tab as a figma component.  
  
[![Annotations](https://studio-assets.supernova.io/design-systems/16150/bdc1a2a7-062d-4d15-aeb5-79a4afd29b02.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9iZGMxYTJhNy0wNjJkLTRkMTUtYWViNS03OWE0YWZkMjliMDIucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=OTfS4OrImAnFuezDfmGQVlFDe6VuxOXtYBBziDmTlbxtlD5fOwefMdmB9QSv6rGC1Vw9vAUtOIDOY5TXF1mDk9uD2iYQgD0RRuW8DnjGXoKkIOeJL3zgiMLYXGgdR5kSSEcR4hATOp-nr99vF9hXumnwrZ5JNiVOFUSX8i334KLjYk5kWcVGNLtCQNWF9ylfByvjTTy7OkQDyj7CV9PRP9ZmcX5qnXlgpOgiDyZ0cECP2GfjM3Nr6Vvu7Sm1iop7QS2NAz7rHnXXMgBNmoNkMzUJ8l99Noag3pO1p5eOVxH2c0KlqYmtt4mBgRt889a~esZ6mNsnVNTxUTH4DdBKVg__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)](https://www.figma.com/file/V0r6OpbkZw2UNCl9vf49uG/Tabs)  
Annotations, Annotation for both styles of tabs.  
  
