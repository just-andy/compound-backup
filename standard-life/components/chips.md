
# Chips

A collection of buttons used explicity for filtering content.

---

## Key Points

- Chips should only be used for filtering data and the elements should only be used in the context of chips

- There are two chip variants; one with an icon and the other with a nested badge for futher information

- The whole chip or element is tappable

- The add item and clear clear all controls is optional, it may not be required based on the filter

## Usage

Chips are a collection of button types that are used along with filters to refine large data sets. There additional control buttons which allow a chip item to be added or a clear all to reset the filter.

![Img](https://studio-assets.supernova.io/design-systems/16150/4b0144e2-6eaf-4be3-b2c8-f87c2c622b06.jpg?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC80YjAxNDRlMi02ZWFmLTRiZTMtYjJjOC1mODdjMmM2MjJiMDYuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=Yh8byn0Q5fV3r4won8Uyev0qAn9nil2zfcYZJaM-5l2~rWLd~4EOu2BCOzUEfNOAP7xnJMjOCACX81lz~y8wBiK2TIV-VWoGEEzvdkNx3ql0vSNLqnD~hEmcU7OeI2oO1anFmD-Zmx4DU25-2VlZEo2vv8wZ5RAOIIWL9EkGUWIs84Ij-dONODYKlxDb~noWZ-JFjQqpWYUK1gJnXRTseGsGWI~CR5DbUHfpAIfmTeKcGtW6OpQx3OMuzXO2oaznz~SU2yvuHipVVJumUMUG0cqzrTan7EHRUc9bk01m3TjeOeAKkr8DOz-tIDrbeAU8M8VQSsQNZF~WSFG2thNuUw__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

Chips should be used in a collection, the controls are optional as the filter behaviour may handle the addition and removal. When controls are used:

- *Add Items* should always be first in the collection

- *Clear all *should always be at the end of the collection

Collections of chips will run over multiple lines if the containing space is narrower than the collection. 

### Chips + Icons

This chip type is ideally suited when a chip needs to be correlated with an icon. Note, that these chips use icons from the [16px icon suite](). If you require new icons to be added you should follow the [icon creation guidelines]().

![Img](https://studio-assets.supernova.io/design-systems/16150/82a9d082-107c-4f9d-88c6-7b8cf538b060.jpg?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC84MmE5ZDA4Mi0xMDdjLTRmOWQtODhjNi03YjhjZjUzOGIwNjAuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=SB3rskyEglgUOqoHknd6gVG8PyLqY4denAiFQLQyoIrf3hFYtD~g8QZQ2f-bYAmsQuFQ3dhEENCJzRNDtN-JWd6TpvMO~OD3o-2dcG-~sYvEpqRKvUSRaR~CmWwmQmP1VQRuI-Hf5eZ4v6DiwRrFZaPOZ3ch2cxTI9p1AzTux6nCxbKlj-cviL6mXlOfwQkx2pNyrpaZ79GE8dYYEX68ZseY2o8C0JVCFbFhHrJip7AjkFku1JPqU0rsv5J2WyHHkFjs73z4bQxm0AInrC--37Ux8feGi7rXnfsZqYynCtKt1EC4ZeneqUkA6nXTJNjRnHBKr1kmyssT~21QBusqPQ__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

### Chips + Badges

In instances where the chip needs to contain more contextual information such as a count or other label you can use this type of chip. The bade in these chips is specific to the component and does not contain the variants of a [standard badge]().

![Img](https://studio-assets.supernova.io/design-systems/16150/56e61c7f-a529-4560-911b-b77dd639fa82.jpg?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC81NmU2MWM3Zi1hNTI5LTQ1NjAtOTExYi1iNzdkZDYzOWZhODIuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=FR6amlcEc01rQbEiwyehPu4rX5XnjPkz-w939qyKtU7a9ZcWj-ju8Npau6b9ZoqscDpW-Yi30~42C4VkQRHsgwaYSE9q9SYymdK1WxeZbv8KE7bUBsHWZtwqQTSkBhqc6lTvaZzxT3QMPmGoygBNSMyA0wtyukwDzJ5OZ260pCkgrBxypuAfx48x9HnJYfl9uenXL98oiZeqFf2HDPoXGCOgKvCfxtNKeMA6L0uf6DTFz0ML8x--t1OtBgY4CMShMo8TfIwVsVQoxoGUo1QtniA7kC8NaxEWsYMtEsIoJ~FT9-VDSVXQMfshRhb8HIsCNjo6ypZRHDtNToeICuR6AQ__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

## File Links

  
[![Figma Component](https://studio-assets.supernova.io/design-systems/16150/09f09b2e-b3be-493e-b465-a08a7f8fab65.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8wOWYwOWIyZS1iM2JlLTQ5M2UtYjQ2NS1hMDhhN2Y4ZmFiNjUucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=feo~qVxRWPfphrzUpARkueuFwZP2vsV9PMN~3UDhDNnQU9dvEN~AfN5rBUaBqloK5npG8T74iToZKkYpd-Kt1P7JWeb0~H~qwP7iFMvjPBsrVAXGgjw3G5qPoyDCUjz0dfGfcSb4q0rrJ5BP10aMCmnn-Ni-C0MyZVo8hboLWj1-U9MEK4o40Db89Js9wHsI4IifbH1wLcb3uxl7rhWcftpxTCy0LnDCQdp4hZV7zqVEdJzbCTuVJvHqFwD~TPgwLMYzBO00C0Du-bIGXA2LAuhV6BW9M0lVQHtgKe4WLsbeVIoIl4e2RknD7UEmpy7EOzqjRo9kRFxE6dZJS35vsA__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)](https://www.figma.com/file/4bBsPDWmGfkUm9FiRUudGH/Chips)  
Figma Component, Chips elements and components  
  
