
# Popover

A layer component which can contain custom content and is triggered by hover or focus events. 

---

## Key Points

- To create contrast the popovers in the light theme use a dark background, and the dark theme uses a light background

- Popovers are trigger by an icon button, this should be within close proximity to the content the tooltip is supporting

- Popovers can contain text, media and other content

- Popovers are triggered on hover or by being tapped on touch devices

- Popovers can be displayed in multiple orientations

- For text only content use a [tooltip]() components

## Usage

Popovers have the same use cases as [tooltips]() but the distinct difference is that the content can be more complex than just text, such as media and other components.

To stand out from the main content popovers use the opposite surface colour. In the light theme the background is the dark card background and in the dark theme it is visa versa.

  
![Popover](https://studio-assets.supernova.io/design-systems/16150/1bd3b88c-ae1f-434c-ba35-f0aa0f6f92a8.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8xYmQzYjg4Yy1hZTFmLTQzNGMtYmEzNS1mMGFhMGY2ZjkyYTgucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=IQWs9XS7ETya8algCtoqVDWpntH2vC0RBqvVWbgn~3q1~VAQ3VVQ6mVt1W76JS0qc5cpYVV8sIXadjlQNVNT2ZTLAanqpTDDReahJbwfcH3QGPzu2cZXEXgZxcKAchWgtXID~ItCdrkUE8ig3zQTXH6INKMX5OHxvx~LOklDlSR-j9oktpYh8S9R6Uct4xySn~S5VwQcmnuxy05ouhHARQraALaYRHGeTCR5TdGl8RgNCfBoNnN0RvTifzeQ6VCEMzBTJO3PGkNKY5psLH4EO3cKIC5LFHnIkVequRbNLvDSJvNF5hXykSF9DG6Hutl3nOtgfD6E~sswLgImRk80kA__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
Popover, L to R: Light theme and a dark theme popover  
  


Popover requires an icon button to trigger its display. The popover can be triggered by tapping or hovering events.

Popvers should have an inner padding of 16px to separate the content and outer edge. Images or other media can touch the edge if required.

### Orientation

  
![Orientations](https://studio-assets.supernova.io/design-systems/16150/8c2ddf55-befb-4b47-a72a-999687a27bd5.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC84YzJkZGY1NS1iZWZiLTRiNDctYTcyYS05OTk2ODdhMjdiZDUucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=EHPV8RFjkHlk99egYUNGOwY0nt6aDqrTc-ERes4tAprV12XxnWBHewlfTk12VdDS~ojZwJVxWTjduGJdTnf9TPOrozWlQnC2szAhD4oDj9vzVttregz8j~SZch8SQHWSKXE68dJZo9~CP6HtDJ8thaDFDZgI8-u3kvKNIyp6pfszDrBQdVjpGzFlOwInCARHTZK~ukyHPMc~t0eCegDtsXmSie6LzFhvNkHUaxtwr8iPo5OYUlL95cAk~jwsoQfYttSXBNJZb~-rCd261y3DS9gbgPYWIciIbVEz5lIrC9tTL-RE7BuPmmfotsOk8sfWtjSzddAwP-KCGQryhIIxYw__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
Orientations  


A popover can be placed around all four directions of the icon button depending on their usage in the overall UI. If the containing text greatly increases the height then the arrow indicator can move to an edge of a side as required.

  
![Edges](https://studio-assets.supernova.io/design-systems/16150/5b31b687-7920-4490-b20b-3b6edd285d90.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC81YjMxYjY4Ny03OTIwLTQ0OTAtYjIwYi0zYjZlZGQyODVkOTAucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=e5JsyXxV7x8vOaLPCQlNHyWcBNUfm~pbWUBrpz2fRVLZe1FmdePuzDP6eAjgAF3RLlKGZDeyoybiTlSA8dDW2BuiPh~jr~9~4UyDVx8fvo8AwSywi1Gm2C5vj4VoJSqc4UhV~yEOBeA~bhifVrx57EQAjAWC8aoieQ~ir7b498KBOZs~bddIWSiasIWDRyIOemK~rSLmxRlV-b9G3uuwRj6n5o4B~uLZjtwQ0Gh-drfouiSjPV9mNtLtDvL-kdjuY6eIgYA06LwT-btVRHk03RfZOE~UO9NhKQ~JTAtFhCjhIGcvGFDIiw6oD-td0sIvCeLy5ZMHqk4pknnEdlmDjg__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
Edges  


## Popovers v Tooltips

  
| Column 1 | Column 2 | Column 3 |  
| --- | --- | --- |  
|  | Popover | Tooltip |  
| *Content* | Text, media and other component | Concise text only |  
| *Event Trigger* | Triggered by tapping or hovering an icon button | Triggered by tapping or hovering an icon button |  
| *Overall Height* | Popovers can be adjusted to suit the content. Content that is greater that container height will [trigger a scrollbar](). | Tooltip expand as text increase, but each line should not exceed maximum length |  


## File Links

  
[![Figma Components](https://studio-assets.supernova.io/design-systems/16150/4d4951d9-3bc1-4e73-ba89-61735aa2f28b.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC80ZDQ5NTFkOS0zYmMxLTRlNzMtYmE4OS02MTczNWFhMmYyOGIucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=AwpP-qJIDIsWowC~G4exhEdG8JpdYYUsozBmkaBKb9FvaaOXZWRWbjXGa3uNz6WIi4a2ZcyJsWyPNRXWDeGGRNUdcsM1prxxmP0xeUe8GC-0AalEi-GsUxZzs5QwV~DsJBghi5i9m6EGFDC7cV-XUZEA4NDRSPjopcxmz40GtkUayuZ~bDdigiFyvnUliKbVqP-YeIjE5J0qfZgYyzmK9cu~O5Pj3AkZbwJJGgYoI~MSupPPcNuHUQ~fHEF1~~bgKUNSW6dG2qT8EoPVKj~-VD4CAMptTjk~YkjGvBNB1GvGIMdu0LxpoH89b87Ud5gfZ506BQm1ZxocpnJgsxc-XQ__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)](https://www.figma.com/file/kwUvoAHziVnMYH97iJQzw3/Popover)  
Figma Components, Web/iOS and Android components  
  
