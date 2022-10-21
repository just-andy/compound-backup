
# Stepper

A stepper component is a control component that is usually paired with content. It allows users to navigate a collection of content in a fixed space

---

## Key Points

- Steppers can control between two and five items

- Steppers can either step between the first and last item or go through a continuous carousel

- Steppers have no outer padding and therefore should be spaced as appropriate

## Usage

Steppers will always be a child component of a larger composition which is trying to display content in a fixed area.

Steppers should always be placed at the bottom of the composition and given enough space to allow a clear hit area of the controls.

### Navigation

Users should be able to navigate to the each item using the stepper controls.

- Using a cursor they can click on each button or a specific indicator.

- Using keyboard controls they can navigate to a button or to each indicator.

## Behaviour

There are two different ways to display content using stepper/carousel:

### *1. First to Last*

If a user is required to stop at the first or last item in a collection then the corresponding icon button should be disabled.

  
![First to Last Stepper](https://studio-assets.supernova.io/design-systems/16150/715e10b9-127b-4115-8f86-866d5e67c115.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC83MTVlMTBiOS0xMjdiLTQxMTUtOGY4Ni04NjZkNWU2N2MxMTUucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=XcYfQAF9isXL8wP5KzfzGxibIo5LLvpJfm9LobYXau31T4A3JgOBfTswb-VPm~y1GtSAn9luKArznfySHcd5sm61IMT5DJmkWQo90vJvh400Ve3N3sKZ3lIds2v5x5bBRWkxjE2-0QZ0p8yXFTynmHy0Vy9yBb~P2mf7g6ykiTsiwzmnNm3iGrkwqTP-GJUD1EggpK6WgGgNxhLOXIfSgr6YXPZylPFOwhDar513vBH0ox03s8E8kmaEd3mqVFui6XKACjRCT~nuLdDpq2gkumumXhaTjZGpNE1bKG6id9XpCr3a4A2yFxySUbRKGBqWkN37aEry5HDdlCfIaofTmQ__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
First to Last Stepper, Buttons are disable on the first and last step  
  


### 2. Continous Loop

Components that have not end point always display the start and end buttons as active.

  
![Infinite Loop](https://studio-assets.supernova.io/design-systems/16150/2609475a-5aba-4614-b47e-3ab1eb62d11a.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8yNjA5NDc1YS01YWJhLTQ2MTQtYjQ3ZS0zYWIxZWI2MmQxMWEucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=byK-nSSkBPPCEJz7ch9Zi76tI6AySuBAXQzin5BdbNQrDJGNWhcc3CWKt2OeSHSxgG3BjlArv46JD-DKEt6pMLP6eEBogMD5pLqTr~Kn61IaSmVw2G5-HDIm~WFtFD62zX7T1LWeRwmiTFBfY7MtNcbArWJzQegj626jBXFeYTVKdy6uIAn61VlFa-bqL908ibPr1An3zM6q0OETgbgKlByzX62f-z3CN7aegvd21l2rWBhACBe0F-fTC4OcQTOcGVVR2o4~rZoB75alqBIEkT1VX2CAMNQOZe22Pa9bbfgQ4PbP~qiCO2MhiRfnBSOV--CcL7HzWDkfxTK8B~ahCg__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
Infinite Loop  


> Some extra info:  
> The Figma component does not have a continuous loop variant as changing the nested icon button state property from disabled to default will achive the same effect.

## File Links

  
[![Figma Component](https://studio-assets.supernova.io/design-systems/16150/a4da1cba-a3f0-4abf-a84e-e0a533cf3424.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9hNGRhMWNiYS1hM2YwLTRhYmYtYTg0ZS1lMGE1MzNjZjM0MjQucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=gdIdcK8SAkl4c-6MCz92hegwSfZfFI8A70vdIStKvBU6DqdPRQef1lisWLCXMYq3DlR-l14PNSdSYOUct2uzEg2-AHTfowBKuufNiUaZp0i1NTJ6CsANs6UQZ4Wv6USQkM9Wt74V6TBp1Ek-g82n9Q3HWl43nWmzQYNXRPzQUAdD5U1x7G6oy2V~jcKok~zVNRj9I0D6Qyncz9oatLC14zjCgi7LcfxZYQsLl4~PoeSsVnbl234Mswp2BgdFVv-IMLxNUiXtItWSgKs6RCbT9dlbzJ3Ex854DN6K9F~jBYm9ajJqICW17aJq~nU~kSQU~tOqpsfd~0It2IoQXnGdzw__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)](https://www.figma.com/file/vP51Z0jjUxizLppBka3lUU/Stepper)  
Figma Component, Stepper Figma component file.  
  
[![Annotation Files](https://studio-assets.supernova.io/design-systems/16150/34c31c04-9190-456f-b2e6-7f5b111508c7.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8zNGMzMWMwNC05MTkwLTQ1NmYtYjJlNi03ZjViMTExNTA4YzcucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=eNIbIc9UM7-mHgXtZ3ysINKPqNs3GRf6brAtWKZbhrIhqbkZLUUkMg2pO5FFOpj0xBUmGYhXuaCrGyVBYkmuwoqxLVchAZmW1281pQH3nYGuztSS5QWVKLdTSDd~lut7neY8E0qRCwB3sRfSdcy7ZWpV6xQyWYPqD-0AlYMNfRE7hbHnSLn~Iv~XFTTeUjFJMpts3b7tb5ocWIBIkA4uZm9ghaEkyRIqfkYjCJxfEqRNwNjV-s-AViWRaHaZulxXAaXD-mbEDI9G6O8UyAI3kfcboW4o-d-XsdfcPFWrCHV3RnluywXKrVR8k1J9wie~t~kk20J5QaQhJwUc0iuIMw__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)](https://www.figma.com/file/1rLUiN4LneoXvEetUuZVN7/Stepper)  
Annotation Files, Stepper Annotation files.  
  
