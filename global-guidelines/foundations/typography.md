
# Typography

Written content is a key part of our interfaces, from marketing content through to legal data. It is key that is it legible and accessible on any device.

---

## Key Points

- On the web and native platforms, we use [Ubuntu](https://fonts.google.com/specimen/Ubuntu?query=ubuntu) for Headings and Legends at bold and medium weights. 

- Body copy differs depending on the platform:

- We use a typography scale that have standard naming convention for design tokens.

## Links Styles

![Img](https://studio-assets.supernova.io/design-systems/16150/7c166847-f5f5-4ecb-851e-90cc17f132bb.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC83YzE2Njg0Ny1mNWY1LTRlY2ItODUxZS05MGNjMTdmMTMyYmIucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=gMyroq00Ka44cHNti3wuJ4L2JJ2aWC8-jaePraBFmKi0hU3PJja4Jvap7zNGd0B0sj-7Ank-j3BR4B9eivQ-xBRWahOICmBEPMdoHFFR-JHUQbtSaZLJ1W8AeAEx68UdZEicOr4kqZGFgY525Keo4hPynjIBRBjBv-A0JV82aOjRs2kbgMsiBZ4xTTshwykh4k0XMoyY~cX9yUMaxccOWutr2eKoejInvAmprd~9OKalzlvjDtGEBE09fqUTbae6S2gu288QiflqKqBNfkVs7BPOOd~zchKtCFx5PtnbIQOLT9eUoAgM5~wLVPDJdjp9xiq1P3JK6~8ZBLVR~GOHqA__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

On all style blocks the text is underlined, hover the colour changes based on the state. The focus outline will be located around the text element.

## Web vs Native Typography

For brand consistency we use the same stylistic approach for our fonts. Although we use a custom Ubuntu font for headings on each platform, *our font choice is the default for that platform*. Each platform has its own type scale but uses a consistent approach to the naming conventions.

In most cases *the minimum font size we use is 16px*, with the exception of smaller fonts on supporting labels. The main difference between our native and web scales is that the web scales increases to greater size as we are displaying on larger devices.

### Using Type Scale & weights

Whether you are a designer or a developer you will see a range of common styles such as _“Heading 1”**_ or _“Label”**_ used in our Figma files. These are short hand styles to our type scale and allow for designs to be developed consistently.

You may require more granular control over your type, therefore you can adjust from heading one to a more specific token such as U150R which would provide the same font size and line-height but a regular weight of font.

Although this flexibility exists you should make sure that changes fit in with our systems governance around [structure and readability]().

### Truncation

Truncation of content should be limited, instead *text should be allowed to wrap* so that it is readable to the user at all times. When working on designs, particularly components consider how wrapped text will display.

### Line Length

We should aim to keep line length to around* 90 characters per line for readability*. Context and type size will be factors in the value you select.

### Web Type Scale

A key difference between platforms is that values on web use two different type scales (large screen / small screen). The web scale values are larger than the native scale as this platform display more long form content.

Guidance on which size to use can be found in the [responsive design]() section.

Our short-hand type scale offers two different sizes of body copy to accommodate this.

- *Regular Body* - This base size is 16px and should be used for shorter amounts of text and components.

- *Large Body* - The increased font size makes long form content such as blogs and legal information easier to read.

- *Web* - Arial

- *iOS* - [San Francisco](https://developer.apple.com/fonts/)

- *Android* - [Roboto](https://fonts.google.com/specimen/Roboto?query=Roboto)