
# Overview

---

# Overview

Forms are critical in our design system to allow users to input data, from calculators to our contact forms. Each from element in our component library is individually documented, however, this page provides the overarching guidelines when working with forms.

## Key Points

- Forms should meet our [accessibility standards](https://www.notion.so/Accessibility-dfba092ae8844275aa594066b479d5e3)

- Forms should be able to be controlled by the keyboard 

- Forms should be built using the correct HTML tags

- Our style is only a light touch of appearance changes. Functionality should be the browsers default.

- HTML tags will display and functionality based on the browser

- Labels should be associated with the respective field. If labels are hidden they should use the correct syntax and a title, acting as a label, should be close to the field.

- Place fields in order of easiest to complete first

## Best Practices

- Keep form labels and helper text concise, between one and four words, and informative

- Break longer forms into multiple steps

- Use sentence case for labels, helper and error text.

- Use the correct input type for the information you are gathering e.g. number, date, email

- Group fields of related content together as fieldsets and use titles for the groups

## Typography

- Form labels, helper text and error messages should use the body copy text style.

- Headings above groups of inputs; checkboxes and radios, are legends. As these are headers in forms they should use the text style U90R.

- Heading styles, h1 - h6, can be used inside forms to section of content if required.

## Hierarchy

Spacing is critical to indicate context to a user. The spacing between elements should increase the more you wish to separate groups of items.

### Spacing Values

Forms should have a consistent spacing of 8px between each element needed to make up an input; label, input and helper/error copy.

![Img](https://studio-assets.supernova.io/design-systems/16150/40bf782e-8852-4cd9-a358-e835e9e25951.jpg?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC80MGJmNzgyZS04ODUyLTRjZDktYTM1OC1lODM1ZTllMjU5NTEuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=EmVstAjGjDxvBVFvPYHzSr2MJgJsgNRYFw-dPuXM6Ruo26o0Kr-~ki9sxYdthonkNDRYn4TxpSIufVyK11l1K~qy4EF82tQqqUNRuTrl9QbVM9zl1~slPfpgSu3ci4ZlEBbkvW9BprpE~ggMILysuidF6JMlPUr3NUPXfDicgbIp27DiM-jXThJS9DPpGJc~h3iNF29sYKuCkivJ9RiT92aipKv425viy819oe9wZRyhyEtVCKjl8mF-buVqWKUqEnxfB6vv5oTw2N4ycwd~Sg4qO9sSV71s2WskbRFtePruOHIMc~-XNkrx2ZAJ4Uw8TblQi2Lci5VebJs3MlL~Ug__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

There should be a space of 16 px between each input in a group of related fields.

![Img](https://studio-assets.supernova.io/design-systems/16150/acf8e77c-4b74-4468-be11-700093b717d6.jpg?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9hY2Y4ZTc3Yy00Yjc0LTQ0NjgtYmUxMS03MDAwOTNiNzE3ZDYuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=bJeeUwAS1Xj6EP38-xuaTe1y7ixOAlBVlfkoHI9DpVTkolUpuDYwn8P~eF-2jSVJi8UzknAsXJITsowMZNmzpz2AtqB3VdCoRDiAdCOpi9kahFpWdh0zVYqo7lJ7nZD3gBCUf~AVP9xMOJ~e6tljqY2Rimbeg0BVno3b5gdyvvnWadisN8Tlw5p1W1X5l4BVzo~y9uL3V3t-QxCFNLwQ5vUbBSxqupXUeaT6JL~VgMmteQzTQogf04I0YWgzyHFJ5lz6sA7tmsyJVRZ35Gr1sn9eKcIKqNk-cyq4gGZ27qffH3BncIypthNl9byV1FjrEqHWnVt7yHlSmbh5glhiTw__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

Use space and headings to break long forms into sections. The spacing value could increase to 24px to clearly define each section

![Img](https://studio-assets.supernova.io/design-systems/16150/23297371-042b-49af-972f-4b2f7aa1b443.jpg?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8yMzI5NzM3MS0wNDJiLTQ5YWYtOTcyZi00YjJmN2FhMWI0NDMuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=jBowGJBHZ19LA2cRiMtB9u25cT2ycagas61P1kQVYTSydUCn15DCYyQkp9SJL0pv8~2gBfFDqhjpOH8KoduW2BgNdDYCm9O-TZiuQMPXxYOCRB~DZ2m5Xfiked3c7fmhICfVQLOJxEvkX-uui4U5f0PGasr80gpxz8sn4rnNgpTE4URwHse-f2PXcv1ssMINGThDSQ3rKZ3hpJHkQhRoPAZ-zPVsTt-eOZqlwfAg2dZZG~CgN~CVux8oalJDb01gd1~6aqEprjqkh-WB46Nb9t-SAXYqUR9IiR~T4IBEkbo-fwu-XaOs4GoBYgxUVc3T82XGpiQ-78VQb1fOTA7FZg__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

## Required and Optional Fields

Any form should only present and ask for the essential data. 

Should there be case to use required or optional fields then we always highlight the exception. This is indicated to the user with an additional text label.

![Img](https://studio-assets.supernova.io/design-systems/16150/a738dcaf-3cf3-4152-a4bc-09c03aa3c1b3.jpg?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9hNzM4ZGNhZi0zY2YzLTQxNTItYTRiYy0wOWMwM2FhM2MxYjMuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=lajdQEIxJhG168kiyjICh0FtPJ9Oac9CGFP4m72CIz9zunFEw8MnrFrCsuAGouYgK3laOCyM5hFJakmUC2Ebhwbp9LEOtZSAlocYbMJyWO1UXTf1703gOQUweY8yVoR0Br0PcBUKLD5S-hlOZGBsb9iW0Iso5G1g6i9Ivk6YYeXRF8W0cnF~O5m8Fou4xRicich13afrEZm3lbaQxd2Da-f2VPaz2G4TAB8DIRzwt045TK6NDpdaQOvzmHafOG8RPMpa7H2ijK~mMMDWifna3NY0ELQ5gxDmlF9ih4Coj~Zkxsl6JQgWFqCIYub60m8yZv6e~1cZi6ucIfiRf4TbBg__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

## Helper Text v Inline Error Messages

Helper text should provide a short instruction to the user on anything specific criteria they will be expected to follow.

> _”Your password should include a capital letter and be six to eight characters long.”**_

Inline error messages should provide the information to the user on what criteria they have not met, helping to resolve the issue.

> _”The password you provided it too short.”**_

## Labels & Legends

Labels and legends are two separate HTML attributes. Labels should be used with every input group however a legend is used across a range of inputs such as [radios]() and [checkboxes](). In this system each has a slightly different font style and the appropriate style should be used and HTML attribute defined in annotations.

## Keyboard controls

All forms should be able to be navigated to by a physical or dynamic keyboard. Aside from using the correct input type a clear tab index should be included

## File Links

  
[![Figma Component](https://studio-assets.supernova.io/design-systems/16150/b4fe4c98-2590-471d-8e14-51967cb342e7.png?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9iNGZlNGM5OC0yNTkwLTQ3MWQtOGUxNC01MTk2N2NiMzQyZTcucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=mat15s~28jvDtDb2AHLAIU4jCLGymvhGvuqbbvGF~ia9GS0L0aogd9ddGyVwH2UWVSbxQFbQfxW3DRYjNy4Mfe~zzmP2xkHOC1tAFL23SLXhkUQqQynbhoB-udbaK1jbiEl-MRdwsiutuaSidXmaJZlcxesombqlk7Pnz9kbJpEHQaYDpFDDzkm29fhLNYdvyOVlzP9dWm6c5Gu2sa01U79wgBMQ3CgvaeR0e9O6Au89JJAm0njxFDzXit7K6llGwhYcU1ThiN1C3-EvSl4y0Q2Ef~mA24JYfCbDJ9EXwZV5MhAEGEGNOuFNsneQMLiRnk-cYeT7fCpFC-PKFjVueA__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)](https://www.figma.com/file/0fcqKJuCJWIW5Mf5nERjwG/Forms)  
Figma Component, All of the form inputs are grouped in one component file.  
  
[![Form Annotations](https://studio-assets.supernova.io/design-systems/16150/c27480cd-624b-4935-aca4-1a9bfaa168e2.png?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9jMjc0ODBjZC02MjRiLTQ5MzUtYWNhNC0xYTliZmFhMTY4ZTIucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=GgJTDAllXlc0MGdDO8SOkfZzOa3wiHho39rTA6IfajnbQUlVojDykmNU3so0qxCnWCbw4rUtem9I1EAPnpZWvU-uA~Ju4e~IX5MCIzROj3jn2aMBnalqZNvMokLmghA~RThuFan41lKf1G5bpMdUHZsj2S5iIpuzp0dqkPvWIWrGlCzBN7s8-wdNHSwuWAJEy7oG077DhKWfQn408wR8EVHsVWrGToIN0spHDGKO3Wy-zFwYJepNW4wQUvlZeYb8aUCAujMTyfpcMtdAzOarELDaCliSr9C8xOp~J11cw7Q9rTNCJGyToH-O5xMvbE58oQyXmU8wAKuUP5g31idaxw__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)](https://www.figma.com/file/DFj8Tnc7cbcwB7nto3rMhG/Forms)  
Form Annotations, Form annotation files  
  
