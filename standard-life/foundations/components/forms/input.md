
# Input

---

# Input

Inputs are used to collect user data. By default inputs are “text” which collect any string characters, however, there are several other input types which have additional features.

## Key Points

- Use this input type along with other [form guidelines]().

- Input fields are the same height as buttons and icon buttons so they can be used inline.

- It is best practice to you use the correct input type for data you are trying to collect. Displaying the correct keyboard on devices with dynamic keyboards decreases cognitive load.

- Input fields should always be placed under the label and helper text, with any error messages displayed below.

## Usage

![Img](https://studio-assets.supernova.io/design-systems/16150/0fa88fe5-65e6-4084-b24b-0753c75cff78.jpg?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8wZmE4OGZlNS02NWU2LTQwODQtYjI0Yi0wNzUzYzc1Y2ZmNzguanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=cy0wDB2GbIfBVyucQaQ22YsN~loHt5yxhvhUfBbuXWIMVmOEOlAYlUoYTHkQEPb6Oih~8B-3hyN2QSoFMcjIDKOYFtA~ydHjnETQEMGRda6JA41sPMcwYKPO9FycR00u-YAM8gIAZG4RNVqUj0~mMhzcbrfC4JtvwVLamoBCz3qetgSpDNqpE0lGoh8l9-pFouzuGRyRkxkCNchlE85RAi1Jy4WbZMYUDVWTGHRM77fJ5A973op2bQnzixiM9aoRkoyr7HL-RwOweMFOtmOy9wDSM0TqqnAJfH8pLGuy~pama60-E56RRwv6hPhDyG2sr-LkKKNVa-BoCvPQ-Peu5A__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

Input’s are used to collect user data and depending on the sensitivity of the data users can require reassurance. A clear, well structured form can make the process of providing the correct information far more straightforward.

### Single Field Usage

Pages that have a single input field as their main content required a larger label. The label should be styled as an H1 and use the same markup in the HTML.

![Img](https://studio-assets.supernova.io/design-systems/16150/6e1464ab-b4cc-40d7-98bc-14678e73bf95.jpg?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC82ZTE0NjRhYi1iNGNjLTQwZDctOThiYy0xNDY3OGU3M2JmOTUuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=JVuJGLiqu2xdDzpUxETVs3duaJEPQh9vuXDkymbkCjPtsgAoDtDXGaoFllmRUYzIfY7RqvjfVHwEdnlbALt6r3~W1Rx08j18MiMbX8PoQzNGF1KrqAglpoKOfDCuxrUASYkRVlH-7HKqMBHs0u214U4-dCErCskmf2P80MPJXQScRJfa58b0tSbHaKmUnFv5CF4DWtxidOyJi98s5SlEJyIgqF4qoBqGUl320MqN8eefBxpPBHNmvWEB66TTOA889Foo8FCc2HCdWmYRGIjKzeyvk~Xm2HDgsaBOkPx6Mgl55U2O5vm5wL4BRjaPQ-6K8rlYp9~D243-k-OekJMVfw__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

Our Figma component has the option to switch between a label and a heading label to achieve this.

### Sizing

Text input fields should be use varying widths to visually indicate the amount of data expected.

### Layout & Grouping

Forms should be single column in most cases, related columns such as Date Start and Date End make sense to be inline.

Fields that are related should be grouped together in a fieldset with a legend or heading, depending on the content hierarchy.

It is best to start with easier fields and build up to the more difficult form fields.

## Behaviour

Text inputs are part of forms and they will collect user data. Users can enter an input field by clicking or tabbing into the input. Depending on the input type, the user will be presented with the appropriate keyboard on devices with dynamic keyboards.

Number inputs limit the user to only adding numerical data.

## Other HTML Input Types

- *Email -* Looks like a normal text input but has validation parameters. Devices with dynamic keyboards will display the relevant keyboard.

- *Number* - Although it looks like a text field this input only allows floating-point numbers, and usually provides buttons in the form of a spinner to increase and decrease the value. Touch devices with dynamic keyboards usually launch the numeric keyboard.

- *Url -* Looks like a normal text input but has validation parameters. Devices with dynamic keyboards will display the relevant keyboard.

- *Password* - A single-line text field whose value is obscured. This input type will alert the user if the site is not secure.

- *Telephone* - Most touch devices will display a numeric keypad when `type="tel"` is used, meaning this type is useful whenever a numeric keypad is useful. This input type doesn't just have to be used for telephone numbers.

There are a [number of other input types](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input#input_types) that are not covered here but can be applied. If you have a field that captures specific data it is always best to check that you are using the correct input type.