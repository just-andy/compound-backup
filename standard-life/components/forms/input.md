
# Input

---

# Input

Inputs are used to collect user data. There are several other input types which have specific use cases.

## Key Points

- Input fields are the same height as buttons and icon buttons so they can be used inline

- It is best practice to you use the correct input type for the data you are trying to collect

- Input fields should always have a supporting label

## Usage

  
![Form Input Variants](https://studio-assets.supernova.io/design-systems/16150/8bc07e50-15e1-4f38-9f9a-41bfc914e273.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC84YmMwN2U1MC0xNWUxLTRmMzgtOWY5YS00MWJmYzkxNGUyNzMucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=HPlir1mqjgF2~5-0yxA4A3f3o6Xu1uMgfGdZdS~3zV0Uo2uOmuSziHi-IxduBPsGcs8hrDDcxUV~DW-JMLqKjwOT2nLhjdGKKpZjxdB0gBJgSEnsPiEz--aXvB3Ow6PhGjc7dwoaXOi69zcEnrpQS34SW46Clj4ktsinePpBaDXeUh6Oe9t08xn6GjmmogoD4x4nDGJfZJqobado5OjMh-rlQQSGx5Z882lzVvLBK0W7fOof8SQvgUDvZVICPSxahbfZIe5Pyj3jkuzemVTkb41SiHeE98dNo1Mh-zavB6m3Zd6tohai8OHjMFsQXUk-Qbnr6uejzsd0cwZRJSTZ4g__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
Form Input Variants  


Users can need reassurance if they’re giving us sensitive data. A clear, well-structured form can make it much easier for them to give us the information.

### Single Field Usage

Pages that have a single input field as their main content required a larger label. The label should be styled as a heading.

  
![Form Input - Heading](https://studio-assets.supernova.io/design-systems/16150/76b80b74-47d6-44b4-81ae-d6004a27a74a.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC83NmI4MGI3NC00N2Q2LTQ0YjQtODFhZS1kNjAwNGEyN2E3NGEucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=mS3u4qQh9nx-2nnEwFzNosvEG1DHezom6tgKQ0XOZrUgKHShrfX6n4~INfHa-c3o8F58dNVSQlmk6PRHJdh4TcLn10kKb1Bg0B0KOmqr8efh0vs6Uvgs5mev-tTjwcYctMNndPsOzkwt1d-LkY49-JefKpRWTXgjHoINVyQzfAIrSKJVtGuVtkO9YcHydw7rHM4S-3BtJbwyOx67mDfq3foPKdEDceFTwbQ~SX6y5CQ2xap3-o-~6GmoiPZ5rMy6lgnQwsoeqJ05K9EkkQrkR13VyNEN1Ds~DMzwizgMbzMUd7GJ6WrDO529gl9zA0KNKanbPXbrE3C-3UAvrZ3nnw__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
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