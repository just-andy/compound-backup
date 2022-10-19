
# Tables

Our simple table components are specifically designed for static content which is best displayed in a table.

---

## Key Points

- These tables are not data grids, they only present static content

- The table headers have an optional icon button

- Cell content is left aligned for text and right aligned for numbers

## Usage

Tables are used to present tabular data in rows and columns. Each column has a header and the cells below display related content.

These tables are design for simple static content, not as a data grids. This means that the content is not sortable or filterable.

### Stacked Table

Our current implimentation of tables is based on our responsive guidelines. On smaller viewports each column is stacked as a collection of cards.

  
![Small Table](https://studio-assets.supernova.io/design-systems/16150/1153bbd6-e628-4207-92d5-eb0817e79b8a.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8xMTUzYmJkNi1lNjI4LTQyMDctOTJkNS1lYjA4MTdlNzliOGEucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=J~lSp-fq4ntN-oOkEgbq~cbYK8oGAFgpGiJts43hxSJ7HHzJBO0FoUKL34vGlpA54vYphiOVuPbEQV01agoOJZGXeUgPjhEk2N7VTJb0XaBCPklksumrY~vior08sG4QE2gUsKTpkEmE13XJ2OSjV2SrtVrjMpGv0urlSsGDdqVSUwWicTYkEB6WsZSwTQfWBUPtJeJdcS2ikDJyVKWxr4mNRHtrcYnvMbEP7UHfOyw95hXFNnJNLdZkOpjHT0clkeCkYRG1WZkwaVwKg6rJ~fdeIUcZUEMNa-7k75INfSITuuWkwsk82qWE6HZxw5jEEYDCilmNmNnbQujFHI~FlQ__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
Small Table, Example of the table stacked on smaller viewports  
  


On wider breakpoints each column is shown in a more familiar horizontal orientation.

  
![Large Table](https://studio-assets.supernova.io/design-systems/16150/c43f40e0-0a4c-4520-ae7f-76b0189ec7df.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9jNDNmNDBlMC0wYTRjLTQ1MjAtYWU3Zi03NmIwMTg5ZWM3ZGYucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=RQy1V4g28NYZA3ZXpRtyVfvzCiA9FcNKUiF2Em8Gx-vRvU2YIJYu~8arC1cZgM0kTtlVeA6dS-pQpuT0e1U4eeGwp8JzcNvNxzg8FueG3D94NbCLhsOskgpGpF-lWheuZKHch-0HzSEV452TyB-qW4GJZuN4jZy0tsCou90IMYvgdPBFDN7sW0jK3JjRFYhr6uTTwz8QWyM7x6cVgK5eyNg7yk6TLq0Dr0X4QRO0XeRJT2xCOTuFgLNCRT-VeTOh4AIDbSUP14mh8cdRjR67RBnLQ8JK3mBARgs-TEhbKXuFJXAbozXjKVjbTnx9FQZTG4i~vQc9KJ4DDHAXsDxzlw__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
Large Table, Example of the table at the largest breakpoint  
  


## Elements

### Headers

Headers as you see from the layouts above can be used as the title of a column or cell. These cells are shaded to show the difference and also include an optional icon. 

Additionally, there is an optional icon button to the right. By default this defaults to an information icon but can be changed.

*Do not use* this button for sorting, as this is not a data grid component.

  
![Cell Headers](https://studio-assets.supernova.io/design-systems/16150/d5ecbabb-bfef-4ea9-b7ce-14b28703d0ad.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9kNWVjYmFiYi1iZmVmLTRlYTktYjdjZS0xNGIyODcwM2QwYWQucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=dCw8E0TANADSxaQd5CC3KuypRw0I8uJH37VNub8fvnyawJwzv3nzstgXQNDE-XrOg5rAlXigHWdr976e1AFu0usvvCgCaFZTDvT2-pClhV6IWAN93XkHyJynwKj5FABhSq7LoyKTD9R9hTBbmAfXudVCd6iquaL04iI2LSw4IkUYyBD~4~AtSWJljFL-laK-OmQ4c2Xm7zF2cRYG6sA8L5PxrPVmH8o4O1mtq1EbFk3iUzSZXUPwjZwm~hGcFOHA92iuj1~0s7T-hKBrjKOGylJSFOPikE6DXP-~DpUgxHOsfQ1IiMY9bePra5FQs4gS8ti8qR1FMc9ZZGKXAw1Ihg__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
Cell Headers, Examples of the optional headers  
  


### Cells

Table cells have two variants; text and numerical. The text cells include an optional icon and the numerical cells are right aligned like a traditional spreadsheet.

  
![Table Cells](https://studio-assets.supernova.io/design-systems/16150/a7cb7231-1d8b-44b4-b612-eb22eb95afb7.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9hN2NiNzIzMS0xZDhiLTQ0YjQtYjYxMi1lYjIyZWI5NWFmYjcucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=gg3nSdO0BBXyL2anRt4m1zUIUwBlfGcjqcROYoVhLIMVIIQvEJGDD4fA5Xit38lYSMkUawJbJ2si4M4WCJ1R4IlOlynOPJMMAaoIOEaQIazB4Otmq1kSfvPoIKy~U2VHR7deONd99IeVzRrECSDEJwlvE7yt46ZAEC7oaQnLAtJ7pwBHF-t1EOJnsSg3DR0XmBDn~Ds-iXwRmLyDrxccX0foUbG5WqK4HWX4FKLI~d5J2hsKFFsGpItBiAQ0wj-yLhiv0G1b4cupdstVgLgH8ovrNCbRmvPT8qLDEAMLz0yYoNg4NVyDrEdgPfVWf5vKtlc6Uh2gty4KzbUZhAbQVw__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
Table Cells, L to R: Text with an icon, text and numerical  
  


## Native Specific

There are currently no table components for the [Ionic Framework](https://ionicframework.com/) but they can be created using various other elements.

## File Links

  
[![Figma Components](https://studio-assets.supernova.io/design-systems/16150/a23d4acd-29c7-47f5-87a2-d04312e9408b.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9hMjNkNGFjZC0yOWM3LTQ3ZjUtODdhMi1kMDQzMTJlOTQwOGIucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=J9FALmq25R3SdFi5mTG6MmIw9N1bhyk3~hp8hdYd50H6xDaslwWWcFNhHi7z4I6XLBuks1trb6zKMXiLeSr8clak27X-7tao0-iFYXhClUg30erhWW3bRVgHgwKj7oqhxv20wOD8vmCzZ9UvtOCXrJgvTv06UaiXnvnjwpB2VHD-eSPuqedTp7bh0UXA08qV-IXWlySSlfkKvEbxtrPx7h3Ii~bRMxPX5DO3iEaxOW7NWpMzRrtVJnf-f2w6bqIl2pDcDhJdpnSwPmW~A9OpEKI5nhZruAFlnEgQoehM0dg2opRpH3VpNT71ujzfem3rL-9iJTe3DWFjCdWfocgW7A__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)](https://www.figma.com/file/gsdAkfGKQFbUp4hL4Gi1P2/Tables)  
Figma Components, Table elements and compositions  
  
