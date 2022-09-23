
# Guides for Designers

Using Figma consistently across the team makes it easier to share and collaborate. This document is specific for designers whilst other guides in this section can be referenced by any member of the product teams.

---

## Good House Keeping

- Make sure all layers, frames are named to be clear to understand, *don’t leave default names e.g. Frame 201.* Follow the naming conventions where appropriate. If you are using a frame to group items together name it *layout*.

- *Don’t use *[*groups*](https://www.figma.com/best-practices/groups-versus-frames/#groups). Frames provide more functionality in controlling their child elements.

- Follow the guidelines for [setting up page structures](https://www.notion.so/Setup-Structure-6100e77469de47638d91056beced11cf) consistently.

- Make use of the version history in addition to branching as it provides a solid rollback should you run into issues, particularly collaborating with others.

- Use shared styles instead of customisation. Although you may know hex codes off by heart, using shared styles creates a more consistent experience and documents easier to manage.

If styles are missing them [create a branch](https://help.figma.com/hc/en-us/articles/360063144053-Create-branches-and-merge-changes#Create_a_branch) with your proposed adjustments.

![Img](https://studio-assets.supernova.io/design-systems/16150/59aa257d-53fc-4f08-a3f9-1b1dbd4160e7.png?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC81OWFhMjU3ZC01M2ZjLTRmMDgtYTNmOS0xYjFkYmQ0MTYwZTcucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=T45Uum2cjKqPN~FiGg-yCm42nhmAS0ciCSbphWrGRE33ry8t5Ra3RtMMAtpo9pdD2afsXVyWElrc11Yy5sfHeVLGc7xlevQCQolwJ5VFt6TUWq4ykl7ZFI~yOZxddHUaicTsgduPKkAHWip~Ctdx5u3Cz8RbP8KrxgdxAkfDgF86wqlxFknX9zu-f-~PSBnICL8Mcva6-byhXm0HVdbqyzmxHnoQL0xEqsLlwPVc7vmyC82gCV2MFpRA5K0~0LbfkYsViM-HR9vMz1Jxb~g-Ae3DVRoRFc7TxV-WwxbB5G9LFqyQSjZlhr9-8K4A9ExrOOxu8vDqVnd-XjZBGFPEYA__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

- Remove any files or assets no longer needed. Figma allows you to archive projects so they are not completely removed initially. The clearer our organisation profile and files are the easier it is to search and work.

- Remove any unused styles manually [or with a plugin](https://www.figma.com/community/plugin/1052937551486129898/Unused-Styles-Remover).

- Keep Figma and your component libraries up-to-date when prompted.

![Img](https://studio-assets.supernova.io/design-systems/16150/cc22c11e-6e8d-4c57-a21d-8501c43a66f4.png?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9jYzIyYzExZS02ZThkLTRjNTctYTIxZC04NTAxYzQzYTY2ZjQucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=E1uZPPVQxDMeIrdIHcjRT~VmAhvHz4m4UR6JUTQf8~XN4D05OW4Sywxo6pL3pvy3~quzJf6XwJ2rSBPUkxh-Nwy3XLmxKdDeHFWM8kBx7h8kaRrWHdN4O4jykaJRCtIxpBA~d2rG~ZnnxcC7dT6HRpDn~3w86NdyY1kJetGnxdxd-ZC8lEbEnGoBjh4Ur8MrhCzNFFWd1rrTUF2P0xZ0w8KIxs3zh8qKcQ-xV6A3lZUf2pPIjg8UOzBwRqVWUrfvypGOJ-Ld81tWLPPibUGA53~K9zswC5HxrCKwIMPHgJr0KF2wkyMIHL3EjrrzA~zDfI~gF7~4urma1s8jL5r4IA__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

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
*Layout* - Used from any frames used to structure or position elements.
*Content* - As above but the elements inside will be the text or images that are editable. This makes it easy for the user to find where the editable content is.


- Frames that have a collection of nested components e.g. lists or table columns should be named descriptively or “Collection” as a fallback.

- Use “+” instead of “&” or “And” e.g. “Primary Button + Icon”.

- To make components private use the “.” prefix, not “_”. You can find out more about [private components](https://help.figma.com/hc/en-us/articles/360025508373-Publish-styles-and-components#private) and styles in the Figma docs.

- Prefix all component file names to match the platform.
Web / *Component* - For Web.
iOS / *Component* - For iOS mobile and iPad.
And / *Component* - For Android.

### Reserved Words

- *Layout* : Used on layers and frames that are only for structural use.

- *Content* : Used on layers and frames that contain editable text or icons.


![Img](https://studio-assets.supernova.io/design-systems/16150/0dbb5f6b-a347-4766-9ffb-2e50156d48d6.png?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8wZGJiNWY2Yi1hMzQ3LTQ3NjYtOWZmYi0yZTUwMTU2ZDQ4ZDYucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=cycP1e~7mQliLOYUxE41ySk4PKXOTs46egKDfFoaRHMI05~4rWyWHQaJqkpyXxp1p19EF~mB17g4xpJHSWqmPw95pwzKzyyZYwrRL55T6UcLczSs6loxuREWk1YLRYJTlFx0Wo6Avvh1BMnQKamCcY6HYEC9z7hTkGV-v91tNtRhX46tZlymnyS-86FzIzJXT~gHysb~wkW9nt6CUrZf-AyZTuaiBn7nmX-dRMorqkiL6yVdoiNRLoBEadf2FJU30m16qi-ST70fIQSzG4LVoSDmJRW5XSLG-iXVDf3yEg8k9Y4pKWIZLN7Xi0gbxvskuWDOdHen6rZn4O6qGh07Dg__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

- *Collection* : Similar to layout but when the same elements are grouped together as a preset e.g. lists.

- *Label* : A default for any text that can be edited as ** Content **, if no other text makes sense.

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

![Img](https://studio-assets.supernova.io/design-systems/16150/3405d20a-38bc-418c-ba11-3a84af2ebdc0.png?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8zNDA1ZDIwYS0zOGJjLTQxOGMtYmExMS0zYTg0YWYyZWJkYzAucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=NPsOb2wNRUUpuwmztBWtCSyeTu0GhoLJMtqOfhuVi9iIN5bzBYAYN27Q9rPDP4kKVE2bz5y9Ts6f3woRrDAMvC7IrOMZjU3TUgDowyThKpAcHl5gNHO1iQsFOkFXVkR0V8PJykM~gTy7kHNYrnh3Hk4s3gFDJC2saKznDgEbTe8RYsQ8~7IAJmxqTQGbyUASycvQ-pB7oaV-PburgiAp~eCn2~EuZEbro0mclcdLrH5bx~FtAvn-DoKN4m5gUSpcywi5ZUFRa9QZwl1TmvWdEkWd55CfDpDZ-D8bPDIO8GcTrmXz6AyJEuDAEcTceOgzVW9iAmJZEEXFZL9maVH6~Q__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

### When To Save

- When you have got to stage in your design that you may want to refer back to.

- When projects are ready to be published, reviewed or shared.

- When you are jumping into a team mates file to help or collaborate.

- When you are about to branch off a file. Figma does this automatically but the icon makes a good visual reference for scanning.

### Writing Good Commits

- Make your titles short and clear as to the change.

- Describe the changes that you are saving, bullet points is the most concise way.

- Try and keep the descriptions short, it saves expanding the view in the version history panel.

### Icon Key

- 🛠 *In Build* - When developing out an idea this is a good marker

- 🚦 *In Review -* If you are putting a component for review with team mates.

- 💾 *Published* * When a component has been approved and ready to publish.