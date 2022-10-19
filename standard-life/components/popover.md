
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

  
![Popover](https://studio-assets.supernova.io/design-systems/16150/b34e33ff-7fa8-4566-9ade-e4c457bb5899.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9iMzRlMzNmZi03ZmE4LTQ1NjYtOWFkZS1lNGM0NTdiYjU4OTkucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=e7WkAQXUeWKInX8XynTWbqT~nFAIhGJLiBseGHSjRdz2hKO0JdL0PRDfxe1~rxUOZkwWj6uPLf~CwGoCBguYZIS5f1L9wXSWcP2n-9HQGfWZM0NmIhvB5DTGtywTUsqjQS4lBOpY1TXxpsJAjSHcL02~vH0gdZwbd9rpXjZgTRs6tmT0RLUOx~~48WVKR57xF9wrhA2txmdhQ9~ItTjEJdYdASImJ9jHS3fzqDryHjDiU5AxFKwVOBFxRcKnqUFqh3uK4CjwPjP9MS1uDR7ZoWhdqE-bBugLcg2iF6EPKy3gEhsiUczEhEmINdd419KLWeF21SSpbiStCWidb~sxMw__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
Popover, L to R: Light theme and a dark theme popover  
  


Popover requires an icon button to trigger its display. The popover can be triggered by tapping or hovering events.

Popvers should have an inner padding of 16px to separate the content and outer edge. Images or other media can touch the edge if required.

### Orientation

  
![Orientations](https://studio-assets.supernova.io/design-systems/16150/d5d4437b-c02e-4af5-9898-2d1b8066b832.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9kNWQ0NDM3Yi1jMDJlLTRhZjUtOTg5OC0yZDFiODA2NmI4MzIucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=jVATwH-EsTvGwolTzvyup9~RGls7k7IVBDHgyS9yAZRxftfMtzAuUrhbqreoIvKBBlkl7FA2k7t5BXoa1XMyMFm0FKmtNo6PJLSgkOrX1YUCuBeIw5bjowVSmW0-QFI3PQIBmscs59RfEOz-pYqgKemeEOl~-fqh8uLaqQK~Cz34D3c12PyJk6~r3sR5nFg3cMsmOk6kS5yqJ8xKhuG5mJNuSCFB7rJawQ4aE88qJ2TesqzaCPyVSXa6bwIMlwt5PoEbZVW4lqqzR-qh~12n8NymiPojH1U4WEzSC8G6kv1qnpgzcq6VOGx0ToeaFRbAVCJCQ8FcjmY5WgHMZz7FFw__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
Orientations  


A popover can be placed around all four directions of the icon button depending on their usage in the overall UI. If the containing text greatly increases the height then the arrow indicator can move to an edge of a side as required.

  
![Edges](https://studio-assets.supernova.io/design-systems/16150/0478bc96-da86-43d7-bf4c-7d38ef1c5478.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8wNDc4YmM5Ni1kYTg2LTQzZDctYmY0Yy03ZDM4ZWYxYzU0NzgucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=M35Owlj2VcfdddEhr~R4MCUeJEqJrP77lbh9HD4AiM56qTyLRu117j38m-xrSIHtQXUvBie6w4kfxX~WlOMgBcLLYqoEhXWQKyd5wfXmoD1tApnJ908YKsA5Lx-s5K51j4LujAu98xDJ7Ha76zEYjO~3EPgVx9I1jum0cL4Gs5THCGEe7WbQLYtMyTAWyNSJ3e29lPewFk8mjSupWzaJBVBjsDhFPS0G6PAbh6jkUqhAc5kkQXZvyPTcvZA569Cgp1Upimsk1onC3bD9V7XoTzvL1wAniXeN5iqPi-MwG-umA83~l2x3doyz6cCT6g50GV8ROgiEdKm1NAmuacp8TA__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
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
  
