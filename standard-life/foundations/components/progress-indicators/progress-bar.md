
# Progress Bar

---

# Progress Bars

A progress bar provides a visual representation of the state of a process as a percentage value. Progress bars can be used for determinate and indeterminate processes.

## Key Points

- Only use if the wait time is expected to be longer than a second

- This component should be used on determinate processes, use a spinner for indeterminate processes

- The component should always use the theme highlight colour and the theme border colour for the track

- Use labels to give context to the process

## Usage

The typical use case for a progress bar when the length of process is known. The bar is best use with a text indicating the percentage and optionally a label of the process type.

Should you need a progress indicator for a mult-step process, use the [process steps]() component.

The progress bar component is simply a bar and animation. Animation on the bar along the tracks indicates to the user that a process is taking place.

![Img](https://studio-assets.supernova.io/design-systems/16150/31dc7801-35dc-493e-83fb-435729266169.jpg?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8zMWRjNzgwMS0zNWRjLTQ5M2UtODNmYi00MzU3MjkyNjYxNjkuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=XVasaDnzlKjubZ8VDFOLj4PzK0iJSDoR9U8wMC63HAkc7SzB7Tu3LFox9ozsllUrCw4czyItDZhUXDSPTNKcVcaYKJUrxJTBPHm7bLp4eisPP23ASSWUqIWTvsuTdo~u2FFEsRxpTG8CKrOg6tia6Bg3OBJR3e2M10ZXsS1OU6tQl8Qi03g7Rs-cQFMF7D0swNkBJydHeN9uIrGD2Hxk8Xansvv4QwCGoTS2ac91uilpWZeX0onG78NmfEKp74c-x5hSw1T2WSlsRiZAUGH~FKqUKxj49YhnO0DfvO2pwAUsF5jte7PKWqXV5Dh-xI~WSwVFxpFoIwrrFwBhY32wmw__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

Progress bars are commonely displayed with a label, explaining the process, and a value. The value can be in percentages, time etc. What is important is that a final value is known.

![Img](https://studio-assets.supernova.io/design-systems/16150/12aeccc3-c2c9-422f-beaa-8b59009d2603.jpg?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8xMmFlY2NjMy1jMmM5LTQyMmYtYmVhYS04YjU5MDA5ZDI2MDMuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=U01JpvqJdCxgVzLjv1cyXfs6SMbOb3Ij68iP6hremWUF7EDLFcH~h-3KCmN5XvuzV1F0p5vZomPZ3AVRozs-bb1yxcakFDSjFmE3yJM3vRTbA2ARuLznti4-l3Qo11o5GTawrw5zhYWPEJcKr~uuVdaiZUK2E8PbUvQK5UCaVmc32pQHkwQ09p1ohH~5v2gxgRQZLjd0DGSzBwrpTxDloI8yupbzoif-ZBEPxIUNOSVliPX7qogPUd1OXCboxMcQ6qCUQ2ahB3APCjjlA90p2gFai6cPuX87CnCRTQfIgS93t~B5F0TxC0ZF9n4pD9mqaLMnzuBKwDD1JQMjC1Ynew__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

Progress bars, like spinners, should be placed in the center of the container to give context to the size of the content being processed.

![Img](https://studio-assets.supernova.io/design-systems/16150/cec43a5a-b1ba-4df1-b4cc-a13da1049690.jpg?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9jZWM0M2E1YS1iMWJhLTRkZjEtYjRjYy1hMTNkYTEwNDk2OTAuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=aKo-JF2eYPx9t-RNYJDdBQmiCXi5UYa4z9YqkifSTS~TgTXwGScs41dVvhY5XmrEjO7tpjceHTNBpA44p2Fkm8km-E2bG-T97bqM0FTzMYVXlm0Ki7HlHXxtiMfFGiDYUQupPhgahqegKSlGqvgEDEl4ToYPJFOJdangLjxuRUJDwcyTI116nW6eMpy~4sUS8T4TMXW48htyk9jzFPR~3wUB8PtjDbcRMyGRqqVaSttr6Q4NzK0IMM6DBi5SDw0j7Qp9U9gW42tCdJAmR~C~vGItcYxruws-MwdSalWgrxU6ttrE1HD9PP6YwcpdXB7TBcSVSnh7zuv4F~AVeE1UIA__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)