
# Modals

---

## Key Points

- Modals* *should be used when the user is presented with information that is short, concise, and can be displayed inside a single dialog box or a height smaller than the viewport

- Modals block out the content on the [level below ]()with an overlay

- Modals are dismissed either using the close button or pressing the escape key

- On wider breakpoints the modal has a fixed max-width of 520px

- If you require custom content or the height is longer than the viewport, use an overlay dialogue

## Usage

  
![Modal Example](https://studio-assets.supernova.io/design-systems/16150/c3f8668b-46c1-4286-8516-b2c534a60d63.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9jM2Y4NjY4Yi00NmMxLTQyODYtODUxNi1iMmM1MzRhNjBkNjMucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=IsjkmSVqOVaFJg81RWjAMQywJ1hhMQowfqwGXgkTThiKJNL2hJcDDdma16AlQLvCOyVBhDSVLwYPWYCU1uY1LzYVsocAvtvH0LyB-07Y5tsnmJ-zcX0G0LvdlwVGTjl7wLPRwJ21rzfPbrSkzG0YA5DOAtHZ9yOS~rEOxf~tG8eByz02Rem-HRPMKKxobn2l3vwYykAhKtJZJCaSk6JJKRID4d~ecQ9wuQhzxQWUXkHyqxeB5XzWy1YkHkoIQGgESIi0X731IWRthjd3M8ga5zpGMCFkgT6pbpnUWKGQtpGcWKPlYjMpIBRSazzITEjyixR5z0-1HZVlhNQFwY2G4Q__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
Modal Example  


Modals are containers that have a title, text summary and button groups. They aim to block the users flow and present information or ask them to make a decision.

Although they can contain any content that uses these elements there are a number of patterns that have a common composition.

### Notifications

  
![Notifications](https://studio-assets.supernova.io/design-systems/16150/ec10d208-f53d-4745-a10a-e6b391439627.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9lYzEwZDIwOC1mNTNkLTQ3NDUtYTEwYS1lNmIzOTE0Mzk2MjcucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=UpMkLAndT5~xbJoKOP0nc1eQVflWkwCYSlMxhf4vUDiJ8CEDbwaa8pNqIPjSg4Cj2nhcannlv9X34dIJwQ3-Ehn~KijlHgsJ8q0NEDzLIQRcmGL91aZSAD356Z~MRPtjjg68HyRmwPL9Bsnz8u3fmdZIY~T9L5zEcUuf1bMuAwA9zW9lbON83QE~v6F5aEU~yeDIXOWKAYfAJBYqFnYIFvMuDmEl6e6xqwk95HdfEsde2HCv07e85w-batYwLm3esFYx28dBtyztCDVkuBJYMCWNm5NMgA2RjQML0pzlwk8vnoayLYYnktgT9cXmvIu8T0kZLftogznE5U7mFQTLXQ__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
Notifications  


The key element here is that there are no button groups. The user is presented with a message that they can dismiss.

### Decisions

  
![Decision](https://studio-assets.supernova.io/design-systems/16150/1ebb4f5f-1fa8-4ba1-8946-57c6f5716370.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8xZWJiNGY1Zi0xZmE4LTRiYTEtODk0Ni01N2M2ZjU3MTYzNzAucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=R~qOHcc4vXOStgj2kYllT1l1JGtnExdGu8d2zlSi0AonomyE2dxWJuhgNzAwmp1AMipaBm04BXV7eW~CMxlno6Z~hJOXOyYYJiJ2uupc9wDQ8plBRcQMcmf~NmzE58n5i2EhiqvVwOJCttGKZsxy2oe0Ee1SxdZZyX0OkOaWyDC6jTA1pfaYv4UEZueneJua5~tX58OgA88GRY~jkQsX2-tmYe53Zxy-SieJJHspywBwixZnU5LMmwOoC7lk4MyMxPAUYYyQNgKwvHzoKU1vqWAK4GlrQLvc17MJkCouLb4pv2iUWLzjjeGJxSrCpRNAeF2K5L09I43yEVBv2HGENQ__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
Decision  


Using a [button group pairing]() the user has to make a decision before they can dismiss. Any button group pairing could be used here.

### Confirm or Cancel

  
![Confirm or Cancel](https://studio-assets.supernova.io/design-systems/16150/e3660ab0-d03a-484b-8bea-dd2db9bc1480.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9lMzY2MGFiMC1kMDNhLTQ4NGItOGJlYS1kZDJkYjliYzE0ODAucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=fLT~7Uyg4OJiYEAOAaHmDM5dTgFo0vmFg8xIjOb2ZuG~GAdj6IWGg-4-7R9GDcd5Gx86aUUWXHpVvt8qBnvFX5d-09BNRSQtkDIXZQ0l3-raNMXNFZFqVHUEzm99VI6wrEsSUJSw1-kTS1MnlO3BUCjjzFQ0HFCoBXDIUqKopkzCZrLlTqUndrQ9E6pUtnVbrFGJRQE9PEUFhBoNKbtvT40MdmJ94TKBcAsV4pJV7FdTVBY2MpD34bqk2EylejdN5CXuafN~hTfslun-yYgtHoRbh91EQrywccXSTSoqwaSiFgMRTRtbNLjsz7pmNBRiiy9If07xX2LeGtBYbewYLw__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
Confirm or Cancel  


Unlike the decision example the user can opt to do nothing and they are presented with a close icon alongside a cancel button.