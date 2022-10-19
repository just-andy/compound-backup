
# Tooltip

This layer component provide supporting information when triggered by hover or focus events. Information should be helpful and concise

---

## Key Points

- Tooltips are trigger by an icon button, this should be within close proximity to the content the tooltip is supporting

- Tooltips should only contain text, for more complex content use a popover

- Tooltips are triggered on hover or by being tapped on touch devices

- Tooltips can be displayed in multiple orientations

## Usage

  
![Tooltip](https://studio-assets.supernova.io/design-systems/16150/c3bd6a58-b6d5-4101-b798-9c7fc6a254f3.png?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9jM2JkNmE1OC1iNmQ1LTQxMDEtYjc5OC05YzdmYzZhMjU0ZjMucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=fgVS1uVmT93YBnjT78hRe31vqBL~MyLBUq1GArEVDtnI63X93-DnT56rihydzUMGaRXv5sSyViHKZfpvC8guSTjLfCdk2x5ZcXmppN3l36HBHn~0P4BhDucKgeGt1NfJqTxmUaLNEgtUd5Qkt-m~N9G4~HIO0yFYGEAYir0XBktemT0e4lejhl0-FPI85xdZUFXQ5mHI-MttZ9v4rOIeEaPn3NdegwS7pzg1raw8Cg6pYYPrZutwFbYkhbFv6MMT7CS3Chgb18tXWkdCwYcbzaHdCSULD5-yZJvz8AOmPHjZM8aB9YIDVC37-KwtqMrkI0w7MCxacxqvOVJdjfFu-g__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
Tooltip, Example of a tooltip placed next to a button  
  


Tooltips require an icon button to trigger their display. The button can be triggered by tapping or hover events.

The content within a tooltip is text only, and this text should be concise and helpful. The tooltip will expand as the text wraps over multiple lines. The width of the tooltip can be adjusted but should not exceed our [maximum line-length limit]().

### Orientation

  
![Orientations](https://studio-assets.supernova.io/design-systems/16150/5a91ab95-83d1-4240-8c69-6c1b81d9e550.png?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC81YTkxYWI5NS04M2QxLTQyNDAtOGM2OS02YzFiODFkOWU1NTAucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=S-CdWOIDZnJcfEeh6blyZk3QN9Utfjgts-zpLIsN7WsL1ZQVuX~GcQ8cY2QDpJEwRuLgg63zcLiHVGIbXeyRGLfldw73q~YT9IzELckDmKwo5LBq30E6ePL2xcnXtaUZEFU8AuGeRJ6~Zqx-XrX73ynAC~EMAskNeE7NmOC9YmEnMfek2lgRfg5JrW5h9sVwCg1NwCRYIQubmL4Qap0z~LHYoyhyfanTw24E5S-3rEPQMVv3rQpr13hkGM2hmwL3~P-nw8evO0c2KT3QqCQtc~22kcQo5zz5l5GPD-azQ02bhS-StZ0OgK5XCvETonPZwL7NHLwH3r96PgAZG4pb6Q__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
Orientations, Examples of the tooltip orientation  
  


Tooltips can be placer around all four sized of the icon button depending on their usage in the overall UI. If the containing text greatly increases the height then the arrow indicator can move to an edge of a side as required.

  
![Edges](https://studio-assets.supernova.io/design-systems/16150/96830d30-f8ad-4c00-80d8-29467bc547ec.png?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC85NjgzMGQzMC1mOGFkLTRjMDAtODBkOC0yOTQ2N2JjNTQ3ZWMucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=CiURUns3JBWDFeCwCza7hJ4iEaKbcbFUB0F9y4HuGX4Fl7-U1oKmpmotCWTYvsXKY0qf7QF7k5nqtIsJuaYFrBBU6LADkPqxpzBzFLZifZnasU60G6oLCtBc~Cdyx3m7x0FYraMh4N5qCkyMpnVQ4AOyFa89zQiUKdml07FnpPErgyY4Q9ogRcbmGSuYytz6c7wffIzwcDc9dCd0BR9SV6IPwFrEEjwcxpKQ7kyZiNiykXxosc9RiZqwU-B2MQRtkwYnAhpQiTZeZSMSeQZFknnPB8RDFbg8aONg2Aw2TabY4Qc5mZ1oJel9-ogCr~qf~aFRw3sMu3H6JAyBdaNYdA__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
Edges, Indicators can be positioned on the edge of each orientation  
  


## When Not To Use

Tooltips should not be used:

- When the textual information contained within is required by the user to complete an action. This content should be placed in helper text or an [alert component ]()within the UI

- Do not include media or other interactive elements within a tooltip, use a popover instead

## File Links

  
[![Figma Component](https://studio-assets.supernova.io/design-systems/16150/7af209d1-f13b-4117-9957-670c6f49da5b.png?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC83YWYyMDlkMS1mMTNiLTQxMTctOTk1Ny02NzBjNmY0OWRhNWIucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=PGbjGacrxpFferazGsGlVqUOqMxDgROKB6OwbgX4M~vVBDLYRdYifFFEke5fjD7TcjVn4AoT1GFQ7HtoKnefVpJHb0Yr3afS4VEDQ3VvOqaQutbTw6vS~XHvrIiAQh5s-oIdYYyg1pykaJjx1iiebNTH41K22B-e6NjL8D3Qmuo4qABUcNGafALOFvkz8i2kyVHaBQ59zQKbkMo7d08R8caZsmxgzOHyEK6dwZq8UIK0cu-p9qtU5l5Fmw22-pDdrwP3OpD6wxmh4fEQSbaMMKYZk2xXr3tDWSk4ucUZzweYd8lKtP2agXYwasild1Wf9TtKqqVK5qLc13-C8bNYvA__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)](https://www.figma.com/file/SGjaBt8oRUHGAO4ZyCM7rY/Tooltips)  
Figma Component, Tooltips Figma component  
  
