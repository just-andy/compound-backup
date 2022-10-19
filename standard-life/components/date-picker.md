
# Date Picker

Date pickers allow the users to select a specific date and time. The components differ in patterns between web and native platforms.

---

## Key Points

- Web Component follows the [Chrome/Edge Implementation](https://blogs.windows.com/msedgedev/2019/10/15/form-controls-microsoft-edge-chromium/)

- iOS and Android use the ionic date picker

- The date picker is used to select a specific date

- The month picker is used to select a whole month

## Usage

Date pickers are displayed initially as a form input field, the placeholder text and calendar icon indicates the data required.

Upon the user focusing on the field a popover layer displays a calendar. The calendar allows the user by mouse or keyboard to select a date in a graphical way.

  
  


### Date Range

Use two date pickers side by side to all a user to create a date range.

  
  


### Validation

Date pickers should handle the logic of making sure that the date is entered in the correct format. Any further validation about if a date meets additional criteria is out of the scope of the component.

Like all other form inputs an error message will be displayed below the validation field.

## Variants

By default date pickers default to selecting a day. However, there is also a variant to default to selecting month and year only.

The placeholder content will also default to date/year, ommitting the day.

## Native Specific

The native date picker has the same usage but uses the Ionic date picker that has a different layout and the addition of an additional time parameter.

For more technical data on this component you can read through the [Ionic documentation](https://ionicframework.com/docs/api/datetime).

  
  


## File Links

  
[![Figma Component](https://studio-assets.supernova.io/design-systems/16150/742bc767-af2a-4131-b8e9-e1cbd2400de1.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC83NDJiYzc2Ny1hZjJhLTQxMzEtYjhlOS1lMWNiZDI0MDBkZTEucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=h41tYYi3ZnNzD-miNc1xCRA~Srg9cm1c3NkMwMxKNs5~SXax2PM2XLwVen9X97olOoIjXlfCPjTdNHv7uqvh-pBDcqWKaZKc~~ASOqro1JqDuHNEyLvRaIVTHLoGk1b6ES8N~tCba1Dj~4RUzc4eB05faKhUBAT9lcVJRiibA4r4UVwqA6iS64Qu33lrz6KTWJxT~jsgLOLtUr5RRbtC0YWae6yTBeeMU-lDzgdoiFO9CS6OFTP6lQ1aJ7rSyxnyPl-zLxxw0occ0CbLCY78zvCeg1p-RB0oDOGmzgyzSHOvXedAKCZ877W27zf2BJJpUI-oVIbIDffSmuZeYEHxjw__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)](https://www.figma.com/file/3LvVypJTkFbniTAJ1JCPtT/Date-Picker)  
Figma Component, Date and Month Picker components  
  
