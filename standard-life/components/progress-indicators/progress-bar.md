
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

![Img](https://studio-assets.supernova.io/design-systems/16150/31dc7801-35dc-493e-83fb-435729266169.jpg?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8zMWRjNzgwMS0zNWRjLTQ5M2UtODNmYi00MzU3MjkyNjYxNjkuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=LekS-41tURBQXxfVD-P9znsgSdB0MCfdWAp7hPo1oFvN9J2GCviS-73F65EqdwJzPCl0K2k9ZluGII7R3VCq0zf2yuvcmtdrDOl8Z4mNmtsgf0jtjWIRN5QggIwTdOSs8nT-Sjjf3S53iWI7jY6iweF1LHlTozvez5rJj~1FI9btfdW4SEyvAvOtSR0yhYb~ssj6pLMQB2~CWdTmS~sqGfasuzMhedOA3W2wa3o1FhbQZ1LMEf9as95Nm0FuG~IIRN-Ql9SqI9xkNhFX~lW73wNR9KUG7za9a5r-H4POaknx4b3d0-BEl6v-maAJSkRvdmSHlf02DrbQlXHMPy3JCw__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

Progress bars are commonely displayed with a label, explaining the process, and a value. The value can be in percentages, time etc. What is important is that a final value is known.

![Img](https://studio-assets.supernova.io/design-systems/16150/12aeccc3-c2c9-422f-beaa-8b59009d2603.jpg?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8xMmFlY2NjMy1jMmM5LTQyMmYtYmVhYS04YjU5MDA5ZDI2MDMuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=lGQgCAQOCE2pik7Zx9xa4GesOGN8SvAUTBH08Ukw4omIVgWRorGp018UziPln8VlwIkOv2RAApUYg2TZNZEoYOshNfmg2cJ-CFoUl1QPfQw1ftzYg91zYKqZvBPaooYeGLxLpfqXW2NYO7Y9bJ3mFHb9acaOKbq5wxmwcrr1j0C~sdZkQQCosp6ZjMy2wHp4DDJ-YYKs4LTkTKQk01WJzrARCdNZwD6CJLTXmRxaHEIE2H~bX~FLuthFMWrrgBbguZPhLsXJpRDkmp5Or6NYFIYLBcxn2oM6st~iPlfmurkNjgDRDOX4lHFf3Od8MUohvfN059nMi55Nh0zcJRWtTQ__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

Progress bars, like spinners, should be placed in the center of the container to give context to the size of the content being processed.

![Img](https://studio-assets.supernova.io/design-systems/16150/cec43a5a-b1ba-4df1-b4cc-a13da1049690.jpg?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9jZWM0M2E1YS1iMWJhLTRkZjEtYjRjYy1hMTNkYTEwNDk2OTAuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=iMa0lm1kIqID-VloBM1DIlfFon2AcRbPD4bZECzKlZA0Tl4s0JJKmy4VUGa5ADSefOs43Uobk236utO90PzI-~KsqUKyZ1CjycSLS1pROX2BgWPQlcWNE6hXLx3HroDPbGKSzQx2uE7cTLgh4DRtUZmIwCJlzcyjpu7Y8SsatZ7m-O4s5JfTiCsNMWe9evA99tQ~AFx4d1ehhpxfVIlMUK9PIokuN2wzVRhzkvvoPHXrhzN-Potwrpw6j12o~MKHw~-QlfvT0J7DkXCQwLjCvdeWKXzLrCKDkt9oOYPlz4cnUNtcyqeHMfm2CjkvISgMSX5xt33s7kmtzo~onbILfg__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)