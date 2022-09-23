
# Scrollbars & Overflow

Scrollbars and overflow work together to indicate to users that there is more content outside the view of a container.

---

There are instances in UI design where content is larger than the container it is placed within. In these instances, we use a CSS property `overflow: scroll` which indicates to the browser to display a scrollbar.

## Scrollbars

Native Scrollbar display horizontally or vertically in the following scenarios:

- When it’s not possible to stack or wrap the content within the available area of the viewport e.g. Magnolia tables

- When component’s own properties requires it e.g. Horizontal Tabs

- When it helps to constrain and fit on the page unusual items e.g. a long in text modal window

The browser defines scrollbar styles and we should not override them with CSS styles.

![Img](https://studio-assets.supernova.io/design-systems/16150/fde84876-9171-4608-9819-05aa5c6e38fa.jpg?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9mZGU4NDg3Ni05MTcxLTQ2MDgtOTgxOS0wNWFhNWM2ZTM4ZmEuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=adBYqRAcNeBHaYXwLtLQKYhYdpuBuk1iiSJx6ztEIIpGOFFPaoLxlkVrF2hFtwqhZ4-Y-wRF4kjrGGT03WTkdLGKwzxjrYtkG0IstBFOvwLe~8vwQOPTrGQ51M9VkdPOyfLJq3ju1OcKj3qLyUP4dEYXTr47NvZ9o~sw20oon4uRnGMssdXcA5bbdZVcaueJcgl58aJenvLDXQTY3ipAz3pQf2m9hy6CaLNyjVeAM~RC8g1t4wct8yEKuHwiJqjbOp5efTOHoalPIvSZNrkkCYhdBtg-I7q4jb439LNL2WM7MtUrVp4UHuppMq-A3q8lbYdYR1FHNCOFebObGzlVLQ__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

*Horizontal scroll bars:*

- This appears at the bottom of the container

- The padding between the component and the scroll bar should follow our [layout and spacing guidelines]()

- The padding between the scroll bar and the next section should also be sufficient, larger than between the scroll bar and the component it belongs to, to indicate the grouping

*Vertical scroll:*

- A vertical scroll bar gets appears automatically along the right edge of the component.

Designs should be considerate of how scrollbars appear in different browsers. Overuse can add additional noise to the screen.

To visually indicate to a user that content is available off screen, some browser scrollbars do not display by default, a gradient fade should be placed at the edge the offscreen content is located.

## Overflows

Overflows are [fading gradients]() indicating there is more text or content or beyond the limits of the container. They are presented in different orientations and colours to be used in various scenarios.

![Img](https://studio-assets.supernova.io/design-systems/16150/ca545922-def5-4c44-8122-120352101fd3.jpg?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9jYTU0NTkyMi1kZWY1LTRjNDQtODEyMi0xMjAzNTIxMDFmZDMuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=CE-ulmavw66zEdZsvZ-flEV0ygGQjbnJycdKvSuIrF64Rvn1lzogbLsNqalWPvtayu5w73oUXHL94u57pOHILYvYjBC6BFKnnXnxCO89x7t3peUeuN2jgrCPPChHW5jN9554yD~DDqgYimkLk6wuahVk5Em2g7i1VchebsU0UjxONGO8GmB4Swdizs19AxqVqnVw2dzcHS6~rDnN~oeGx0lmVrxQD60-X988WZrz0-ECMyqR1iyA3v3F5qbddI78ok2miDMCOFKRsx2RLO7Ze0ziJvNQhstCBMUT-6GGUcSW1zgRy8cDnukXi8SNjetT29gdDA04j9SkG2WgrH7Amw__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

In the example of the Tabs component below, they display to the user the further items are off to the right.

![Img](https://studio-assets.supernova.io/design-systems/16150/c4d8c973-b5a2-468e-ae0d-da7f755b8238.jpg?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9jNGQ4Yzk3My1iNWEyLTQ2OGUtYWUwZC1kYTdmNzU1YjgyMzguanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=E9Wlem9slrss2f1lXfPo-VjgE~uMtl8TXAdRl2j1Iky1miSl-5ZLTt6XBixZ-OrPh~7qBw5yd-B43oGg3F0KB2Atrx7nAwevAoSRR2saAE5~6gMDqvSt-cXPMG~9TVmzYYnc5V2oamW7rnin0YHtdMFR1N~2~Ao1dKLrfjICemsZMBw4c5JWUi5fwWMAxxF2XUpyK5t-Q2pft0yj~-bs3oCvfcYoY7vW4qanH4Rjr7mBCV2UIHLxWKEESutzCBwTy78aBGGHrOXRcsuq7F0fv1taTWI1ZqJXDEHC~9-mk3TZHYRdsl~tcI6hU6fu8hUykRw60hlRqRCGvRQ1XDTBtQ__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)