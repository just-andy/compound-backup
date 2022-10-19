
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

![Img](https://studio-assets.supernova.io/design-systems/16150/a6bb0e02-ac3d-4e62-a746-ef9f598c07ee.jpg?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9hNmJiMGUwMi1hYzNkLTRlNjItYTc0Ni1lZjlmNTk4YzA3ZWUuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=JtNkCclX1~rJz1NQg80wW7eBQc9gIKdXOaAByrGQddFZcKkM3O6pBY7jbR7L2WKwEpxX9ct6SSgGy6xE~8GNjgtRyPWgeO6dQKI6mPd6Hx615KeJNR0WwKjFhSTeda4ksnvyRl-H-~mGa9tSqTdUg~acJOa5D1piB8m3iDL0NwO9RxbJm34LU3~jUkPcTccDdnDZeIa6JFz7yd1wUwAxMOsVIGa-kfUNjjnw6Bslw830lY15xi~ByEMLfEr~014GZMRR7RvoGQIPxIFWV~TB4WZ~5pcHI8EahtdQGYlmd4qabTocZpKnujzjW5VJVHGMOMewtxFHFuubyC-~KeAnXA__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

So the user is aware the the current page should be shown either as:

- the last item in the breadcrumb

- the page title. 

### Hierarchy

The breadcrumb hierarchy should always show the user where they are in the journey. Starting from the home icon and then displaying a text link for each level in the hierarchy.

### Truncation

![Img](https://studio-assets.supernova.io/design-systems/16150/b524f88c-611d-4051-ab9d-66d448f109a7.jpg?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9iNTI0Zjg4Yy02MTFkLTQwNTEtYWI5ZC02NmQ0NDhmMTA5YTcuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=cRHwdZ9Kqqj3gQtJ7bcey~exzgAcocso6sfWsFT3CvAVXtQ1PgEhr3kH~08tXek0LMmJL9aI6s~XNch5T1sI3Wa4tfuJCHOIvhXfhu4nGkhjQ2P7HOgNzMGRvpC-qCnGGK6lKAxJEzGdhxgCHpV6YDNu36JUsDtNYjrrkBDtcENI6VYoBSOjFMpGkRT8yE83dGpJw9paC5H6XEaLynxycMpDPawpojF2IawSMSWlxqmzXQSSgpmU3u2q6UMb3OPEU0p3es91R8II2S0MX3qXWa7ZaXRA1jLTlBa1~aHcVQR0taZ34JGAGWL3tJKXrKXAJv1L2Q6sn7e1OoXyWVjlCg__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

When a text link is longer than 12 characters it should be truncated, allowing more of the breadcrumb to be displayed to the user. The full label should be available as a `title` tag so that it can be displayed to the user on hover or via a screen reader.

## File Links

  
[![Figma Component](https://studio-assets.supernova.io/design-systems/16150/13ebc76f-03f0-449b-8b4c-32c79f842708.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8xM2ViYzc2Zi0wM2YwLTQ0OWItOGI0Yy0zMmM3OWY4NDI3MDgucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=JmnqpL9K8eBNYfTJN3jR3nkZC35lbym1pIaug5LsIbXMBYGr-KNhfRHinwA7S0RZldCPh~rGfbc8KSGnnhGzvg4HcjdZNm25n65HhtMIatllFDc9vul6IYoIwl2zOiTRxWJRaUYWs2Rzfd0jvPo86MI2CDqL4X64atvj-RKRpBGK5GHXlL1Xx0008unS98yGrxmrN5OxlzHHLz5-vkJOKUkBnZRlRcTvo5yDx4hQ8ED98yOjC5imGw3KXkb0KU7fyg4bypTjF2jnnkr-gyy2GMSYGZs0OrUVHyAw9a9c6Zbh-v27~XQEn7rk6LGuBgBTDNuT~JdyHcvoJmD4GHtUpw__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)](https://www.figma.com/file/VzlsZkoSTQ2qhpGmXBM950/Breadcrumbs)  
Figma Component, Figma component and annotations  
  


## Roadmap

> Some extra info:  
> The following issues are still yet to be defined

- How should breadcrumbs be used alongside titles and steppers?

- How to display the full label to the user when text is truncated?

- What is the UI for breadcrumbs on mobile. Ideation for this has begun in this file.