
# Chips

A collection of buttons used explicity for filtering content.

---

## Key Points

- Chips are compact elements that allow users to select a choice, filter content, or trigger an action

- Chips should only be used in the context of filtering data 

- There are two chip variants; one with a icon and the other with a nested badge for further information

- The whole chip or element is tappable

- The add item and clear clear all controls is optional, it may not be required based on the filter

## Usage

There are additional control buttons that allow a chip item to be added or a "clear all" to reset the filter.

  
![Chips - Elements](https://studio-assets.supernova.io/design-systems/16150/cb589a0e-5092-4668-9437-8f6b426aa195.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9jYjU4OWEwZS01MDkyLTQ2NjgtOTQzNy04ZjZiNDI2YWExOTUucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=jYVe6wMFW4X5eIz-IRp1L7lcEmnOJPBmSaH6c6eHVAOGEMBch2M0cAwKOGDThp-WX8OLrGbCHogv5J1RE9dfJLFrCtM4x4PMM7hyYXEf0L0SF-NBCJqL5CBSe3DuGDwAOnW8jMujbhpUy4sZ1AWnFCVStFnoxrnr6IkV4H-ttubg04ouVXEHRiebUv6AAQxzpsiEl95a9Zec33eElYOIlkOcm6qzs2-v1vIx0-Epty2TvOZQjAYiDuszlIZjVmmd2q-WumjJlQqs~tClRfXMf6LtcAfRDgorWoncml9QVwIiYlmZMmr~YSEL~5fVmKU6p4eQ6r7hMG8Qg-dfVfKopg__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
Chips - Elements, Elements L to R: Icon Chip, Badge Chip, Add Item Control, Clear Items control  
  


Chips should be used in a collection, the controls are optional as the filter behaviour may handle the addition and removal. When controls are used:

- *Add Items* should always be first in the collection

- *Clear all *should always be at the end of the collection

Collections of chips will run over multiple lines if the containing space is narrower than the collection. 

### Chips + Icons

This chip type is ideally suited when a chip needs to be correlated with an icon. Note, that these chips use icons from the [16px icon suite](). If you require new icons to be added you should follow the [icon creation guidelines]().

  
![Chips + Icons Collection](https://studio-assets.supernova.io/design-systems/16150/844678e4-ae07-4f96-9fb8-bad6270cfa7c.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC84NDQ2NzhlNC1hZTA3LTRmOTYtOWZiOC1iYWQ2MjcwY2ZhN2MucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=b7A2Gl6peDBcf70PG0kg7U4DZ-ycFPn-kPpnl52zUWVBqwq1pyBAMABSwPv5UHVbUskR6XRSN~gDuYqS1icEsvOHNmtmo1xgsQEJ9jjUkyQvLO~QoKOKz1-siB4KA-T9jU0Cnyl9F3eGcV1m5zafcoaIddiEZaE3jqztl6HcV34ACZhmbJmdlhycOONmwoStTSmKDv4TgZCdDlL7xoVac3gk-pqkNOppVqvKxTNvfTqYBUaBXrhNjrKMLaex7a0MFYjAbv5NG~MTyLNeboZLjXnUDEroCN04yT28vUU3rUeiBCXkdettFnXH1evxFXe7LzigzSrwTTPiPRiiBxIk1Q__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
Chips + Icons Collection  


### Chips + Badges

In instances where the chip needs to contain more contextual information such as a count or other label you can use this type of chip. The badge in these chips is specific to the component and does not contain the variants of a [standard badge]().

  
![Chips + Badge Collection](https://studio-assets.supernova.io/design-systems/16150/63e26b46-6ff2-4ada-98f6-2a86191af7e2.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC82M2UyNmI0Ni02ZmYyLTRhZGEtOThmNi0yYTg2MTkxYWY3ZTIucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=kM7m-ptuqYn6OuyxWd3kMWKmrPUe6sqPJC2nRpcmlap8ykfEE-dlnN1GnJGE5AUp2ThzhkfW4WJnuHd-ECweAa~2Ty9a84DBMp1xmTQ0Gzsd4qDptCO7xiatOqZ-dVTstxise2mDbnASUcXDfms6P4A2VJHq~FXnvVvtVtjwDJca1ywD3W9ngJuQN1Tt7ZGAzRiUfJ9c2kvpS1TIH4YzYqcZeeSDJ94hNLJYnCRP98ysQid0XZ08Rk8LSw0yZqbjnbEGklJLnuFJlHeHCvvTeDniV6RJA3b5Y9GCkeBQaei4pXmtw9Zf-YLmnwTNvzxduq-9gPxm0UEiXW0BZ50KzA__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
Chips + Badge Collection  


## File Links

  
[![Figma Component](https://studio-assets.supernova.io/design-systems/16150/09f09b2e-b3be-493e-b465-a08a7f8fab65.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8wOWYwOWIyZS1iM2JlLTQ5M2UtYjQ2NS1hMDhhN2Y4ZmFiNjUucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=feo~qVxRWPfphrzUpARkueuFwZP2vsV9PMN~3UDhDNnQU9dvEN~AfN5rBUaBqloK5npG8T74iToZKkYpd-Kt1P7JWeb0~H~qwP7iFMvjPBsrVAXGgjw3G5qPoyDCUjz0dfGfcSb4q0rrJ5BP10aMCmnn-Ni-C0MyZVo8hboLWj1-U9MEK4o40Db89Js9wHsI4IifbH1wLcb3uxl7rhWcftpxTCy0LnDCQdp4hZV7zqVEdJzbCTuVJvHqFwD~TPgwLMYzBO00C0Du-bIGXA2LAuhV6BW9M0lVQHtgKe4WLsbeVIoIl4e2RknD7UEmpy7EOzqjRo9kRFxE6dZJS35vsA__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)](https://www.figma.com/file/4bBsPDWmGfkUm9FiRUudGH/Chips)  
Figma Component, Chips elements and components  
  
