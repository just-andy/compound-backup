
# Breadcrumbs

Breadcrumbs are navigational components that display to the user their place in the hierarchy.

---

> Be warned:  
> This component is still under development, see roadmap at the bottom of the page

## Key Points

- Breadcrumbs are mainly used as navigational and orientation aid that allows the user to understand the structure and hierarchy of websites and applications

- The current page should be displayed as the last item in the breadcrumb or as a clear page heading below.

- The current page should always be shown in the breadcrumb or page title

- The home link is represented by a home icon button

- Breadcrumbs should sit above the page title when they are used.

## Usage

  
![Standard Breadcrumb Example](https://studio-assets.supernova.io/design-systems/16150/02a159cb-6e97-4989-bed6-683ec6d1d584.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8wMmExNTljYi02ZTk3LTQ5ODktYmVkNi02ODNlYzZkMWQ1ODQucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=LDEASWjsJC5fD0vZ83ujLBfkE9xYDh1YDOVJLmTZCCdCM96ufUb5P0j5aw4haDt4AC~SAvKVB7Z5phvEGQzNhIzcbvgXe~mhowHvHq5uYBb0Hlrh2JcTgkbVzJShkwwDrCfiW11iokMcRPUfxcRfxZrQqIemuLxPr2Q4u6zMgmz83LfroiJ5j-oogvdvfatr3boVYqpS9C5ikYnwoY~1h9adVqWmG55FWa5RryO6CoMJHpav7zhtU01q92YmKPNOmxKWC6cvZMgsEY5WJIzoxB5Xa5APZ1HqEx4XMxHGkODMe~Ie44jDMMk7CDjSpEQX9xUmI888LqiC6tZKAtZRYg__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
Standard Breadcrumb Example  


So the user is aware the the current page should be shown either as:

- the last item in the breadcrumb

- the page title. 

### Structure

The usual structure of breadcrumbs must include:

- Last item should always be the current page

- First item should always be the homepage with a link to return to it. It will be represented by a home icon

- Middle pages should be linked to the corresponding pages

Middle pages can be shortened to a truncated link if there is not enough space. We strongly recommend at least showing the immediately higher level to the current page

### Hierarchy

The breadcrumb hierarchy should always show the user where they are in the journey. Starting from the home icon and then displaying a text link for each level in the hierarchy.

### Truncation

  
![Truncation Example](https://studio-assets.supernova.io/design-systems/16150/56d1a7d6-bef7-4509-b8f0-74fd3725f25b.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC81NmQxYTdkNi1iZWY3LTQ1MDktYjhmMC03NGZkMzcyNWYyNWIucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=EZSrVwYnU0Q9y7a3iiQiSkFp-kLsIc0yzrOTly17RTDHzu~g0GtJhVCx8R9U~-3KY4-YTeUNj6TYeunFp8~0fwkG361dQTu7TWYmGIIuP3NtWI9jsSPUhTp0FFPeBMXBce9pRKwcqVUBVG1vRHyrwdnHSq8Wxm~w~pxqFBpc-0uxv9a~QLNpia9iCBnlakeqlcbSKU5f5pD7k-r-ygDqPAi8GzMYFEUXXz8xAEOg5nhYt4I7T3JUNJc5OE41VGjEH7ptCUCnHwE-gQrPIzy4hbYQVHLu4YV0GIBQWEhcXGO3piOcjPEkKQ6Iri~8Yc0EV~Ultwel~LVzisZW2A5I3Q__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
Truncation Example  


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