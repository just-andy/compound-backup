
# Pagination

A component used to split large collections over multiple pages. Navigation controls allow the user to move between or jump to specific pages.

---

## Key Points

- Pagination is stacked on small screens and displays inline on larger view ports

- There is an optional element to show different quantities of results per page

- The current Figma component is web only

## Usage

  
![Small Pagination Examples](https://studio-assets.supernova.io/design-systems/16150/1e0249d7-36e6-478e-97b4-9bbedc463be1.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8xZTAyNDlkNy0zNmU2LTQ3OGUtOTdiNC05YmJlZGM0NjNiZTEucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=CWu3juAm7YpWtudOC1JCVk8O7x9B02O02fpJhtlpoR3qoproOzRQOHFS2CvxD8L6ybhmR1XN8a~L1Cibu0BUJPzwmWYofJF2Runjs64SS-0YhPplNPsUOY~v7RO0Yj5dE4i7WkvnRsXw7N1pe0mNYUSAMy4EWVgxT60aATjoVDNbHZEvgAATpnB1XXZBDDiEYmdNmGBKD0kdcYUzy5nLNslkqDzhibt8j7Gd9vQxn3R7V1JVeixZeZjtq8NOQCK-kwHYvIEghsjXyGA~urJWAygfHjL3HSjfRl9hbFFrbSp4f13xSYsHJg19thVBjggqdRZ-97JRoMHUVd~SWvtduA__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
Small Pagination Examples, L to R: Default pagination and default pagination plus items per page selector   
  


When there are large collections of information that are better viewed in sets pagination should be used. 

Pagination should be placed in close proximity to the collection it is controlling, this is usually located below.

By default there are specific page controls shown and this is bookended by icon buttons allowing the user to move to the previous or next page.

The number of page controls displayed is determined by the width available in the viewport, the minium would be five.

  
![Large Inline Example](https://studio-assets.supernova.io/design-systems/16150/69d0fe15-fdc2-4f92-9851-80a464765021.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC82OWQwZmUxNS1mZGMyLTRmOTItOTg1MS04MGE0NjQ3NjUwMjEucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=eeBVjjo2qqUPNCQrwOuU~CMNILUM4olgxKJVo1laqK0c2fCsSSepY-vmSnuVNZlml99lW1w3fme-t-3w82ZeTsF0UtmuAI8Uq5sZniZjknV~5rhDhzsy63ulKoCf4JDIgPgJnYxUMEfZPfjRLXCODz1i3Lb3dFNgKWow1K-zL2u-UAVIYlhM3KcVYRqfS-w7I0GA5~N7g9qyNbYG3FqVqsQjdv~EXyvAz9CWsISVGjTpkLESHyHC6lY8fMlcHO~Z9iKvOpRuFjBIzngjXt8h0gHQaKUJsAKSZeBi6f8FP-sFlc1IVWCSWTwqkUNIDZvykGq9hdABW5YYYaPd0QKR4Q__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
Large Inline Example  


The number of items per page can be preset, or optionally controlled by the user.

The first and last page should always be displayed, a non-tappable separator can be used to show the division in steps.

  
![Pagination First and Last](https://studio-assets.supernova.io/design-systems/16150/9abd7d1a-e41c-42a5-8596-12e2265f0cf2.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC85YWJkN2QxYS1lNDFjLTQyYTUtODU5Ni0xMmUyMjY1ZjBjZjIucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=EBzjaTorbVKl2obdPCU8Dsl4nkf~~Yha~xfCS70sxJxdgp-o~MhCioxvaEd6upN1qP0xMJiP1FWPieEFifljSh1GmZsXqqsNjLQA2q6ku400BGLss~5mJukHtbHUHXzDg2jyayz0laeiL9aNYDy9UtrUDTh506A2VHc9nZVMxfoKfNMUendwy6yPgh3RpyE1eOxpXf8udYaQz55G4FC3VBYSdx7Txr3jVVzbtC49ySIU-NH8NO-X3IENz6GZOnnZUlU8ZLzIi1thoopC5sEk0w71LXBhy11fJGiq5L3KyOxeJKph1kzmNnrEtY7Wg2TJ1XWDxtlzM8dBlsaGdBYmgg__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
Pagination First and Last, L to R: Default view of 10 pages, view on the last page  
  


## File Links

  
[![Figma Component](https://studio-assets.supernova.io/design-systems/16150/937213b2-f055-400a-a4d7-2c099e5d8abf.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC85MzcyMTNiMi1mMDU1LTQwMGEtYTRkNy0yYzA5OWU1ZDhhYmYucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=Tl0WhUog7uo1IEHPYwa8dCa6SyiR~gclKMRtCFV4Z8ckD-jTxa-FKak5TrEXbvsuLkfe1OsczaD7sJravr1~JQXtd9xeI~bLtqvWIE2CiU5V~9ijGx0jZ1oWhksXHKLJodgSlxLpXaeZjx9UfnlmB~i0kbrwyC53KMawfWDvW0jKT7kXuBIzAMsslJ5xxaloiuvM-4ZK2B3sxrrgkX06AJBvBpnWAMK5XYKPXPXp4DsyF~9WyIABcjynY7T6KaKNGyn2BOjqzzcZuIVOZAqNVS7HrvlyLGVJfN~RbA4t-owQma9jCXPC6d5m8H7qfp8Z93qFLEWqCflkUV4yjwq8Og__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)](https://www.figma.com/file/RY0ZdRAwmFgnYaTG3IGA00/Pagination)  
Figma Component, Pagination component and elements  
  
