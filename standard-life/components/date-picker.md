
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

  
![Date Picker](https://studio-assets.supernova.io/design-systems/16150/6cb3a9d4-508f-4e8a-af89-af76edb4701f.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC82Y2IzYTlkNC01MDhmLTRlOGEtYWY4OS1hZjc2ZWRiNDcwMWYucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=hM7L-a0jGZdQsmZdOmVHNc7wjG9HncKYEyZBPrxjhbrULy~~8EKJjdCJskCrM9k2g4XMCeliSGVZnnWk9W8BGLbIDaXxGmHMe-IsLOykhhJEvnkFQZJ7l0ZthhJkn48hx0oOqmNqeHZ13~-DqAAulQDAfKtzDWkcFjC5nOAQ59Rjucm2XTXwfGQQFR8Wu75A36Pq0saEkNf~EWsIoYHKzZB9LZXDpVoAB4d1cBdoEbSSP40-fnrO00BQb7ftMXBYzKl1IW8-J5Nmd-PuCxz7ooZD0uYan89siyRaxXHsAT5YHF-5dsQTl7nS6qOq44q~QoJJSQMP-pvA9elqkuG1QA__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
Date Picker, Example of the date picker and month picker for web  
  


### Month Picker

By default date pickers default to selecting a day. However, there is also a variant to default to selecting month and year only.

The placeholder content will also default to date/year, ommitting the day.

  
![Month Picker](https://studio-assets.supernova.io/design-systems/16150/915d1506-c0d3-4cdd-a865-0b2160e3df64.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC85MTVkMTUwNi1jMGQzLTRjZGQtYTg2NS0wYjIxNjBlM2RmNjQucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=GVHtyK4gzbhDn7GMngmLqQIdvniKU1MuC2nsVvw2Ot-95N5PooN-AhVlBAsVE1v~pd3LIH9ovnZajW4FEXLLWRdcntD9fpZ9vuUaa3iiUV8c4QkYJpOcGOej28Stw0hXKXb3TFeW9WDgvqjQ8tHVFOIcTdEIvLA9WX0YK4tt9CNKmfayXfcACJBSIiW8P8uYdMgYZNKZ9VUEbfPM1b1meqLCLmcHeZAwk6Q1aG3UQqOoTaW-09tKKFBKmVqzDv-thDJ5S4xr9H7QEDp3wMVNVLHIM~~eSgsVe77flyv2hoDgluFcLrtejGSuYK0iPnHakDOb1NAzjEcC1eDnE~4zgQ__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
Month Picker  


### Date Range

Use two date pickers side by side to all a user to create a date range.

  
![Range Picker](https://studio-assets.supernova.io/design-systems/16150/408f1886-bf4c-4701-b98a-0b6969a5ed10.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC80MDhmMTg4Ni1iZjRjLTQ3MDEtYjk4YS0wYjY5NjlhNWVkMTAucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=HTlLZadXra4XemQUjuPmIs8DrUorkJTXioi3qcgRiFouUimS0tIunGfQkZCd-GWLTMMP05dZrRaXjvjo7GbLgNasynBy7p4mMoLRUetdVxvt7wFcLG2aAHwekGvDXTb0ftSOOw0V3I~7nXEjMPgvvRhsoChThqFXZ-mKSW57ma3Zpneq~bAvZUKKl21mKSTfu4zOSQYEYI43RteihFQzw1RuwF1DIhRAPmDeBgAOrr6Wf3jumjYzyLmAass5uRwYUdFw1NYQg5HtpLoAiTU4ibNwArASwLP9n1-xXft1ZuddfpJxOamSytaHPv6VQcSMZ9tMVXNXOd1XOz2Fpc3Ijw__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
Range Picker  


### Validation

Date pickers should handle the logic of making sure that the date is entered in the correct format. Any further validation about if a date meets additional criteria is out of the scope of the component.

Like all other form inputs an error message will be displayed below the validation field.

## Memorable Dates

When asking the user to input memorable dates, such as date of birth, we should use three separate [text input fields]() and a legend heading.

  
![Date of Birth](https://studio-assets.supernova.io/design-systems/16150/91f4263b-4681-419d-8d5e-44426b2704b5.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC85MWY0MjYzYi00NjgxLTQxOWQtOGQ1ZS00NDQyNmIyNzA0YjUucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=NVziKF77dRe2mIBPdCUwkiR7zoUZVbB8~3ftMBAgGbEKOcrMAEv7FSp7RM43ME0PY8UShEx0~H4tq0Cm6vCUZsX7~DFwgLhDinf6J~PSIVd4BwaJy~pFzbli6I1W6BcLF2sZOVJ5EgHljlCrzrcgOzMi4~TGbRrXX1f4JQ2IFg8TMmofFFSrC1t-zSAu3XXkF6b3Ueq32ujeF-1KRZi~CcCepNrdigP95w~PY6EtVLZO4nLWULdsWS~eWB2dIQNV4hmqSe5ASWTH-IwjpkuJujKYR0V3e3wJGfAZj9Ep4dCNi3j-Slogekx1Jh-ig1deCYgsz97UlN1govKMnUC5EQ__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
Date of Birth  


## Native Specific

The native date picker has the same usage but uses the Ionic date picker that has a different layout and the addition of an additional time parameter.

For more technical data on this component you can read through the [Ionic documentation](https://ionicframework.com/docs/api/datetime).

  
![IOS Date Picker](https://studio-assets.supernova.io/design-systems/16150/4986cab5-f657-4114-a156-b4935621778a.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC80OTg2Y2FiNS1mNjU3LTQxMTQtYTE1Ni1iNDkzNTYyMTc3OGEucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=RtTcwhXc9A1KBv6q1IsYV~hbVH~7r0Q10EBZneYi9zLeRP8o78XyYMa98DVPSampVMrAxHYl~U~nXO81fP1fadpoF2CafAmc9UYm5skEin6db9mk65iXonSVkOIh8wk32eshH7YOjMkZEBfsOx88s7G8TM5YH5kOSf7ujjgmWujIAfh-PyRGg-seDQsPwiJl0PrWqKuty8N9sM1e0otPan1Y1O~VaAnK-vbeIPh2n~U9WfLDqqH-l4QjfQ64WdY9PuV3TeN0wXpWu7uKyxpgsfm-svWRik~YW5hQFwi8H7EILOb05fT5WDRv0eRA0n-~CJtmCF0Pb2-~TSohAlFrYg__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
IOS Date Picker  


## File Links

  
[![Figma Component](https://studio-assets.supernova.io/design-systems/16150/742bc767-af2a-4131-b8e9-e1cbd2400de1.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC83NDJiYzc2Ny1hZjJhLTQxMzEtYjhlOS1lMWNiZDI0MDBkZTEucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=h41tYYi3ZnNzD-miNc1xCRA~Srg9cm1c3NkMwMxKNs5~SXax2PM2XLwVen9X97olOoIjXlfCPjTdNHv7uqvh-pBDcqWKaZKc~~ASOqro1JqDuHNEyLvRaIVTHLoGk1b6ES8N~tCba1Dj~4RUzc4eB05faKhUBAT9lcVJRiibA4r4UVwqA6iS64Qu33lrz6KTWJxT~jsgLOLtUr5RRbtC0YWae6yTBeeMU-lDzgdoiFO9CS6OFTP6lQ1aJ7rSyxnyPl-zLxxw0occ0CbLCY78zvCeg1p-RB0oDOGmzgyzSHOvXedAKCZ877W27zf2BJJpUI-oVIbIDffSmuZeYEHxjw__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)](https://www.figma.com/file/3LvVypJTkFbniTAJ1JCPtT/Date-Picker)  
Figma Component, Date and Month Picker components  
  
