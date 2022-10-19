
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

  
![First to Last Stepper](https://studio-assets.supernova.io/design-systems/16150/51b8b36b-af35-421c-b59a-1b97cce57fb8.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC81MWI4YjM2Yi1hZjM1LTQyMWMtYjU5YS0xYjk3Y2NlNTdmYjgucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=m7EiKZS4C-PopJlCARdJyjG7JiyqQ21sNKHX~95~SfKARvX8wQsuBXbopEULj3TPbSl6vWNZ52yggiOhVogvfpAxhaKvKFbnNk4bAva0zvQyz1zLECNSeLBfUKkB9mddDUpmWYVqLHHKR66-Y65NrYQHiDhLXfZZzQvmrQh6KJKBv9sHFeyBLCaS6kdEqvcMQ7MJUHSZUrUJ20d-rdnQAbJNP5qwi6JyjcO5vWPJss21ffjQO2sEkTMQokBz63e-t96nFuKxuOqHCH5jzGI638tkPvdWq5Y9iKBL1CpNx3fMx93qf--rfwEArnsw0FcEuXeSp-2n7QS5EMkgaSAuJA__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
First to Last Stepper, Buttons are disable on the first and last step  
  


### 2. Continous Loop

Components that have not end point always display the start and end buttons as active.

  
![Infinite Loop](https://studio-assets.supernova.io/design-systems/16150/5a91d24c-deb8-4a8d-bd4a-b2f6324e5edb.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC81YTkxZDI0Yy1kZWI4LTRhOGQtYmQ0YS1iMmY2MzI0ZTVlZGIucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=G1Nf042yeVp8vSKvUOFAKteLlfFPyRoh-E5P-uhgtF9U7I0RQcaUI7m3TiSi0GngaEHZEhlix2F8U9JlWgjJE3aUnolRURHq7j~9fnZl3SLsCUKvNkcEBKfsMAO87wjlF3FTLmP9tDtHuMQE-oYxchiXcTZw0yqNKktZkGKfL~iey9HaM05zycL-b2JUtZH6Ymy6RxMo3D033Mkzv2yNiTxLJ47s~BbHZS2VrzCXrjc7usXEvSdpWhUxGCSWRA3iyeD0gR5faWsgF-huQCcXfi~sTnwBXn9hkWdtYCBo3pDhen3ooVQjP3Vpad4nKW52BbCVmVS3xLSfvDVS3trsLg__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
Infinite Loop  


> Some extra info:  
> The Figma component does not have a continuous loop variant as changing the nested icon button state property from disabled to default will achive the same effect.

## File Links

  
[![Figma Component](https://studio-assets.supernova.io/design-systems/16150/a4da1cba-a3f0-4abf-a84e-e0a533cf3424.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9hNGRhMWNiYS1hM2YwLTRhYmYtYTg0ZS1lMGE1MzNjZjM0MjQucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=gdIdcK8SAkl4c-6MCz92hegwSfZfFI8A70vdIStKvBU6DqdPRQef1lisWLCXMYq3DlR-l14PNSdSYOUct2uzEg2-AHTfowBKuufNiUaZp0i1NTJ6CsANs6UQZ4Wv6USQkM9Wt74V6TBp1Ek-g82n9Q3HWl43nWmzQYNXRPzQUAdD5U1x7G6oy2V~jcKok~zVNRj9I0D6Qyncz9oatLC14zjCgi7LcfxZYQsLl4~PoeSsVnbl234Mswp2BgdFVv-IMLxNUiXtItWSgKs6RCbT9dlbzJ3Ex854DN6K9F~jBYm9ajJqICW17aJq~nU~kSQU~tOqpsfd~0It2IoQXnGdzw__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)](https://www.figma.com/file/vP51Z0jjUxizLppBka3lUU/Stepper)  
Figma Component, Stepper Figma component file.  
  
[![Annotation Files](https://studio-assets.supernova.io/design-systems/16150/34c31c04-9190-456f-b2e6-7f5b111508c7.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8zNGMzMWMwNC05MTkwLTQ1NmYtYjJlNi03ZjViMTExNTA4YzcucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=eNIbIc9UM7-mHgXtZ3ysINKPqNs3GRf6brAtWKZbhrIhqbkZLUUkMg2pO5FFOpj0xBUmGYhXuaCrGyVBYkmuwoqxLVchAZmW1281pQH3nYGuztSS5QWVKLdTSDd~lut7neY8E0qRCwB3sRfSdcy7ZWpV6xQyWYPqD-0AlYMNfRE7hbHnSLn~Iv~XFTTeUjFJMpts3b7tb5ocWIBIkA4uZm9ghaEkyRIqfkYjCJxfEqRNwNjV-s-AViWRaHaZulxXAaXD-mbEDI9G6O8UyAI3kfcboW4o-d-XsdfcPFWrCHV3RnluywXKrVR8k1J9wie~t~kk20J5QaQhJwUc0iuIMw__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)](https://www.figma.com/file/1rLUiN4LneoXvEetUuZVN7/Stepper)  
Annotation Files, Stepper Annotation files.  
  
