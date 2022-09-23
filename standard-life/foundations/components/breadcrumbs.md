
# Breadcrumbs

Breadcrumbs are navigational components that display to the user their place in the hierarchy.

---

> Be warned:  
> This component is still under development, see roadmap at the bottom of the page

## Key Points

- Breadcrumbs should always demonstrate the hierarchy of the application to the user

- The current page should be displayed as the last item in the breadcrumb or as a clear page heading below.

- The home button should ways be present so the user has a point to return back to

- The current page should always be shown in the breadcrumb or page title

- The home link is represented by a home icon button

## Usage

Breadcrumbs should sit above the page title when they are used. The purpose is to display the page hierarchy and provide links to the user for each level of that hierarchy.

![Img](https://studio-assets.supernova.io/design-systems/16150/a6bb0e02-ac3d-4e62-a746-ef9f598c07ee.jpg?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9hNmJiMGUwMi1hYzNkLTRlNjItYTc0Ni1lZjlmNTk4YzA3ZWUuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=cyFUFBUEAwwO79gO8Dzx2Yl5c4OCW1yiYiJYYbxGM2KV0Tdi846Nmd5jxvGseI~5NYTYOQYuBrXK-8yH2GFHtChsd5IOfmbUWQ6iMJLruhZ3P-z3akIx-WAm328zpFfBk6~fI8mkJ54QrVydWf9Hg23bARMZ8mLgF4nLYrIkyHUttxQA8tgmUiVi-7sf0AW-goLdW8kyNqfPXftQ1kLvxGnKkB6F02fA3AQAD0OKQHxTzuic4Ma~qIGNsfGkUJBNygS4mw-UuK2AtvRgXz9BiQM0eUgIXu46uwCR7MKkxT8Da2jHfs1DmP3Ti2p1mT8x6RVf9DLhC3GznD8FOcswug__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

So the user is aware the the current page should be shown either as:

- the last item in the breadcrumb

- the page title. 

### Hierarchy

The breadcrumb hierarchy should always show the user where they are in the journey. Starting from the home icon and then displaying a text link for each level in the hierarchy.

### Truncation

![Img](https://studio-assets.supernova.io/design-systems/16150/b524f88c-611d-4051-ab9d-66d448f109a7.jpg?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9iNTI0Zjg4Yy02MTFkLTQwNTEtYWI5ZC02NmQ0NDhmMTA5YTcuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=Q2JvcwUy9B62nUSxiOLr2~PW9r7G82qF06u9TptLGojI7FkV-hg-H3hvAGgjMDk7ftx~rFmNv3zu3dYBvHkg7osfpDMExGw0s5KMUa-bbve1f0triXpmP2Bo~OSa0qFRFIePBiO7Le2t6CFMsX83glXuyL~PTIQ0Zl~Kh-mYDra5t~dNM0OeaSu2TG3woktfDm88Db~8NTHb0ecjyCVKVEC2YBvKSyfwFKw3101e6YzXznuZt3H61fhsYnUSM8av0LCK44rra7mMqO-sHcO0EutRSGJ7jJdOJcdOkZdEP7KDdsAZzIogNt5GhrNAcZmcco1bggYkpk2Tsu5di5-AlQ__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

When a text link is longer than 12 characters it should be truncated, allowing more of the breadcrumb to be displayed to the user. The full label should be available as a `title` tag so that it can be displayed to the user on hover or via a screen reader.

## File Links

  
[![Figma Component](https://studio-assets.supernova.io/design-systems/16150/13ebc76f-03f0-449b-8b4c-32c79f842708.png?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8xM2ViYzc2Zi0wM2YwLTQ0OWItOGI0Yy0zMmM3OWY4NDI3MDgucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=Z2vN0hjdRxcgQTRpkT1khKAHrezJ4CsU4M6vEjkFE3UjUWkPSDnSPn0tacg3zb3r1O6Tt8z~DQF~l1mC4Fn9wrTFounOcZrLBL1UVtdlV-ptOB50M~sdISLc2nhZFG1urVfWWbR0nFofvl5TGjD7Fv43u4-TqWFLB3CmdUy9vrMPtsHGp2LjKox7bK3WaZf-8I2iYB5EqBLzwXQ4XZeSyXCFY6UkFpXg876wKXQjE3Pvui9I40t~PvgDS9FqHJou9TRLYHLOvNowgA342OjppFijYEkD7ZlakOn~FuLDe6Npncwj39Bo0iyRTdP60RwYR19d0JenmsPospYPEJOi8w__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)](https://www.figma.com/file/VzlsZkoSTQ2qhpGmXBM950/Breadcrumbs)  
Figma Component, Figma component and annotations  
  


## Roadmap

> Some extra info:  
> The following issues are still yet to be defined

- How should breadcrumbs be used alongside titles and steppers?

- How to display the full label to the user when text is truncated?

- What is the UI for breadcrumbs on mobile. Ideation for this has begun in this file.