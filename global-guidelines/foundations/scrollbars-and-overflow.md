
# Scrollbars & Overflow

Scrollbars and overflow work together to indicate to users that there is more content outside the view of a container.

---

There are instances in UI design where content is larger than the container it is placed within. In these instances, we use a CSS property `overflow: scroll` which indicates to the browser to display a scrollbar.

## Scrollbars

Native scrollbars display horizontally or vertically in the following scenarios:

- When it’s not possible to stack or wrap the content within the available area of the viewport e.g. Magnolia tables

- When component’s own properties requires it e.g. Horizontal Tabs

- When it helps to constrain and fit on the page unusual items e.g. a long in text modal window

The browser defines scrollbar styles and we should not override them with CSS styles.

![Img](https://studio-assets.supernova.io/design-systems/16150/fde84876-9171-4608-9819-05aa5c6e38fa.jpg?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9mZGU4NDg3Ni05MTcxLTQ2MDgtOTgxOS0wNWFhNWM2ZTM4ZmEuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=mUarLHC4DNLEecnSK9FFyvSVovywJGmSEZMXGUYqiUY4OLDRs1VYPNaoXNTDM5cETDqsJo4RDd-0jvDWRayuatdWv2aruJkL1HE6swYSEMS0xJeUrpXc4DgXAOg7R870hsmd9~J49fl~XLclJSncufQzYav4w6cUgrjSevIsychaTZYRrQbuLsfLjkDEguY0DAG~1BZEsYCCNlHrMFxely6hgvbn2TgzWVigw0pb~TTktQw1wWC9I4CiSAHC41~UE06Y-STN88Vfg7uVKbSlV8V2JcCqdZG2KqpJ4gFsZxebMjT5WtSiLciNqgMYSgEGywSQJdX5rfWZZ~VlfLy~5g__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

*Horizontal scroll bars:*

- This appears at the bottom of the container

- The padding between the component and the scroll bar should follow our [layout and spacing guidelines]()

- The padding between the scroll bar and the next section should also be sufficient, larger than between the scroll bar and the component it belongs to, to indicate the grouping

*Vertical scroll:*

- A vertical scroll bar gets appears automatically along the right edge of the component

- Designs should be considerate of how scrollbars appear in different browsers. Overuse can add additional noise to the screen

- To visually indicate to a user that content is available off screen, some browser scrollbars do not display by default, a gradient fade should be placed at the edge the offscreen content is located

## Overflows

Overflows are [fading gradients]() indicating there is more text or content or beyond the limits of the container. They are presented in different orientations and colours to be used in various scenarios.

![Img](https://studio-assets.supernova.io/design-systems/16150/ca545922-def5-4c44-8122-120352101fd3.jpg?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9jYTU0NTkyMi1kZWY1LTRjNDQtODEyMi0xMjAzNTIxMDFmZDMuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=TTcIgW3GhEK5eftzJmKzSm6UY8hkpLW9FTSB-lW9YsAsZf-jQycaSy2oZLCGvk-iQOmNLPxGB5wRQS2HlXvk2uzPHjwMyivcu5me7L2xvrELQ1GvikdVgQrnfug0uSPrPnRrKJ3qiz2nG7-tTj2Ce8XGL3bJQ9HFSYjb-dQ3ra3ANl1s0uR4Pwx8wh0AqWJpaNwkWjG0aG0CDRnu~Ct5pukcKCwhtVKKbNl0Sp~~s6XDCdbPOJulD5t8b5l85tK0CLtvIVEHRpAU4oRzGQP~yGJFi81AZkwm4mcfxWDX8g67ypazBYGDXonuh0Fxv-TyVa369dnDXPAaQMN62UKVIQ__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

In the example of the Tabs component below, they display to the user that further items are off-screen.

![Img](https://studio-assets.supernova.io/design-systems/16150/c4d8c973-b5a2-468e-ae0d-da7f755b8238.jpg?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9jNGQ4Yzk3My1iNWEyLTQ2OGUtYWUwZC1kYTdmNzU1YjgyMzguanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=PlIbMQRsoZkv9h8eIs-JO4iGQbyFiCKjIGg1WRYZ1oMavGK4irWedbE9C8~8TGXgPwyyeQoHqFgDo0a859Cnb16nck3fslnHEIh8eGJkHpSsRldTOmkTbzoe1LbTyEECBxcXpeKuAVu4FYZ1ITh8zvDmF6wgWuMGtV66NBkyXr48FjMB4XhPASsyUZnA09TU4bxqsufv6L3oCo6joJ6BwzshwvlV7Kq4ZfbCT9SCO~3TfUwN9KjYPfve32-WsiPLEhZz4ephNImdzPVdrrDwlslU7yH3NrpgDK8IfgIUIgGnxTAYfmdm-iT4tsb-I8166w5hRCXQ2qqw5xqDUudHMw__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)