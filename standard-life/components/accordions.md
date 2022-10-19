
# Accordions

Accordions are components that allow sections of content to be vertically displayed on a page. The header for each section controls if that content is expanded or collapsed.

---

## Key Points

- Every accordion should have a clear header that identifies what content is collapsed and hidden

- Accordions can have one or no accordion content open on first page load

- Accordions should be able to be opened by default if they are triggered by a deep link

## Usage

The accordion component makes it possible to display large amounts of content in a small space through controlled disclosure. Whilst this adds an extra click to the user finding content it keeps related content together and the header will provide key navigation.

  
![Card and Accordion](https://studio-assets.supernova.io/design-systems/16150/2ca36d03-6628-4178-8680-d93565873f23.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8yY2EzNmQwMy02NjI4LTQxNzgtODY4MC1kOTM1NjU4NzNmMjMucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=Ps12mHCZ7tz4twuAE-x1GK3kMuiq5OMixYj7omFN-dJNn75prgE2TexrFRgQoAyMr59g1Cn3uB~VL-PGMwOslDQQP8M4hhEOrvVi8Z7Fs1eAkUTB4KxpqNJ0NeIBJ9eaCdkWpywQcQJPVHpE~5t38TDhJQIBvUdDr0hEgsHG2b8sY-1px4zdxKRCGRr6S4uPnPlleA~PtwWVrzv11QCTdWnREappto-4HPlcQ~PYwBYMzsgutl5zMc~OCBT4HaRDMIF6FeDWzzfkjyfKVpzmZAIaxr-Exlju4fO6o449-3zLOV~XRjdwdxS85MXkLdiJCT78AEvdnlyUI76ObkoEGQ__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
Card and Accordion, Example of an accordion nested inside an card  
  


Accordions can be placed on a page or inside other components such as a card. Be aware that the overall height of the page or container will change depending on the section(s) which are opened.

  
![Accordion on a Page](https://studio-assets.supernova.io/design-systems/16150/d7f1ec6e-6392-47a1-b9e4-c5b9d59fe4d4.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9kN2YxZWM2ZS02MzkyLTQ3YTEtYjllNC1jNWI5ZDU5ZmU0ZDQucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=HFEwJ1ad5pTBzUBdlWT-JlN3bY~T2xSgBwndZ9csJeZHgM7KLr6Di1GHOHlNawXHFJp9cYKeNaZg6oEg-1TtIrwVa54pdjI8jYOKWUWDdJj0cvNp-R2LAATCWA4FEB0bvo0bf7g3DkLmaP0Xmc4HuuCmDrWMpqGt6GSNxLkbazM78iBlj741w~V8J8FCKYIna8W5rJ2sjOO1G0rXKWg6Mm6taqOf9cN0h5FJzcesZHmUpFF0qp8qjLAhn30LFJdMnY-Bmrz9jtf8ofEktYZhG7Cpo-ZDxkCbGZL91EPWaVkLUovrPmUa6z~vuJC9bjHXAi6oN58OwdHMPXAgFj2fUg__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
Accordion on a Page, Example of an accordion on a page background  
  


## Behaviour

To keep content related within their container the following two changes happen:

- When the accordion is open the arrow icon points up,  the icon down when collapsed

- The divider line stays at the bottom of each section when expanded, this differentiates each section

The whole header section should be tappable to trigger the expance/collapse action.

## File Links

  
[![Figma Component](https://studio-assets.supernova.io/design-systems/16150/05958447-7f1c-45eb-aabe-b9ee21efa641.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8wNTk1ODQ0Ny03ZjFjLTQ1ZWItYWFiZS1iOWVlMjFlZmE2NDEucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=Oo6RmtFebdDMP8w-av27MxnPSn2tZ13k2U2rR~v55v93Uw1OQi2DhjkeDUOMmuy6JiFrhxOOmDnxuxx2Ekahyn1aA3tBMGk8j4kaXGcCa4rrh9vRsnzEzvQEk9jqUbfo16K3mVU0XsGc3euic2Ey41353Q~1-MrPvdS-1GlHY~kw4E7k~6UXYQMN-XJZGm356yQ7uONP7Y4o1yZOe6RlRVK-Vx5Sv6XPYu0WE8Adq5bDJ5GrIRAzjDJVu3aBweAEKsdzqg-HV5zLzcvjf~W5vYkaZgUSjkWGdtrOtuIlty6Eb1UFENbfWuXMz0UGkl17P53h2nN8jtWaWTCJJwli~Q__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)](https://www.figma.com/file/FIcmCWBV2EQgCFJzlWR7yR/Accordion)  
Figma Component, Accordion component  
  
