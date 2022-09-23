
# Stepper

A stepper component is a control component that is usually paired with content. It allows users to navigate a collection of content in a fixed space

---

## Key Points

- Steppers can control between two and five items.

- Steppers can either step between the first and last item or go through a continuous carousel.

- Steppers have no outer padding and therefore should be spaced, using the 8px grid, be spaced as appropriate.

## Usage

Steppers will always be a child component of a larger composition which is trying to display content in a fixed area.

Steppers should always be placed at the bottom of the composition and given enough space to allow a clear hit area of the controls.

### Navigation

Users should be able to navigate to the each item using the stepper controls.

- Using a cursor they can click on each button or a specific indicator.

- Using keyboard controls they can navigate to a button or to each indicator.

## Behaviour

Steppers can have two behaviours that can be set on the props of each component.

### *First to Last*

If a user is required to stop at the first or last item in a collection then the corresponding icon button should be disabled.

![Img](https://studio-assets.supernova.io/design-systems/16150/adf8cc37-cfb6-44a5-a055-a75d58664cf2.jpg?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9hZGY4Y2MzNy1jZmI2LTQ0YTUtYTA1NS1hNzVkNTg2NjRjZjIuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=Dj3h~gthN8i0faA65JLXVBxBIo2hpuI1xKV7kDvVUT9WktJrDo6iSoBHtumsM~lBecmt0mdmSPl7TfqhNzPNY5qQ-qPOo3YfIQxgu803cJ4G3BSkAM084McfFGxDC9h06gh2K8ZuXTVutrBj3D1FS9YRl6kwVwCDnQYg9F1LJ7291mlgprR2xsr-Itg6CVxzXAbD0wIXuC3NcdC9Nrvl4if13OhjjTeKKHbySPvf8bToibkFq7SlXIVJW3akY~TtCDoxC5H9JTAlwPg2BPY2Dd6Sv0nqAU1GGOVQPeMSC75rtmasHuSRyIb5LPnDW59eZEcqRAvFINEYT0V-3fUjBw__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

### Continous Loop

Should the stepper control another component that has no star and end point then the icon buttons are always shown as enabled.

![Img](https://studio-assets.supernova.io/design-systems/16150/aa5f16a0-6a95-43fe-af59-9ecbed79ade9.jpg?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9hYTVmMTZhMC02YTk1LTQzZmUtYWY1OS05ZWNiZWQ3OWFkZTkuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=nHmJ9ESABsPnUVZGjJA~XYjOKliAQQTHXGu0y1UQQ~gMo4hiUf4Ez4SioJx8-2XC8NkfxHf~2nui3fkeUm~MXn-z9KEMXedhmxuBCib64HMaMAzhnmrOZQkjdM7UFdYO0CFfX1AUee~-0rGtZDKDdIx1a4lDmTr3ATaw~C2d6th5gmj9cVhmZf2idsGOxLSKUpAG~LBEOTmpOsdIkzbqxAIA2qlOQyVj7YQVzOOJXG8Gilu5XEP1M~j3rcKQ2yDnk5K-Gd8ftlLHJC6YqVDSLGql19GNOJX42RefDpk7u8bm9gSLSpd1QSFE95zyyug9kQAyRIUCwCo2XPcrK2e4eA__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

> Some extra info:  
> The Figma component does not have a continuous loop variant as changing the nested icon button state property from disabled to default will achive the same effect.

## File Links

  
[![Figma Component](https://studio-assets.supernova.io/design-systems/16150/a4da1cba-a3f0-4abf-a84e-e0a533cf3424.png?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9hNGRhMWNiYS1hM2YwLTRhYmYtYTg0ZS1lMGE1MzNjZjM0MjQucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=Zs4q-jX3vPnbVFnD-fxq3HpqnyY8hkmTI2RyU7MUSOUzKEEqKgXivp4n6w1wlwctcJmQKQrqJRQIBSkCYZBd2n2vAMZ6q97DYe72XRWsgqTYDIuPXDWz2ppofaJoBBRaM8bct4JweNU8zydR-~hFqKYvUU54n2yz~onVW5zGDUof8ZxZlEN78Tn-uPwcvwhstcdkwLYNydjUL-Ithp~GiOZK8~MReX5Hj4reI7ohJDhmGIaLqLCGIKNlFSIFCyUG~F~Ce-KGRTbm12ZlEtJATvzPjLCtKqq1Ji9evhTU7fzQkmftSFnVVIrhM5QxS1OR1yKjC9HY0jMyWkg1TNrDNw__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)](https://www.figma.com/file/vP51Z0jjUxizLppBka3lUU/Stepper)  
Figma Component, Stepper Figma component file.  
  
[![Annotation Files](https://studio-assets.supernova.io/design-systems/16150/34c31c04-9190-456f-b2e6-7f5b111508c7.png?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8zNGMzMWMwNC05MTkwLTQ1NmYtYjJlNi03ZjViMTExNTA4YzcucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=RViCc5EvMg2DiQ-e1D~CBi9ia5lQQ5YXAqw7ymNxYWoq2KTJLLX6hJqJVeF6xJDHWLLvd7GV4xxXSVZw4Ne562-PnSIIQkosMMjAXbfaSirMQwQY0kAKMxkCKnhqifJZdGub41~w~c~2DkfhnVsDy4U8aiAEuoYVvNiHuwdrS0PV1ZnUqafj~kFZ6X4f3a-tzXQiIa0UD54enHR4DW3f9Lg5kXEn~JTNl~eDNQ3E1pO~Cpqudr8kDvPNkz~j0-qwHD9DM7U5r07lAEjwWmRzCx92ykcfjj4A3S6wmvFocTbrvvFy~uDNWQ1BGLxCbHFG6WFk959TQbnjhL37lBQUKA__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)](https://www.figma.com/file/1rLUiN4LneoXvEetUuZVN7/Stepper)  
Annotation Files, Stepper Annotation files.  
  
