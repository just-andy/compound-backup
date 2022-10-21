
# Input

---

# Input

Inputs are used to collect user data. There are several other input types which have specific use cases.

## Key Points

- Input fields are the same height as buttons and icon buttons so they can be used inline

- It is best practice to you use the correct input type for the data you are trying to collect

- Input fields should always have a supporting label

## Usage

  
![Form Input Variants](https://studio-assets.supernova.io/design-systems/16150/2105164a-aeed-446e-bfde-25b3268c263e.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8yMTA1MTY0YS1hZWVkLTQ0NmUtYmZkZS0yNWIzMjY4YzI2M2UucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=dYO6~SKuxtVfXbHaXfnFRNVk8awPFGHJl27DNozabrDdcGW4btUHi0gjPh4HyLpDuOtVPxMMMNz7XFj1Q1YeQEmd2nAh6gJ9HfBdh3cFhpQRiochfBGPXbR0XfmNO99rRQ0uZKF5RrpuGcD2kxmkgRlyfWDUdwskzvNClNA7WpXFauoJdTyUwDcGOQG1gI002tZxwnjO9rgfiGFZ0Va7Nnkx4nZo-uUVpw9oQ9~Qrgn4Erfnwi0xAFdpxSEsyEPrzAhkkj2bs5WRH962~LEV71C6DqnHBqbOWX94g4kYSq1j5N08kAsJsJPN4aw6d3Drsj4f8wVEgsV4nzdJ4Fe7sQ__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
Form Input Variants  


Users can need reassurance if they’re giving us sensitive data. A clear, well-structured form can make it much easier for them to give us the information.

### Single Field Usage

Pages that have a single input field as their main content required a larger label. The label should be styled as a heading.

  
![Form Input - Heading](https://studio-assets.supernova.io/design-systems/16150/1a8f59ae-9d13-4492-989d-325b8690364f.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8xYThmNTlhZS05ZDEzLTQ0OTItOTg5ZC0zMjViODY5MDM2NGYucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=C2HjKP6~pR8zvo3flBGxrf4s~ekxhJzVxDv8DWuvUUoiUdUOTuUiaSPNGxYDNVjnytIoiWHyEYJL-6kZtfCCIWZKMBLErR7-n1Fiql-2C~O5VvttzB6zqODSeCvPDk5VYWr1uR~nSJHRgfyqXn9qdjTkjdEWnL7XeJL-0pJl9XYjD7OF~xe5vX6Xrx1GZ-K~s1250SgSAC1lmonz~9e56FCJhSZ86qUllclP50-VC95fo0H4C7rLatTWh~oSc9~YcE1RzKjNQfU-fotfSRiHSaUTZeRktsKKizhKiaKltOIbIMBBNOIasVAJUQdLRjMkpiJQZyH-BNc4G03DdnqfUQ__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
Form Input - Heading  


Our Figma component has the option to switch between a label and a heading label to achieve this.

### Sizing

The width of text input fields should match the amount of data we expect.

### Layout & Grouping

Forms should be a single column in most cases. Where there are related columns like Start date and End date, you should put them inline.

Group related fields together in a fieldset with a legend or heading, depending on the content hierarchy.

It’s best to start with easier fields and build up to the more difficult ones.

## Behaviour

Users can enter an input field by clicking or tabbing into the input. Depending on the input type, the user will be presented with the appropriate keyboard on devices with dynamic keyboards.

Number inputs only accept numerical data.

## Other HTML Input Types

- *Email -* Looks like a normal text input but has validation parameters. Devices with dynamic keyboards will display the relevant keyboard.

- *Number* - Although it looks like a text field this input only allows floating point numbers, and usually provides buttons in the form of native controls to increase and decrease the value. Touch devices with dynamic keyboards usually launch the numeric keyboard.

- *Url -* Looks like a normal text input but has validation parameters. Devices with dynamic keyboards will display the relevant keyboard.

- *Password* - A single-line text field whose value is obscured. This input type will alert the user if the site is not secure.

- *Telephone* - Most touch devices will display a numeric keypad when `type="tel"` is used, meaning this type is useful whenever a numeric keypad is useful. This input type doesn't just have to be used for telephone numbers.

There are a [number of other input types](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input#input_types) that are not covered here but can be applied. If you have a field that captures specific data it is always best to check that you are using the correct input type.