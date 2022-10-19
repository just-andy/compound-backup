
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

![Img](https://studio-assets.supernova.io/design-systems/16150/4b0144e2-6eaf-4be3-b2c8-f87c2c622b06.jpg?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC80YjAxNDRlMi02ZWFmLTRiZTMtYjJjOC1mODdjMmM2MjJiMDYuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=KKTZUhlYwHxjqzQ3Ja6Sop~MkmyA08h56QI0PTdoRZGNk8OqVJItaFjLkMtPdlBWAyUFaXIxxZ7Dz~WfBdnnVpQqcpn6DfwiX8xeHC1vsyQYF8ALHAbbl-Tt3B5oE9T9Io5-Nl97l8w2B2-JmLKu9Z3oU9PtY7TteJZ82oVnghL5-76f4G30o379DdIOwt17Q3dxVhL1-ZMj114g1iCFql~XCwAuiCh3h2ojad1U2emfY-f6Mhwjkhcun2Tdof~Xx1XWl-KkDnPLZBtHOuOoFV0e-GGr5eBdFh6awHeNNO-C6tqEDjeyErjB5QNGZ-uPG9X~sgacF9RxNUKxl4rMmA__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

Chips should be used in a collection, the controls are optional as the filter behaviour may handle the addition and removal. When controls are used:

- *Add Items* should always be first in the collection

- *Clear all *should always be at the end of the collection

Collections of chips will run over multiple lines if the containing space is narrower than the collection. 

### Chips + Icons

This chip type is ideally suited when a chip needs to be correlated with an icon. Note, that these chips use icons from the [16px icon suite](). If you require new icons to be added you should follow the [icon creation guidelines]().

![Img](https://studio-assets.supernova.io/design-systems/16150/82a9d082-107c-4f9d-88c6-7b8cf538b060.jpg?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC84MmE5ZDA4Mi0xMDdjLTRmOWQtODhjNi03YjhjZjUzOGIwNjAuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=iRC4mV-YFKe6ogCr3ZSnow9COmrGOMCa~zdJuFzvkj71B69GF5JLFhiG1JbIDIrgMesSbvo7re4oqnIjrdnIpvXP16iRhJQ-q48QI5Wdu~hzRINpTGH8Ta51vIN9Aqd6wdQF9emdJ3DJBEjGbW8SFPcNW~i4IbFcH0DMR-6jx3cJyUnSnOPP-zc0hzGbiJ69Ivj4a8MNaC37DbjL4J-~XSUI7UDZyVMjvvkJleqCb~nmB8l~rstlLpCLXFW4TsDwD88XtXbWgFwrfv4cUy5xOrTngaIrUHBq6mD4EUVpZj7i~BP5GJVGVBmsYVI6EWpU4HMxEzZ1VPJUlof9mpmN3w__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

### Chips + Badges

In instances where the chip needs to contain more contextual information such as a count or other label you can use this type of chip. The bade in these chips is specific to the component and does not contain the variants of a [standard badge]().

![Img](https://studio-assets.supernova.io/design-systems/16150/56e61c7f-a529-4560-911b-b77dd639fa82.jpg?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC81NmU2MWM3Zi1hNTI5LTQ1NjAtOTExYi1iNzdkZDYzOWZhODIuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=FvdQ~xBXYkm7i2P9Ox5Pqa~7Ne1dku0rXAFP6VIE5Q-j8Rt5ExWWyoDN7w3pKqBxPl79u-UNzgk9t1gbwvSjsIgC4eCU2AgyjDLHfii8jbj5uUd7-0THVnB3GDtECXtGxUdX1zANkNe2u5NrqGu057g-YxZAQwUu3~on6xZdQS8lbRvIU1b7dHIko6Ewu-cgz0mgTBf3KvwtfKmiCgiySBliHOiJqw6LuUx-M5XfLcftPKS~m9-BVQaN94GPk5Vah-iCcr6bwjZ-zYd91ChO6V3-uy3OMOhNDJvey~4KMkbheDNWmAOs76Zr~9CNROJq7r8v1U7p1T2hHw-FsYbXWA__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

## File Links

  
[![Figma Component](https://studio-assets.supernova.io/design-systems/16150/09f09b2e-b3be-493e-b465-a08a7f8fab65.png?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8wOWYwOWIyZS1iM2JlLTQ5M2UtYjQ2NS1hMDhhN2Y4ZmFiNjUucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=UtzmZoXBXQi2kD55ysDBcrL7-D5d8n1C29heog1qfCkWjAdeu~n5EI7ez2VZUd7OCqLICuFqJt05CloXzZRzg08qMLET4MUPTGAo9eSHy-He5dg8eO~jrHvf7Vx5~~Dak87NFieseYUHbIHWRwgQU93AVbIaewFV~dWCO1NbM463B4L41i9~-5zSpRYjHBVmDGOwsY7cVeoiUc1xqF8vrU2QeQUuUZkV4W8Loj4raXi2rV7doAOkhmNys85RH1hOK4x9dHgKp~KvY8R0BjpjBbGmi8FF1spV0RficYPcF4fZ6wQY6LNqP19sMnrcSL1QjFXarZSmnpQUUPQE-93yRA__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)](https://www.figma.com/file/4bBsPDWmGfkUm9FiRUudGH/Chips)  
Figma Component, Chips elements and components  
  
