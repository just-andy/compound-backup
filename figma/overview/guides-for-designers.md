
# Guides for Designers

Using Figma consistently across the team makes it easier to share and collaborate. This document is specific for designers whilst other guides in this section can be referenced by any member of the product teams.

---

## Good House Keeping

- Make sure all layers, frames are named to be clear to understand, *don’t leave default names e.g. Frame 201.* Follow the naming conventions where appropriate. If you are using a frame to group items together name it *layout*.

- *Don’t use *[*groups*](https://www.figma.com/best-practices/groups-versus-frames/#groups). Frames provide more functionality in controlling their child elements.

- Follow the guidelines for [setting up page structures]() consistently.

- Make use of the version history in addition to branching as it provides a solid rollback should you run into issues, particularly collaborating with others.

- Use shared styles instead of customisation. Although you may know hex codes off by heart, using shared styles creates a more consistent experience and documents easier to manage.

If styles are missing them [create a branch](https://help.figma.com/hc/en-us/articles/360063144053-Create-branches-and-merge-changes#Create_a_branch) with your proposed adjustments.

![Img](https://studio-assets.supernova.io/design-systems/16150/59aa257d-53fc-4f08-a3f9-1b1dbd4160e7.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC81OWFhMjU3ZC01M2ZjLTRmMDgtYTNmOS0xYjFkYmQ0MTYwZTcucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=RNsZGA86MCy9rURYLOLD6NEmpwEvHiZfE3IIuVRwDJJi5nqIuyq1zGL8JYqOCegQqinhewL-Ld-~5RMsTI~8vtWaMDZT9zXCA1VERl0oZSWCdEKr2~tvwM2O-bIh~65Nckla2R7CWcaGKEmwK1rDSkV5U7tBpjbfizJrqwccDw5nEKJwseNnDTDUBgtMbSk1V58nojO5yD09inmKSkzIDj4aKo9NLdBQXSB02OK2R26N-tWNuOLw2oJvfYXvtc7WgVs65tPhkaGRiBW4UV0EnQqkORvo53rBAo7p5wlAHmSAckmOrZk5q92eEz9n83CWSOi5BGyy6A4o9TgYmwQ7CQ__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

- Remove any files or assets no longer needed. Figma allows you to archive projects so they are not completely removed initially. The clearer our organisation profile and files are the easier it is to search and work.

- Remove any unused styles manually [or with a plugin](https://www.figma.com/community/plugin/1052937551486129898/Unused-Styles-Remover).

- Keep Figma and your component libraries up-to-date when prompted.

![Img](https://studio-assets.supernova.io/design-systems/16150/cc22c11e-6e8d-4c57-a21d-8501c43a66f4.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9jYzIyYzExZS02ZThkLTRjNTctYTIxZC04NTAxYzQzYTY2ZjQucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=ax6DoxXdLw1o4EWuMqu2Z~xCD-~P6b2RoOltApqEM-RuUpw8Jk-ym-ceh7f2P1j4Y0e1QwiPJ~Lf1zDPgZ4pZEZP19HPBRLwZQtTE2AsRAyzv9OPqa~c0ZttyflCgV1WkQv29J5NN5k8WzEopr22JUn9RY~NcdXsUebmF7Sq8YBh8L7c942wpa62V8Y-GwRUQnOzqcm2BplfcCakl6R6uUjbexdOkRk3CeCF0p-4cM1sGrktSDTDKfCNWgHi1F27YZ2BlAdE2hh-9dZRjcLYOoGStfU0jtcCyvNScDCeTXxwPz03dQToXTZretSNpsqABZbMD0mHFuwrnuRM4OtOKA__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

- Finally, if things are missing from this document please submit suggestions on our teams [Figma channel](https://phoenixgroupplc.slack.com/archives/C03886X1YJ1).

## Naming Conventions

Following the same naming conventions in Figma files creates a consistent experience for people working on files collaboratively. It is also general good practice to keep files tidy and maintainable.

### General

- All layers should be named and relevant, not the defaults of “Frame”, “Layer”, “Rectangle” etc.

- Use UK English for language.

- The layer names of text should be reset to match the content. You can hit delete on a layer name to reset it or [run this plugin](https://www.notion.so/Plugin-Recommendations-479305644ade456aa93246b4fbddcfc8).

- All layers should:
Start with a capital letter on each work e.g. “Primary Button”.
Use spaces to break up words.
Use spaces between hyphens e.g. “User - Logged Out”

### Components

- Nested frames created to control composition should be named descriptively. In most components you will use the two defaults:

- Frames that have a collection of nested components e.g. lists or table columns should be named descriptively or “Collection” as a fallback

- Use “+” instead of “&” or “And” e.g. “Primary Button + Icon”

- To make components private use the “.” prefix, not “_”. You can find out more about [private components](https://help.figma.com/hc/en-us/articles/360025508373-Publish-styles-and-components#private) and styles in the Figma docs

- Prefix all component file names to match the platform.
Web / *Component* - For Web
iOS / *Component* - For iOS mobile and iPad
And / *Component* - For Android

### Reserved Words

- *Layout* : Used on layers and frames that are only for structural use

- *Content* : Used on layers and frames that contain editable text or icons

![Img](https://studio-assets.supernova.io/design-systems/16150/0dbb5f6b-a347-4766-9ffb-2e50156d48d6.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8wZGJiNWY2Yi1hMzQ3LTQ3NjYtOWZmYi0yZTUwMTU2ZDQ4ZDYucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=O~mAzEM1ngOiJ0RhsLSRMxQxcy0cIclcV3H8YVU02rtBhzSzw98INKDubFo95pfS1HI4KDari1aIKFEO4yb0jvd382TJRTjEd5XSwMvCF6CDwGOw9P4rdEP1dp4Qds3mrm1t0ubt9eBS2BBbtImrvlxBLUFy-3uFXaxs3MSRepiVvSa4OFTtXiHpyvVndJtl2zb7sS7w51GKy6fsV3NTqCHZEuQ~BtztCz76D9tgcF2G6gymWBJoRzEW-RqrQ5tJqPyZf~nSaudbdjjJC35kzlI-d4sr4Ir7zRZK1F-Xg0uI~maCY7Glxzc8xFFms2c1yYit5xMFO~54bbIfL-Ij1w__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

- *Collection* : Similar to layout but when the same elements are grouped together as a preset e.g. lists

- *Label* : A default for any text that can be edited as ** Content **, if no other text makes sense

## When To Make A Component

As you work through designs you make come across the need for a new component or a variation of an existing component. It is always worth running through the [“Component Pre-Check”](https://www.notion.so/Component-Contribution-c03e1cc6ee9f4fb7af1eabcafcd6856c) to make sure that there is a need for something new.

If there is a need for a new component that you can work through the process outline in the [Component Contribution](https://www.notion.so/Component-Contribution-c03e1cc6ee9f4fb7af1eabcafcd6856c) documents. If it is only a requirement for your team or project that you should build it locally with approach that this UI element may be promoted in the future.

### Components in Figma

If you are working on a project and you have identified there is a need for a component update or creation there is some additional work.

In your local project file you can work with your local symbols in the short term.

Meanwhile you should also prepare the required information for the creation of the component.

- Proposal

- Annotations

- Documentation

Once the component is ready to be released by the development team, a matching Figma component should also be prepared.

The Figma component(s) can then replace your local file components and be used for future projects.

The reason for the separation is that your local components and final build component can vary and we always want our library components to match the developed components as closely as possible.

## Using Version History

Although Figma autosaves your work it is also a collaboration tool. Diving in and out of files and other projects will be marked on the version history. It is a good idea to save work regularly and the following icons make a quick visual reference to the state of the file.

> Some extra info:  
> *Note:* You can use Option+Command+S to open the Version History dialogue and Ctrl+Command+Spacebar to trigger your emojis.

![Img](https://studio-assets.supernova.io/design-systems/16150/3405d20a-38bc-418c-ba11-3a84af2ebdc0.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8zNDA1ZDIwYS0zOGJjLTQxOGMtYmExMS0zYTg0YWYyZWJkYzAucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=QG8~O6IrFCOBWqOzp14YwO1M6MlRzt0mx8Or9sWqr1VKzUEhZjdDOfX03dmFrkNOQgEQN6b-ldFhUUYU1dllBkpTx6SIOcPt1eZMCPUJPIJybhErOxVXvotMTlgaOEFQXY2boiThzm9uMics3hU8SlND0UhZZlecxIK6Lpg5jFUUyl9cbiCfuBdUexK6EoNfFFCZKyFviYw-zbNu6FrkIGfNbbPVfEarIdrzCRbfexxLXHj9Cq7v0HlMK85bjk8UlycugUREzOqsaCXeeEfPxN57NuVK8EZicUhjIbgygS7fUUSBrrondEH8QEzj2tQX1rWH~dBhKESkXO~9On28hw__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

### When To Save

- When you have got to stage in your design that you may want to refer back to

- When projects are ready to be published, reviewed or shared

- When you are jumping into a team mates file to help or collaborate

- When you are about to branch off a file

### Writing Good Commits

- Make your titles short and clear as to the change

- Describe the changes that you are saving, bullet points are the most concise way

- Try and keep the descriptions short, it saves expanding the view in the version history panel

### Icon Key

- 🛠 *In Build* - When developing out an idea this is a good marker

- 🚦 *In Review -* If you are putting a component for review with team mates

- 💾 *Published* * When a component has been approved and ready to publish

- *Layout* - Used from any frames used to structure or position elements

- *Content* - As above the elements inside will be the text or images that are editable