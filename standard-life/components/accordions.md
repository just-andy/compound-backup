
# Accordions

Accordions are components that allow sections of content to be vertically displayed on a page. The header for each section controls if that content is expanded or collapsed.

---

## Key Points

- Every accordion should have a clear header that identifies what content is collapsed and hidden

- Accordions can have one or no accordion content open on first page load

- Accordions should be able to be opened by default if they are triggered by a deep link

## Usage

The accordion component makes it possible to display large amounts of content in a small space through controlled disclosure. Whilst this adds an extra click to the user finding content it keeps related content together and the header will provide key navigation.

  
![Card and Accordion](https://studio-assets.supernova.io/design-systems/16150/ab6212f5-a8a4-4fb7-b256-cd537dd0cbb1.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9hYjYyMTJmNS1hOGE0LTRmYjctYjI1Ni1jZDUzN2RkMGNiYjEucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=IX42iiiIky5yrUUAE~loQsh9EDs56RmxymnJOudh2LHQS6lrdOGrs613jNFK2jaivlaBEQmN382AVRUfi9esX28IPBK3oAm3fCMEFNjv93hgOXVJX6ry2bilO3IjID1ONmhxDEsnZul20wtPSscjsk2pfthkBUcO72xV8Lt7XHtwJVHAe3USv9OouGJ6JgL18b00psGGsK7rme4Yh9SkcipYugRSB~6x2W~wU6elcvkBtZKHsZqC7k-cjuIcWmUrJb5MOKhlPJKq1Ecfg1L1y4gOrD~xyxAfUmAiTm1OZ1aB9JRbJPoBDHHy0U9JdS0ch7zp9cIOKHOi9oHn1j9-hw__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
Card and Accordion, Example of an accordion nested inside an card  
  


Accordions can be placed on a page or inside other components such as a card. Be aware that the overall height of the page or container will change depending on the section(s) which are opened.

  
![Accordion on a Page](https://studio-assets.supernova.io/design-systems/16150/c180ae9a-7a05-47bb-a9ec-d75f6b29141f.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9jMTgwYWU5YS03YTA1LTQ3YmItYTllYy1kNzVmNmIyOTE0MWYucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=jo2iMWKK1HA3M08A9lC1rjICNImRudrPg2qOCT-npKbwJA~SAY11sdQNeLXOm4nLSUX4hvqZwagEWZUX1-AHsqs2sczUT9sgQ7Zsi0We1jvyf1WsG-bQH6J2oUUnQmrpKTGG~c7K1PhpTTi77J5et4PbKQujoiqRhw~o~CIbD23WpYKQBFom3~pJ478pUNbaalSYKiXT1yh8wiDMVUmkSX3NQhyq54dMxuGpuBbbdWqakj-aMwwG4CsfpgjDexWOgwBSEwY5q9v9tryp~a1kQPnYDasyh3rzGjQmUjxJOQR3xLyEQfnBvH01moLUp4mjpAH8uw7MaiiXwuUWHUycOw__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
Accordion on a Page, Example of an accordion on a page background  
  


## Behaviour

To keep content related within their container the following two changes happen:

- When the accordion is open the arrow icon points up,  the icon down when collapsed

- The divider line stays at the bottom of each section when expanded, this differentiates each section

The whole header section should be tappable to trigger the expance/collapse action.

## File Links

  
[![Figma Component](https://studio-assets.supernova.io/design-systems/16150/05958447-7f1c-45eb-aabe-b9ee21efa641.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8wNTk1ODQ0Ny03ZjFjLTQ1ZWItYWFiZS1iOWVlMjFlZmE2NDEucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=Oo6RmtFebdDMP8w-av27MxnPSn2tZ13k2U2rR~v55v93Uw1OQi2DhjkeDUOMmuy6JiFrhxOOmDnxuxx2Ekahyn1aA3tBMGk8j4kaXGcCa4rrh9vRsnzEzvQEk9jqUbfo16K3mVU0XsGc3euic2Ey41353Q~1-MrPvdS-1GlHY~kw4E7k~6UXYQMN-XJZGm356yQ7uONP7Y4o1yZOe6RlRVK-Vx5Sv6XPYu0WE8Adq5bDJ5GrIRAzjDJVu3aBweAEKsdzqg-HV5zLzcvjf~W5vYkaZgUSjkWGdtrOtuIlty6Eb1UFENbfWuXMz0UGkl17P53h2nN8jtWaWTCJJwli~Q__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)](https://www.figma.com/file/FIcmCWBV2EQgCFJzlWR7yR/Accordion)  
Figma Component, Accordion component  
  
