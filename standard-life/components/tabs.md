
# Tabs

Tabs are used to group related content in the same area of a single page

---

## Key Points

- Tabs are a navigation elements that allow users to easily access different areas of an application or different parts of an individual page

- In Compound, tabs are available in two styles, and each style scales across three sizes and in [light and inverted themes]()

- Tab labels should be short, ideally one word

- Top border tabs are best suited when all tabs can be displayed on the screen

- Bottom border tabs are ideal when there are more tabs that the viewport can accommodate

## Usage

Tabs should be used to display related content within the same area in the page hierarchy. Although there are two styles each is best suited to a specific application.

### Top Border

  
![Top Border Tabs](https://studio-assets.supernova.io/design-systems/16150/1ebbef83-198e-486b-90e1-2cf7f21466b6.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8xZWJiZWY4My0xOThlLTQ4NmItOTBlMS0yY2Y3ZjIxNDY2YjYucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=XYCqxDPy8cyzv5N4LkkHpno7sr3xpy0g5TZ4FI~GEL537X2sp1rU794VMjrQktSE4YpZVlITlyofER~as-iPovD19G4SDANFQhNy1YZcUKzsaPfxOJes8sx9afSME5Y86Vr3Vx50sPY6KasPd1c885QQnflawI0dqtihGair-B~L2eSd8ZvvrfK8n5Z11kJ0HfRI2zGchE6Z54oTPaPN7T2-JOelfiORokPkUAQ1QPm6kXiRGyo65j9~vDueh~WtYBf3-018xorRlutQl8XiO7Viis3P8VGktE1eWsBs1H0Cs1e5mfAR2CD5I07ooPCSpUZaxsv5Ix0kuBVQJjQi~Q__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
Top Border Tabs  


Tabs with a top border have a style more suited to situations where all tabs will be visible on the user's screen. Because of their skeuomorphic design which replicated a paper folder, they are best to be always visible. The bottom divider is removed on the active tab to show the link between the content and tab, like a paper folder.

### Bottom Border

  
![Top Bottom Tabs](https://studio-assets.supernova.io/design-systems/16150/a019e04a-843d-4cb7-b3bd-a77784e67dc0.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9hMDE5ZTA0YS04NDNkLTRjYjctYjNiZC1hNzc3ODRlNjdkYzAucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=XuHteGzardA~WqBzJzPz3w765giqwZcqKB4aGgj6p~gD~qE9-TudPgLRZYcdVughQcpzNLe0eEOM8K4gs2Xt4f-vc-JfXTK3zsNdeYibq0qaOyCxfMkSpj~0ERS4FYxpOZ~h2rNjSU9cVzMrHHUimhaNT2DZlghOoUQsNVFMCd7SxBlPXQPfQJP-i~8CLZ06YvQ-RF6gz--nZsQ8a0k1lFcQpa3zvWleRpcpVuczc-btF0I1Ny8wQDAoj~vXVaKEvuhSF5d04S~FbowVK2WIo00vSyiAT3lwIEA5LVzL4-EJIVJptBBLsQy~Ea7wyK3bv1yvIxKfWLYkqH5hMsKyHA__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
Top Bottom Tabs  


This style is suited to situations where the number of tabs or their labels will exceed the available viewport space. The container around these tabs displays a fade indicating there is more content off the viewport that can be navigated too.

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
  
