
# Tabs

Tabs are used to group related content in the same area of a single page

---

## Key Points

- Tabs are available in two styles and each style scales across three sizes

- Tab labels should be short, ideally one word

- Tabs are available light and inverted

- Top border tabs are best suited when all tabs can be displayed on the screen

- Bottom border tabs are ideal when there are more tabs that the viewport can accomodate

## Usage

Tabs should be used to display related content within the same area in the page hierarchy. Although there are two styles each is best suited to a specific application.

### Top Border

![Img](https://studio-assets.supernova.io/design-systems/16150/79b2ec38-efbd-4d62-ab90-7fcdcf256ba6.jpg?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC83OWIyZWMzOC1lZmJkLTRkNjItYWI5MC03ZmNkY2YyNTZiYTYuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=CtYj9cOZKHiBm5GnNYHTGHKLFUDvjRm1MDsZ97ejMjN8BlaA0TyfCner9VvIfdDnyuLWzk~DFmk9H5SGm-qr0VIWVRIBGCkKek2zgSSLl3MHkUmGSG7F~UqoX64oNCaL6LA6gC5Ns~ZEZM-HdVkmguzByAMUEcAsg02Qeb5cpsxbKe2FVC0UekEr13hEC5pLw3i1ktK8d6ivCau5qJM9ZpCYtkNvHugfzegT-YC9bnOYRnme9KKiwqqwwwbna8-1-aKgWov-RIv7gPbUnbZWHRHNRPBK3l5AhZuKfffJDi9gWe~WjV6XCO4swQOSobdSrkm2GkRNQdufIiC8lZTs3g__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

Tabs with a top border have a style more suited to situations where all tabs will be visible on the user's screen. Because of their skeuomorphic design which replicated a paper folder, they are best to be always visible. The bottom divider is removed on the active tab to show the link between the content and tab, like a paper folder.

### Bottom Border

![Img](https://studio-assets.supernova.io/design-systems/16150/4dcd2117-e62e-49a3-881f-9ea539b86589.jpg?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC80ZGNkMjExNy1lNjJlLTQ5YTMtODgxZi05ZWE1MzliODY1ODkuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=MzQOdFvB8Slw0fSS95oSYXrIvqi9FKxD4Z6ijIjV9BTON2wKZsfnBZ1rBa-QjHkIrf1XbWJwZVuV3VFnprM5tBxWJXvw5wDIs8Qnta~kuXPbCA9JPPEgATiQrP~hp9SOrgXkEaCE2Q44SRR2ex0YoqOVbU3gHX0zIo5ZSgEYcZ~fsqER1wwT3FxZg0H-NlEZVeympXcHxB0cs-e7A4HtAndBJazBN-XEKerhLovQLC6x7tTbxdS0~pyHDqoxTLNwJCMOBbUSZJDYJpdflKVWlpM8w2upJ00DO0EqO3D1A~S6C1sXrKrOhroNIav-8johhkQnmHiMtDRC5hNvETgT6Q__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

This style is suited to situation where the number of tabs or their labels will exceed the available viewport space. The container around these tabs displays a fade indicating there is more content off the viewport that can be navigated too.

*Note:* Scrolling should be a fallback for edge cases. Content should focus on displaying as many navigational tabs as possible.

### Sizing

Each tab component is available in three sizes; small, default and large. Based on this context of the page the sizes can either be manually set to one size or set to respond across all sizes based on the viewport width.

## Behaviour

The interaction for each tab is the same. When a user clicks on a tab the area of content directly below it shows content.

The active tab has a specific style that visually makes it appear closer.

  
[![Figma Components](https://studio-assets.supernova.io/design-systems/16150/31d6f7d7-27b5-4b32-b320-f2007257e307.png?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8zMWQ2ZjdkNy0yN2I1LTRiMzItYjMyMC1mMjAwNzI1N2UzMDcucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=fEa7Qem8H0WrIRMiz5tZbOBverIxmm~R2jGUsZrrZwQG6nS2hP0srMNjKKiqlKQ~jIXzGigJ83qdOPFtp7N3dIK9f2v7mW-vdGX9SWcxKZWepzmtV1t22Axzvvg-BXIP1ug~vm15jZSXQxg9Xu6~jf1m6way1zJ33xj2qn9nMESu1gaXdhOzlOBnmpnZ-D-CukJ7U-CaEeAdUPEsejJZj9KjhVX~3Pse2k0z2CHSGoMEaK0cCNPcgX0VAUdA2YwO5vdCwSu4FXo4uFINMtGCjIB7Rg~KVBIn8ARG1FpFXij9w-jgmdWM~yH9xEja9Gs4GqaSVM1NyHADqpBW4HUNbQ__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)](https://www.figma.com/file/tV0UdsxUnOj4ZE8cwC6W2o/Tabs)  
Figma Components, Both styles of tab as a figma component.  
  
[![Annotations](https://studio-assets.supernova.io/design-systems/16150/bdc1a2a7-062d-4d15-aeb5-79a4afd29b02.png?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9iZGMxYTJhNy0wNjJkLTRkMTUtYWViNS03OWE0YWZkMjliMDIucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=jscW0GA81NErzj2CxKDS4sQIKM8tEgiiuhkd3cMqxv5~-NkxtelS52xqHegbzjNzbGvUkcSJuLVhNMfdj859rE30nRc2vpvQs3NM89N3fWyBW3RrfgW~4aqem0U3HW0QrzfSvqAH1GK-wlBkuzLc~7yRyma3PMn8vuEGrnMhXOzrO4XKqumksbwmGDNNggH6pdMrnZYQgci4B54TWpEAN64qDog2hS3DawULn9TYRfr98VbN9NPEFjoz5Hhaahe~-dh8QplA6bVSRSih43R97EUAhBawRObY~Z2p-Jye8vm6kXovnVXFjJOzN~F5gZFTV~N0XTcVXjH7GGHZ~qakpA__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)](https://www.figma.com/file/V0r6OpbkZw2UNCl9vf49uG/Tabs)  
Annotations, Annotation for both styles of tabs.  
  
