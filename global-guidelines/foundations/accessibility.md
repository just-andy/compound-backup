
# Accessibility

All work should comply to AA Web Standards.

---

# Overview

All of our information and services should be available to any user interacting with our digital products. It is important to remember that all users can face accessibility issues at one time or another.

Web Accessibility Initiative (WAI) is seen by most as the standard in Web Accessibility. WAI exists to create standards and tools to improve the accesibility of your products. There are [three](https://www.w3.org/WAI/fundamentals/components/) parts to the standard:

- *ATAG* for development

- *WCAG* for content

- *UAAG*  for users.

There are many in-depth guides to using these tools and standards but this document should serve as an overview and how it relates to other guidelines in our system.

## Minimum Standards

All of our work should meet a minimum of AA standards.

### AA Standard

> Deals with the biggest and most common barriers for disabled users. Website SHOULD satisfy this checkpoint. Otherwise, one or more groups will find it difficult to access information in the document. Satisfying this checkpoint will remove significant barriers to accessing Web documents.

Source: **[*Web Accessibility Standards: an overview for designers*](https://uxdesign.cc/web-accessibility-standards-an-overview-for-designers-1a4d39f2fe5e)

The key principles of this standard are:

- *Perceivable -* Users should be able to understand the content of media, both images and video. This can be achieved by using the correct HTML markup and clear descriptions.

Most importantly for designers colour usage and text sizes should be legible for users and content should be structured so that it makes sense on different viewport sizes.

- *Operable* - This is principle is more than just thinking about keyboard and mouse usage. It also entails thinking about information architecture, touch targets, tab indexing and navigation with other devices.

Designers should also think about animation and transitions and make sure any motion does not induce a seizure.

- *Understandable* - It goes without saying that we want our content to be available to all users. Following [content guidelines](https://www.notion.so/Written-Content-ae6ee9f675854e1a8cc96ae73fa4fac9) and making sure our [UI is consistent](https://www.notion.so/Components-Ignore-8943747d060e45dc93f4e23ba3f91235) will aid all users in understanding our products and how to navigate our site.

- *Robust* - Any digital products we build should be able to work with current and near future technologies. Although this is primarily falls on developers to implement anyone in the product team can assist in planning and testing their output.

## Impairment Durations

When we talk about accessibility it is usually mentioned in a permanent context however, accessibility is for everyone. At any point a user could require accessible solutions depending on their impairment.

- *Situational* - Short term difference in their environment e.g. holding a child or glare from working outside.

- *Temporary* - Temporary impairment such as an injury.

- *Permanent* - Loss of a limb or physical impairment.

### Impairment Types

Aside from the duration the user may have one of more impairment.

- Vision

- Hearing

- Mobility

- Cognitive

It is clear from this list it is hard to judge the scenario of every user, but what we should prepare for is that a user can still access and navigate our content in more than one way.

## Quick Checklist For Designers

- Make sure any designs have a colour contrast that that passes contrast test.

- When annotating a flow include the tab indexing, Stark’s plugin can help with this.

- Work with your development team to:
Discuss the correct document structure.
Agree on the correct tab indexing and use of keyboard controls.
Capture the labels required for supporting tags such as alt and titles.

- Although we are [mobile-first,]() make sure to consider how information and UI interactions will be displayed on different viewports.

## Accessibility Tools & Resources

### Browser Extensions

- [Axe Dev Tools](https://chrome.google.com/webstore/detail/axe-devtools-web-accessib/lhdoppojpmngadmnindnejefpokejbdd)

- [Google Lighthouse](https://developers.google.com/web/tools/lighthouse)

- [Wave Accessibility](https://chrome.google.com/webstore/detail/wave-evaluation-tool/jbbplnpkjmmeebjpijfedlgcdilocofh?hl=en)

### Figma

- [Stark Figma Plugin](https://www.figma.com/community/plugin/732603254453395948/Stark)

- [A11y Colour Contrast Checker Figma Plugin](https://www.figma.com/community/plugin/733159460536249875/A11y---Color-Contrast-Checker)

### Sites and Reports

- [HTMHELL](https://www.htmhell.dev/) - A collection of bad practices in HTML and how to fix them

- [WHO Vision 2021](https://www.who.int/publications/i/item/9789241516570)

- [The Button Cheat Sheet](https://www.buttoncheatsheet.com/) - A guide on button and link best practices.