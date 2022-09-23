
# Accordions

Accordions are components that allow sections of content to be vertically displayed on a page. The header for each section controls if that content is expanded or collapsed.

---

## Key Points

- Every accordion should have a clear header that identifies what content is collapsed and hidden

- Accordions can have one or no accordion content open on first page load

- Accordions should be able to be opened by default if they are triggered by a deep link

## Usage

The accordion component makes it possible to display large amounts of content in a small space through controlled disclosure. Whilst this adds an extra click to the user finding content it keeps related content together and the header will provide key navigation.

![Img](https://studio-assets.supernova.io/design-systems/16150/15c5c4fc-196a-48fe-abb3-71372c58ef30.jpg?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8xNWM1YzRmYy0xOTZhLTQ4ZmUtYWJiMy03MTM3MmM1OGVmMzAuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=ORxhdYC0UgGM6D9TEnWwfQtRl7lDnOdqj4TjqfOBqRpk~WiNQg4L2gtk3QTsbi~dOIIhH2ZHlRL9qnAOpWO7fBOqxz-IsZXF9o8b0-3p5CD91Msq7lYLMdGmjoAcfjEAgT~oUga~nENR5thAWvJe2GB4TfrD7L~FjHRiQKtvq269wq0iWIhRp6WrSY-2Zz6k-NPAYGupqLmOWcFqOVPKmD3~y11wTIXRSKF0-nUfTY4G-8caxeOt0NxCPSzvHirqYqiv7RmAs5XkyXA2BJMbkPTFEn0Zy0IzfHkYdGiy2bULCEcQtmTUPnbYhACkRweGSbd7nIQR0x3FZrZ2ThBcdA__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

Accordions can be placed on a page or inside other components such as a card. Be aware that the overall height of the page or container will change depending on the section(s) which are opened.

![Img](https://studio-assets.supernova.io/design-systems/16150/fb3b82a5-4a09-402c-b7a5-10ced97a39fb.jpg?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9mYjNiODJhNS00YTA5LTQwMmMtYjdhNS0xMGNlZDk3YTM5ZmIuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=khNcE6g-23ei2fS-U7s-DSlK2Jdij1TUdKJxBn11rpVYPna09BKJrIBSZDb2R6JG1ymhyHUPv32ojkdAe4CpI-2oEKhftPHpgZ6sHcNcpCaFDzMBaFGDKgeOUfUDSueuv8LQS0fMSkzTtLch1R9c97SWMKkgb2a6H5y0kEIiSD4hPHfL5xZAJzoG8Bovt-ZfXzvGydo9JrehGzg7D1ylN7-QZdmqlcREITGWMFJB7l~q0jsj-QhWupgGpdYk4aDcJA-13mRVvpOaLNVRZ18K6gd4T4I-7CjtpYBMFlyKP6hYukArvag6ShtZ57L73EQlZIGm7zn1LLkZZPpvxzq4Yg__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

### Behaviour

To keep content related within their container the following two changes happen:

- When the accordion is open the arrow icon points up,  the icon down when collapsed.

- The divider line stays at the bottom of each section when expanded, this is differentiates each section.

The whole header section should be tappable to trigger the expance/collapse action.

## File Links

  
[![Figma Component](https://studio-assets.supernova.io/design-systems/16150/05958447-7f1c-45eb-aabe-b9ee21efa641.png?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8wNTk1ODQ0Ny03ZjFjLTQ1ZWItYWFiZS1iOWVlMjFlZmE2NDEucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=PRRUnMfmrd0tuRjE7e8nIoIVqaCip8~NLOZNL87H1zqcSGfG8FWxZiqcYQ7Rga2-u1~59r4Hiq6W6cjkW0BYMHy-ikSSzK53sMU47UbS6u6ChcoarQhRc8JCxV3q7OoCXLqgx8e-qb2WxUwFzsMvUUYbJC53ycj1eqkwDCaki1iiE71SQ1oOyNqVOf0l5sRqmT2ZdFn8xiykVV7sdPqXwky2kWNyXtMSAmd97Ja-S6~5jLDdbn0f0vWoGT9BnO3L35qVy40EYUjeLfQK5kuK1NSvXvGlQ6WBks3K97LywaKUazhXU4PxgDkKZIAoy5i-j-iCbWcRgY5Svty9emiEIg__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)](https://www.figma.com/file/FIcmCWBV2EQgCFJzlWR7yR/Accordion)  
Figma Component, Accordion component  
  
