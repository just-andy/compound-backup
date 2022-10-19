
# Tooltip

This layer component provide supporting information when triggered by hover or focus events. Information should be helpful and concise

---

## Key Points

- Tooltips are trigger by an icon button, this should be within close proximity to the content the tooltip is supporting

- Tooltips should only contain text, for more complex content use a popover

- Tooltips are triggered on hover or by being tapped on touch devices

- Tooltips can be displayed in multiple orientations

## Usage

  
![Tooltip](https://studio-assets.supernova.io/design-systems/16150/502ad722-1e5d-4be4-b52d-8e45122bc668.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC81MDJhZDcyMi0xZTVkLTRiZTQtYjUyZC04ZTQ1MTIyYmM2NjgucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=dTch2slso6yYp7z75npfRhujd5K4n-gfr~Gbwhtc8JxuTBlw9T-io93wIecYP9NfJtUQwhs~ILd8I1S2x~4tQwiioGqG4MgtGkLmlWwKdlJUnTLT0rz~xJRGdt3XCfRwmY1vOBfdipMh3s7O3xflYs0g8St~ghUOHxah96DIwJ71PLLh8e5dINS414uHxRrQ2zAXHZ8tYmYD3X~i-rnEx1V9w~qEWzinPVcZAtHqxl9FufcDReeTwIv-jEsXEB9AUaiKHTfA~jskSM9cYPjD7aL3QcNyE~0F59OCXIIjkImodJb9~7Az7w2sdRNrJWKpfZLBLvw4QaUFra16NYLMGw__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
Tooltip, Example of a tooltip placed next to a button  
  


Tooltips require an icon button to trigger their display. The button can be triggered by tapping or hover events.

The content within a tooltip is text only, and this text should be concise and helpful. The tooltip will expand as the text wraps over multiple lines. The width of the tooltip can be adjusted but should not exceed our [maximum line-length limit]().

### Orientation

  
![Orientations](https://studio-assets.supernova.io/design-systems/16150/544346aa-e2cd-4193-adad-924cb32d72d0.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC81NDQzNDZhYS1lMmNkLTQxOTMtYWRhZC05MjRjYjMyZDcyZDAucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=lN3K3U0ydTX6oiX-R~HFtEDl4zzpJsS1sRueA50WXodhPax97BDLjU3o5fTxbPn15TdTE~Omn9POs6C8QntFqwS5ZepZUtYTe7222Asc8OR0sFXZnetL3Un8Y5ANfMnQGPbUMukp93fr6YRVwCeQA90K9BVx29MTm-pX-YZHCfKQMztXRG9TaM8IcyboxEJlLBmtkJ4QvWMapBByXDl7IPtCDpUoJzX0aMdfDnRNCT8mQtaeeSP4GPwM9cZgJnjd54MR1dFw-W3894J3fJbar80ayrHSQAL1T~3ZwXDQGLdysXWsgcwnvAyeetIqJGrdzZEikjg1qf72-JXflLO2lQ__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
Orientations, Examples of the tooltip orientation  
  


Tooltips can be placed around all four directions of the icon button depending on their usage in the overall UI. If the containing text greatly increases the height then the arrow indicator can move to an edge of a side as required.

  
![Edges](https://studio-assets.supernova.io/design-systems/16150/6d1ba242-f0dd-4032-8ab8-37fc961bdb33.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC82ZDFiYTI0Mi1mMGRkLTQwMzItOGFiOC0zN2ZjOTYxYmRiMzMucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=a2WsNJsXFEHy0FLlVHuKvmIqEvw~DFZ~RwV9MZct2pOvMWcs096W8dS3zkbPwdJU5-j857-48CJDod0FusSJNnsQHm~lKWVrXn2PJ8XvjqS~bSLCGUcnkj5BlCmNGvASgkfZ3M8mO95G9yWPYnMb1Wn2DVeMeLowSr4xlsXFwCz0dpcjWq2kOchaAxW4Os3M3wDlBXgVr7x7hjRM2oDcasesiqZ~l1XEq9rFEOge7KoJHEIVL6tIdABmaqyhZjFc5hfTgCZMd0lrqNWPuR-XECZukTStsDJ7XafnfYZYRDogUBwdatGUSojosJY0Dk-ralh2nOg4jB43q01ZV67jBA__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
Edges, Indicators can be positioned on the edge of each orientation  
  


## When Not To Use

Tooltips should not be used:

- When the textual information contained within is required by the user to complete an action. This content should be placed in helper text or an [alert component ]()within the UI

- Do not include media or other interactive elements within a tooltip, use a popover instead

## Tooltips v Popovers

  
| Column 1 | Column 2 | Column 3 |  
| --- | --- | --- |  
|  | Popover | Tooltip |  
| *Content* | Text, media and other component | Concise text only |  
| *Event Trigger* | Triggered by tapping or hovering an icon button | Triggered by tapping or hovering an icon button |  
| *Overall Height* | Popovers can be adjusted to suit the content. Content that is greater that container height will [trigger a scrollbar](). | Tooltip expand as text increase, but each line should not exceed maximum length |  


## File Links

  
[![Figma Component](https://studio-assets.supernova.io/design-systems/16150/7af209d1-f13b-4117-9957-670c6f49da5b.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC83YWYyMDlkMS1mMTNiLTQxMTctOTk1Ny02NzBjNmY0OWRhNWIucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=DHm~mQVq75YTMADXWUQcPhqmgHUrgYbcXwqCBEWXr2KEqOviS1~a0EJFzjUKAl81sfmlWgJNFKtT8l3cJLq6lsP-LtuIj27ockG75P0Cacv2m~llNw2z0Uky8dNiZ67Ft-a1EPXU~UwmKbmkNO1HG6ct3RZbSvTIUygeUb-rYQ~7ryNosUJ~nzVYZIEe2L5qZ1VwLYHgxD9vXTPLifsGw9Sz3WmOs6FtOzFgOWcbJYyZwoCno6FDc2VHHBFq4aLKJYI3qC3fr9Va9pvRCMEq04RYeQ6cZGKuE4mSfC4oLt7so64s71KRDFb7fxteDSlZBzg-6g0oXQ2o-u6QDBvm2A__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)](https://www.figma.com/file/SGjaBt8oRUHGAO4ZyCM7rY/Tooltips)  
Figma Component, Tooltips Figma component  
  
