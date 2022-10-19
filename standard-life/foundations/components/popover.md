
# Popover

A layer component which can contain custom content and is triggered by hover or focus events. 

---

## Key Points

- To create contrast the popovers in the light theme use a dark background, and the dark theme uses a light background

- Popovers are trigger by an icon button, this should be within close proximity to the content the tooltip is supporting

- Popovers can contain text, media and other content

- Popovers are triggered on hover or by being tapped on touch devices

- Popovers can be displayed in multiple orientations

- For text only content use a [tooltip]() components

## Usage

Popovers have the same use cases as [tooltips]() but the distinct difference is that the content can be more complex than just text, such as media and other components.

To stand out from the main content popovers use the opposite surface colour. In the light theme the background is the dark card background and in the dark theme it is visa versa.

  
![Popover](https://studio-assets.supernova.io/design-systems/16150/342ed83b-0c53-46a3-ba3d-0501367503c9.png?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8zNDJlZDgzYi0wYzUzLTQ2YTMtYmEzZC0wNTAxMzY3NTAzYzkucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=OjQNYad8SGvYFCEZyXFME2B6JZt8ZjndgiR9DBGrzPWSh3nsZ3ubRjEfye2XYfr9DAHlKZIQhpdUR48dwtPIxzBiwaSosTEoM3MwJVvAHWTWPJ5FInjDumMsGHrrSFUynXnnSdi0mRRaNfRernw-2kskLnqFPR028YAMcBW~ikgkOj4BIV9UROKBQ~dyCiAqroSFh96grMfmb8hhMajNpCqu4HumCklNwjBYFac4l7NBn4itRtoXwwcZkGBV2gqHb5IF0TLByLL6Ej82bwKoE5VkMgW309FDElMMufeuIpgIbyymLXOWXSDvEAqrRpV7aSk9EwxzU3BFJxxe8MFxWA__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
Popover, L to R: Light theme and a dark theme popover  
  


Popover requires an icon button to trigger its display. The popover can be triggered by tapping or hovering events.

Popvers should have an inner padding of 16px to separate the content and outer edge. Images or other media can touch the edge if required.

### Orientation

  
![Orientations](https://studio-assets.supernova.io/design-systems/16150/da43bcd0-52f2-4293-ab72-eb3709c9311a.png?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9kYTQzYmNkMC01MmYyLTQyOTMtYWI3Mi1lYjM3MDljOTMxMWEucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=k4S47aJDr3dKTLh3Os0QL3f4FcmzeCvsv4rh20TBEtAkdmc9ch-X9xcsTZTYY~YJF-ruLU6fm3-OB5P4j1tOwzZInNIq8MB19852Y7ko7c7wH~S7F0apHSuBThRXX8VI72nC5unbOjI2XXH-fCxfRWpo3ObFuobjWtFHGG0XEP2tLCFXf~aMbeT~WKjh~tFi9f0WzfYDynXHTiUuR0qL5~T4lNp5j9ZGvkij0mj6xKw2H0t0qJIbCIDpCaPVjgljmj-H9rbpB09q-oQpuhkzT2Q3AqCSMrenMjfZCZsw4HBwMY5gq~JHb44~wlCigR32UalJWrA9Cpg8gbJHU7QSyQ__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
Orientations  


A popover can be placer around all four sized of the icon button depending on their usage in the overall UI. If the containing text greatly increases the height then the arrow indicator can move to an edge of a side as required.

  
![Edges](https://studio-assets.supernova.io/design-systems/16150/cf1a5284-bbb1-4731-a88c-121f87752087.png?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9jZjFhNTI4NC1iYmIxLTQ3MzEtYTg4Yy0xMjFmODc3NTIwODcucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=Nxq7bQeDlOkuO1yrcOHzymjvZLJ2TLNCFH6t0WavxKCqFa45QRyiqLcWFtr0TfKzT-Z4KryG00OyKsAlLRsBFwl-8LN3Vf6rigmOdZ-4Fs7lj60fW9XyabeVEaBVbxkaHfFVmCYkSnSLvCFq1tJWmIDuDmVUpm1rwKUtcUkzbLE3i1u60eQBBa7oPn3wqsD5dETLt-H5O89XJudnwLSUIVEPZJ35oOWSGl-Kp8hxn5i74cxoW05AUNII2UVAP18HsN1rNVVs9NTMmcemiwc77TkbvCpk~0XFJu0787npPyi5O8vF89eVM5PZh3-cjYG1Qo~LWhbWiMzkc2vwjQPW0w__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
Edges  


## File Links

  
[![Figma Components](https://studio-assets.supernova.io/design-systems/16150/4d4951d9-3bc1-4e73-ba89-61735aa2f28b.png?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC80ZDQ5NTFkOS0zYmMxLTRlNzMtYmE4OS02MTczNWFhMmYyOGIucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=mSls6wklZNibSPd7fGHLWGPK7aKHNYUBPNRT1PMa7MOjSYVGVfRIpXhO2qN3v8~Zc2XlBNtb-HwCOnERtefs9oSlsQWYg2W-~-JdeOqhY80UHrEouzb3BK7GkHSm6EU0BYT0zFwhWa-AXPb1RZmwFlf2s7f-rJM51OREM7FgcghsI03OvJSsXcsktnz6QoW6QTERi7Z2hNyc-UqtZ4GuVj8bzO4hBJAU8ZcXv0CBuNix4l6xLVZ~BcERRxOn7NqFP7Yfa58y3UCRHDAJ1PR1HbkO8tKAiBQPA1ZABGow1ciop~SMIpxZoiQpDtVb8Gn8TynQom4DDUlDnDvryg~GEQ__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)](https://www.figma.com/file/kwUvoAHziVnMYH97iJQzw3/Popover)  
Figma Components, Web/iOS and Android components  
  
