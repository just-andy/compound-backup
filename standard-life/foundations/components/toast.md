
# Toast

This component provides visual indications similar to alerts but is displayed at a higher elevation. These are ideal for scenarios where the user needs to be presented with an issue that may be outside the viewport.

---

## Key Points

- Toasts should use consistent styles already defined

- They sit at a higher [elevation]() than other [alert components]()

- Messages should be brief

- They should be consistently positioned in the viewport

## Usage

Toast should be used to indicate the status of an event that is off or outside the viewport. This component has similar to an [alert component]() but with a higher [elevation](). The elevation is important as it indicates that the notification is not related to the page itself and is of a higher order.

The default toast message can be used to display a generic message to the user. Toast messages should be short, ideally a single line.

Toast messages should not contain all the content of a notification, only that further action is required.

![Img](https://studio-assets.supernova.io/design-systems/16150/4fa94308-4d2d-4436-9fa0-49bbac5147e4.jpg?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC80ZmE5NDMwOC00ZDJkLTQ0MzYtOWZhMC00OWJiYWM1MTQ3ZTQuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=hyfqdmna1HgO5yhADY5fe4rCDluvzdW~whMpnLYUTFvAgFxC46lgvPVYVr8Z9715sgQpXb6YUPfrWuMvAlJhpo8tJThqWiukObPdjAJEk5WnMs1pA0CdmzhUF4vSFR5M~Quru7S7BgHRDYFO~CICmTAfQ2nJnVc28bDhNg0s7XiyNNF0Ml67BFdwE8ZLqEFHqJC9jw3jYMz38Y-uPOLT~PoP3rR1Cj7j7mEJFO9HpvpJ6ZWligK1yg4l2XvPBHV3S0AZ7xCmuoMNpxKtwxznXcFDlZugxXbiGKZdZJ1IfIigYmWAfNrLecK0jWLgYGkdr6YshlJOZBDjXe~yVBW8jA__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

### Success

If a process has successfully been completed then the success variant should be used.

![Img](https://studio-assets.supernova.io/design-systems/16150/705fd48d-70c5-44e7-aa4e-2a4f8f775f78.jpg?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC83MDVmZDQ4ZC03MGM1LTQ0ZTctYWE0ZS0yYTRmOGY3NzVmNzguanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=VyUKocZKT2X2DI4VL-osKxgS4QP7cFbmYhm4RDXb3NOpGe4DThL3vYF-pzi6WCm5ddPwWXQ3VHA5S0f5Wt1qn3pNKtvfCCb3fxPCsTHkC7rK2P4m1rqbZO5q0p01YgYo6Y~Ow2QgxFNt0oFzDEfaBn~sU-KlUhfVTz4ru-p1REJn2aY3LaGg7HVuUSQtNHmFWQA5tqYvn8NYTzuhzGO5nS3~G0dStTj5KWCIVmTdpoo7qsAHxHntRXOw5rT0GO~gZ7g~Qmf~8MT6PXy5IUvtagBO73LJZ0LDM7H3zGfsyR2TCQMIrVImr8fe-Q023r-x8cDxYHkUNhStWsqpTEwNLQ__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

## Error

If a process has failed then the error variant should be used. The label should indicate where the process has failed but not attempt to display multiple error messages.

This component could be used on [long forms]() where there is likely to be inline errors outside of the viewport.

![Img](https://studio-assets.supernova.io/design-systems/16150/f9c48915-14d7-4dcd-b4dd-1f40c7eaf78a.jpg?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9mOWM0ODkxNS0xNGQ3LTRkY2QtYjRkZC0xZjQwYzdlYWY3OGEuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=hPrqf4XkeNLOmpaiRH60fSRvRBvpJ~nDJJXMJE2PFeA6ld~Jgibq5MJBaHRw5Nvvm6ZxGh9nWMkw5CuozLyEhqnkonS2AJEvie4i9GPnB5AS8K1MpJMEB0jCTrTrO8lkHMwOetRaAB2aGdvGPSyyzbrkZRqmbpofD~COcdxQb6skZ4ksYa2U6EOyOkAGyPEGC9793xPsm1KRWlzgDRPkLveToymGU2XdOiGCW6ZgMLNR4odC7m4HKzIITzt~d4C0bfL~s8QZjXBrhaSFvYjeE59cv6r~0VOFuxdKAsL0r~Jhwv~6FAVOx4vpaTKQthPBDBK8tae7ix~0Ts6MUHjMuQ__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

## Positioning

> Please note:  
> How toasts should be positioned across platforms and viewports has still to be agreed.

## File Links

  
[![Figma Components](https://studio-assets.supernova.io/design-systems/16150/e5997e9e-c604-40be-bb82-7ba8df459167.png?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9lNTk5N2U5ZS1jNjA0LTQwYmUtYmI4Mi03YmE4ZGY0NTkxNjcucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=hjiIjq2689y7m1HLMCglt7-2XHJrkWxkPj8C7itEHY2ql7ymQ4y1rBxlIELfbc2YiQC9sljWjLYHzkpPkfFut7w7Bh6xlm7Dg-pODhpiqIQI-UPIQc9~YfJPBLPBHIv0IhMmCQQQRBNe0ZRI-Hdem0dzmigZ8WnsswBSj-1BgOQ1pb3PWLuMzYR9MponWjkuXnBJg1bxfb62qvrmMPezjBT9-MsPnzCbmFkhaIbJjO0Qw9ZeC6tVubL9VvlySIuY29mo-NyhjSy5xT46gFK1gbmN5sw-LzOc42S1clqLGKm2wM0dJ0tT7uGhIwItrHONkWfcq~IL-tVT6STxXrrnJw__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)](https://www.figma.com/file/CK2yCzWcnw8Uns15A2OpTA/Toast)  
Figma Components, Toast components  
  
