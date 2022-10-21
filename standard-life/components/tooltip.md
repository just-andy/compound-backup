
# Tooltip

This layer component provide supporting information when triggered by hover or focus events. Information should be helpful and concise

---

## Key Points

- Tooltips are trigger by an icon button, this should be within close proximity to the content the tooltip is supporting

- Tooltips should only contain text, for more complex content use a popover

- Tooltips are triggered on hover or by being tapped on touch devices

- Tooltips can be displayed in multiple orientations

## Usage

  
![Tooltip](https://studio-assets.supernova.io/design-systems/16150/72ed21d4-ed67-4535-9b75-3d8a412e17b3.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC83MmVkMjFkNC1lZDY3LTQ1MzUtOWI3NS0zZDhhNDEyZTE3YjMucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=MUQ6nGT5ksTxo-wW~Xxzeu~fBBG2~NpS9k58wbG2Urw6VHi3Xi-4eETPHe~qdMJXbtbgxrlrGpUUqjKJsr~jW33k7~tC~Toim1s4ZYqZUioBmi2QbGKNyQK0RAAkw6Owkqog-w1nKz9XU1uPXoOdyAz4xwBTUm799h9cqhwaLgym-Rng4VENj9qhJW5RRIyKy83TapOgAKLcPF0e9wNJt2bg5stXo6G4GCyOdEhy2Rdq3uCt0-FvREhVb9UBI~0MXY36isTX64IL7SQRddjTAqgDuFWh4RjlG~DMBN0lTa7Rsoc3662CXkB-LxhVQ3YmxMUzGFfTpWSOAL50M3CanA__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
Tooltip, Example of a tooltip placed next to a button  
  


Tooltips require an icon button to trigger their display. The button can be triggered by tapping or hover events.

The content within a tooltip is text only, and this text should be concise and helpful. The tooltip will expand as the text wraps over multiple lines. The width of the tooltip can be adjusted but should not exceed our [maximum line-length limit]().

### Orientation

  
![Orientations](https://studio-assets.supernova.io/design-systems/16150/6e3995b4-f4ce-4810-beea-223f1623ce26.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC82ZTM5OTViNC1mNGNlLTQ4MTAtYmVlYS0yMjNmMTYyM2NlMjYucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=KNwKDIDA6Z-Fh85JcGi9VnqHYdtBESRVyck93t2ryizNcvFKYJtrjQDhpG53QfchJfc0LcsEkM3zoUMWTo~5-5QL34FCjyS7NGBrN3y2lioX-8gMW73lnBziqnMgaHutPW~V6DGjgrnJDEtMkToYjQowH8Kbo9cElLM0jrgQZSHO~BlfwKRS~Zdixnz0Odd2TAfhlnehvz~wI~SJI-gr-xXhShlQnIA5xI8FwEWm6BEK4RbcNnCQ4ejxlORTHnbGDUp3n7eGMeV95l5cqiwU-rUTfcF1cj2DbOcD3TfzB9DUcdmNkuarR2DwSSG4-d2aHylZhctMoNxGxXcG6Cb1bQ__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
Orientations, Examples of the tooltip orientation  
  


Tooltips can be placed around all four directions of the icon button depending on their usage in the overall UI. If the containing text greatly increases the height then the arrow indicator can move to an edge of a side as required.

  
![Edges](https://studio-assets.supernova.io/design-systems/16150/1027f3c9-8bab-47eb-a32c-30e3e0079827.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8xMDI3ZjNjOS04YmFiLTQ3ZWItYTMyYy0zMGUzZTAwNzk4MjcucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=dGWRs31Yu0OpYumX9ibLweM7OVc-rYCkpTsqkrDPc3Dl4hFP2JQZXcYIvfaeN~N5tdyWTOmqnLYa56CWrRMI9gR1IXY8caC-wwfnC9sztiwKtvm59sQc-4YBEYT~vskGrjfZ4yipqCA-8nfmjvpKGFQt2H2h0JfQ4844rRpMU~mKvVTHFztoxfwIaVD8-kX0tE~cFmIE~E3yL7b-UrFFmkOL0ptzVrB~zxJGJCjzsypbu5WkYaZB~e50QSXl1BySseiKK5eVdSzhLcLp2vs0bUEk0w28nuEgp3GxpGPq4tE3HsPKS-OmTmT-dDnlkvOK6f-G1ivbhTZcdNVOvPp60w__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
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
  
