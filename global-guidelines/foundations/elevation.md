
# Elevation

This principle relates to the distance of a component from the user, as a result this affects hierachy, colours and shadows on the interface.

---

## Levels

Elevation can mean many things across design and development but keep it in simple, generic terminology of levels. The higher the level the closer it is to the screen.

Our base level, level 0, is the main content area. On top of this other components can be placed to show their levels. You can see where various components sit at different levels.

![Img](https://studio-assets.supernova.io/design-systems/16150/54437d9d-3906-445c-9c85-cf2d9f14fbf4.jpg?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC81NDQzN2Q5ZC0zOTA2LTQ0NWMtOWM4NS1jZjJkOWYxNGZiZjQuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=TsJde5cpNECIBpePlaekNgX0RuN~bjMaGho09KfQ~8td0MeGp8rzBkAoEuXbBLzIIHSSbuS8PaVPzwnB9Vc6FZk-~J6DLMo4v1DeMTZxoMec7qVKzBmDIjZuuOkmoRpcVIulT7Vpz3F1NqSCbteaB~Ch7uXdk6u0~CW6qvNfP-FzyMv3usElt8bjpdnohwA-zUTpdjAEO4WOEW-OkRt3eohcTTvKEmq934ARf-2AnLbKZlBg3IsTkmxGcGWOCExoZhKFlYgf03My3RjYTWScncH3QNwFoAAkrHJZ7qPdjcO7SL4ezO76hctknF~YOjeLd6XQXqYuAFSe5rQfHmLwgA__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

## Shadow, Layers and Levels

Levels are used to separate key components based on their usage, components in the overlays you would always want to be above everything else.

Within each level there are a degree off layers to show depth in the interface. Cards is the most common example.

A nested card will be on Level 0 but could have a tooltip component that displays above it. We use a shadow to show there is a layer above this. 

In the example below, card A has no shadow but tooltip B has a Shadow 10 applied. If we took the example of card C that sits on a background then Shadow 10 is applied to show this is a layer above. In this instance, tooltip D uses Shadow 20 to show a greater degree of depth.

![Img](https://studio-assets.supernova.io/design-systems/16150/6f05f5d0-7c57-4216-8d18-b7608d56b34d.jpg?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC82ZjA1ZjVkMC03YzU3LTQyMTYtOGQxOC1iNzYwOGQ1NmIzNGQuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=EUoiY45mzcp6KIouYvMcBIIDyZQNZv1NfTNPJSqfRN917ZUu4UsGa4ktJQU7GHDDYPLl1vCl6LAueLzKUvd~HwQsrHnQKvdmKFrhoZkzzDza6hVIciUDUTuv2I40Rm4IwJxDZ-IHDHdj7EPZOcBDyz~8oMQjxBNpk7J67ob6k6tEBNHo82Uh-MV7iHbXEAtcFUMyUa-I1X2xDy3vndSZlbqlA7R1nQPMpuaoXYUjSWQEa9AMHVqykziRBhCSiCay7C8uL0tEf8S44YZFN2hpQLXjTcbPgHOcrN0L358aTRhFFkBoW-W9vXbjWomBpRX0nGwhc4TfXjBbjxXwtx3EuA__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

There is no strict formula to the shadows but the best mental modal is to think that layers stacked on top of each other should have a greater depth.

By using levels and layers together we can work with a more manageable set of shadow styles.

## Shadow Styles