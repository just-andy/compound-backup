
# Components

---

### Guidelines

- Before a review make sure that the version has used the correct 🚦 status indicator.

- Make sure all layers, component properties, component properties etc. are title cased "Small Screen"

- Make sure that the component file has been set up following the [setup and structure](https://www.notion.so/Setup-Structure-6100e77469de47638d91056beced11cf) guidelines

- Be consistent with breakpoint size naming; small, medium, large and extra large

- Check that the [guides for building a component](https://www.notion.so/Building-Library-Component-bc3125df94374a9189b28a5d565c1248) have been followed.

- Check spacing conforms to our 8px soft grid. In some instances, we can go down to 4px if required.

- Check that any component with [variants follow the guidelines](https://www.notion.so/Component-Variants-15bc43c7ac7d4b96a1d851969ebea99f).

- Make sure nested layers have been [correctly named](https://www.notion.so/Guides-for-Designers-348239c4a1f44056857a5114e4a06802).

- Make sure layer and frames are correctly named, see the [Guides for Designers](https://www.notion.so/Guides-for-Designers-348239c4a1f44056857a5114e4a06802).

- Pages should be named based on how granular the components are required to be.
*<Component Name>* - If the component can be used across all platforms use the same name for the page as the file name. Figma removes the duplication in the Assets panel to keep the naming more concise.
*Web, iOS, Android* - If a component is required for each platform. Remove pages as required.
*Web, Native* - If the iOS and Android components can be shared.

### Testing

- Check that styles; colours, text styles, effects, have been used. Where styles from outside the system have been applied their usage should be justified.

- All colours should use the design token styles, not the shorthand styles
Do Use - LM N0.
Don’t Use - Interface/Card Light.

- Check the component responds to content of different sizes or being manually resized.

### Native Components

- Check that any nested components are linked to the correct parent component. For example on Forms > iOS the labels instance in the Input + Label component should come from the iOS Label.

> Be warned:  
> This bug comes up when you duplicate another page to reuse the components. Figma keeps the link to the parent page.

- Native components can have a dark mode theme if it has been defined. We will build this up over time so it is not currently mandatory for every component.

### Cleanup

- Make sure the first component or variant is aligned to X: 0, Y:0. With this anchor point the other variants and frames should be:

- Update any child components or styles that Figma flags require updating before reviewing or publishing.

- Reduce the amount of nested layers if possible.

- Lock any layers that should not be edited.

- Add notes or supporting information into the component description field. Use a prefix of “Note” if it is an instruction.

> Some extra info:  
>  To add the same note to all components quickly, select the variant and add in your description. All components will receive the same note, you can then further adjust specific components one-by-one if required.

- Check any previous comments have all been completed, marked as resolved or deleted.

- Remove any extra files, dummy instances etc that have cluttered up the document.

- Make sure groups have not been used.

- *Don't forget the cover* - Ensure the cover component has been added and has a thumbnail set and all relevant content is correct.

- Before publishing the component make sure that there is a save point and [the correct 💾 status indicator](https://www.notion.so/Guides-for-Designers-348239c4a1f44056857a5114e4a06802) is used.

- 48px between components, variants or frames in a horizontal direction.

- 24px between components inside a variant.

![Img](https://studio-assets.supernova.io/design-systems/16150/188bf226-0bc3-425f-8b22-98aa0b675330.jpg?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8xODhiZjIyNi0wYmMzLTQyNWYtOGIyMi05OGFhMGI2NzUzMzAuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=h1YdpdQF3IPfegqgWsNdcIRxMjx0fVtSRRgnaoZ0G9nZ2EVY6GPWcj1fl91wuH7g-kTsrtlCMA8Q8fYUMNPk6nzlpPh~AB8dRiKNsNuLTvS2AA6Pz-1JIIUTtba2gD85J4awPwCWWKcBmuZZSlDRcak9o6nofrPxIPq2BFxoBtjblv5QEJPzy-h52Jo9UCkM1Elc91qVH0~f8LHWf8349tE9ImPAHt5iuhaDrQwrqw7jMyAVsfuC5rF1t9jnviMmKItbXU7D9wpDji~57pXgLxtyckLMZl4RXFJC0yiEdNQxwWDAFOiriKg4aYiTFxCJdoI-l~JmQNnMgzZ-ISlquw__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)