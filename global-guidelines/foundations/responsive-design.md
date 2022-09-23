
# Responsive Design

All designs work should start with the smallest viewport size and work upwards. We support a number of breakpoints across our platform and these are guidelines on how to approach this method of design.

---

## Mobile First

It’s critical mobile customers receive the best possible experience so it’s our starting point for all work undertaken.

[Working in a smaller viewport ]()allows us to deliver the most critical user journeys, then we scale up supporting content as the viewport space allows.

## Breakpoints

Below are the range of breakpoints that we use across our designs. Our [grid Figma file](https://www.figma.com/file/QE34vuB1YzPjps85hIKANa/Grid?node-id=0%3A1&viewport=363%2C206%2C0.23) provides a starting template for designs within these ranges.

  
| Column 1 | Column 2 | Column 3 | Column 4 |  
| --- | --- | --- | --- |  
| Min Width | Max Width | Example Devices | Name |  
| 0 | 575 | iPhone SE, iPhone 8, iPhone 13, 12 Pro Max, Google Pixel, Galaxy Note | Small (SM) |  
| 576 | 1023 |  Kindle Fire | Medium (M) |  
| 1024 | 1279 | iPads Landscape/Small Desktop | Large (L) |  
| 1280 | ~ | HD Laptops, iPad Pro 12”, 13” Macbook Pro | Extra Large (XL) |  


> Please note:  
> Our approach to content, grids and max-width content has still to be confirmed.

## Layout Grid

All of our designs should fit to an 8px soft grid, 4px can be used in components for narrow padding.

Our [grid component file](https://www.figma.com/file/QE34vuB1YzPjps85hIKANa/Web-Grid) contains optional layout grid styles that can applied to any frame, these are available as a layout grid style in Figma.

![Img](https://studio-assets.supernova.io/design-systems/16150/71be2e1e-daf9-45b2-94fd-cacf129e0356.png?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC83MWJlMmUxZS1kYWY5LTQ1YjItOTRmZC1jYWNmMTI5ZTAzNTYucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=ZVQjDqXPWq5rENWwWLeltvgzlARWWLY7wc6Khdtmqn5zdqCs-C3rntCXm91P7V3CJisccT8vF5gn9PbR77JfWN8wakn0cqY519OBuZ8tF~D9Yz8fUTPZ8Hf~-b~Ll51JZUHlI-NNbSlt-z0AFhzry9uG1hL5Mb3F~EJUtmzeWa3KXqFEiYZCkDXDZq-c-ZoyyiYEaaA99edIc46Y~p6Ce6g~2Sn-8PUPF35WLDvuYLMZ1-LqgVn7z-F-FBL1arCKexmmLvuBrJqsZyEV~7UMf990GPQ6~MbA0bTY1qoMSqAv8u2PB9i7mXTVIvyc87Yf5vl2RBNG-uzDA5yRk83Weg__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

These layout styles are made up of the following columns, gutters and margins. All of the layouts should be center-aligned to the canvas.

  
| Column 1 | Column 2 | Column 3 | Column 4 | Column 5 | Column 6 |  
| --- | --- | --- | --- | --- | --- |  
| Size | Columns | Gutter Width | Margin | Artboard Frame | Margin Width |  
| Small | 4 | 60px | 16px | 375px | Center Aligned |  
| Medium | 8 | 64px | 32px | 768px | Center Aligned |  
| Large | 12 | 68px | 16px | 1024px | Center Aligned |  
| Extra Large | 12 | 68px | 32px | 1440px | 10px |  


## Max-Width

> Please note:  
> Still to be agreed what max-width should be within the context of breakpoints

### Line-Height

![Img](https://studio-assets.supernova.io/design-systems/16150/351b7d20-872f-4bbd-b867-4dc4fba2feda.png?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8zNTFiN2QyMC04NzJmLTRiYmQtYjg2Ny00ZGM0ZmJhMmZlZGEucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=RP9DQXSEdNs~h7ylCHA5NwgVIThKxOeAcSrMEPu1C0DMS97755I8xtBeL7ym40iFDzWxl94FWRaSR8CK3jbStFFysYwzcX9MB4paM6kYVB3P4AOIeHyxsDJ-dWqxcDgvXgTHTFUV4Let9KhiqilteTSqb72RMgpuevMLiesY769QA4xQ2EafyICuwe3fqelNA~l~lR5dw71YehLVar1P2h-BCwR4DxJRor7fjV8SFcObXFr9pF4cmis5wr~5CO17NRWu55oRyxaBuDyOhDTN~QSEne281bxw6-Jvr~U7j0Vwi05OoY4Se1fyyRZ1yu~Lu6jbNK6g9wSTOBfDrPn-pg__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

It’s a soft grid, so there are no absolute rules, but a good rhythm based on an 8px grid will look something like:

- 24px, 32px, 48px or 64px between panels, cards and other page elements

- 1x the header line height before headers within elements or in runs of text

- 1.5 x line height before body text, bullets and links

- At least 24px above and below buttons

These gaps will vary according to the font sizes you’re using.

As a general principle, always remember to group related information and elements together. For example, a header should always be closer to the content it’s describing than whatever is above it.

This is based on the Gestalt principle of proximity.

When applying these guidelines, be sure to look out for excessive gapping or bunching of elements and adjust accordingly.

## Resources

[https://responsivetesttool.com/](https://responsivetesttool.com/) - Test live sites in various breakpoints

[Figma Grid Visualiser](https://www.figma.com/community/plugin/831003768229656707/Layout-Grid-Visualizer) - Converts Figma Grids to frames to overlay mockups

[Figma Responsive Plugin](https://www.notion.so/Responsive-Design-759f5be5df014dff93a8a4aa1d10ba2a) - Preview designs in figma at different size

[iOS Resolution](https://www.ios-resolution.com/) - iOS device screen sizes

[Screensiz.es](http://Screensiz.es) - Directory of screen sizes by device

[https://medium.com/built-to-adapt/8-point-grid-vertical-rhythm-90d05ad95032](https://medium.com/built-to-adapt/8-point-grid-vertical-rhythm-90d05ad95032) – a good article on vertical rhythm

[https://www.toptal.com/designers/ui/gestalt-principles-of-design#:~:text](https://www.toptal.com/designers/ui/gestalt-principles-of-design#:~:text=There) - There are six individual principles, a quick summary of the main Gestalt principles