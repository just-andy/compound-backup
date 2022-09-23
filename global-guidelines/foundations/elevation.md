
# Elevation

This principle relates to the distance of a component from the user, as a result this affects hierachy, colours and shadows on the interface.

---

## Levels

Elevation can mean many things across design and development but keep it in simple, generic terminology of levels. The higher the level the closer it is to the screen.

Our base level, level 0, is the main content area. On top of this other components can be placed to show their levels. You can see where various components sit at different levels.

![Img](https://studio-assets.supernova.io/design-systems/16150/54437d9d-3906-445c-9c85-cf2d9f14fbf4.jpg?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC81NDQzN2Q5ZC0zOTA2LTQ0NWMtOWM4NS1jZjJkOWYxNGZiZjQuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=D~hvrjdlOLPAAfMRmOAoo5inol-PKQbfOCCnFcSYKt44smDF4lKrAg8-Ye8tP-3MHIENSAlnBXQ-JadCNusWB9Ne4Wh~sgK14pvnRxm68OVrbrBzibww8oopfsAkczA8Yd7rHfOxcIRfycnq5rgTXAcXvFp3S41RZJKuWNSDFtbzhohBKGFkRTzdHWhTKwlVBbMyjx9ypU4ZRaV7uwtDlVpDVsPihZMTHXoTweDCh7WnF53OCd~Av50pUDaugtZZD4RkUNmR6xbWFdpBJagFxgTSaygYlNdjK-DfIepo9mFxzZ0ncuSysV9zbZWA-EQS6G7jwjq5jS9w87EmiB~AQw__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

## Shadow, Layers and Levels

Levels are used to separate key components based on their usage, components in the overlays you would always want to be above everything else.

Within each level there are a degree off layers to show depth in the interface. Cards is the most common example.

A nested card will be on Level 0 but could have a tooltip component that displays above it. We use a shadow to show there is a layer above this. 

In the exaple below card A has no shadow but tooltip B has a Shadow 10 applied. If we took the example of card C that sits on a background then Shadow 10 is applied to show this is a layer above. In this instance tooltip D uses Shadow 20 to show a greater degree of depth.

![Img](https://studio-assets.supernova.io/design-systems/16150/6f05f5d0-7c57-4216-8d18-b7608d56b34d.jpg?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC82ZjA1ZjVkMC03YzU3LTQyMTYtOGQxOC1iNzYwOGQ1NmIzNGQuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=mOPkoW7L8h8fXAwAt11XYHU9jyImE~O5dKEEIIWmNG-VjPqWqmzr4eSMzJYyKE2KxJCje4NrZ4l1Jyc5CeZcubx2r4cGfc0~QMTfoR~v-AdGOSXxJvdytUas4UQuuavPP2tiKR6Xin8B-w2xD~4LPFOBJpcc7X23QfgxgjEVoVqckZvOiUBtDUqekAaVlAOyIzV11PG4BFLMf~EHB~MH4NsGEd9088eq-eUpZAcWR7uxiknC4Mdfn67SrhNKp49Hc2rbLQs5Ua63bRI4o~TNSrD-mrbTIgpy1VbKm4~eZcg6MvMjLWNGSZNpHREh4BqlrCpYuDD02O4WN3KyfMldpA__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

There is no strict formula to the shadows but the best mental modal is to thing that layers stacked on top of each other should have a greater depth.

By using levels and layers together we can work with a more manageable set of shadow styles.