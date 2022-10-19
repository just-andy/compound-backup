
# Progress Steps

---

# Progress Steps

This component indicates to the user how many steps there are in a flow. There are two variations of this component based on if there are more or less than five steps.

## Key Points

- Progress steps should sit at the top of page so it clearly indicates the stage of a flow

- There are two variations of this component; the usage is based on number of steps

- Each step has a different state; default, active and completed

## Usage

The progress stepper should sit at the top of the flow, between the breadcrumb and the page title.

### Steps 1 - 5

If there are less than five steps in the process use the `Progress Steps 1-5` component. These components make use of the additional space to include supporting labels.

Each step should have a clickable hit state, so the user can manually move through the flow.

Keep each label concise and related to the page title.

  
![Progress Steps 1 -5](https://studio-assets.supernova.io/design-systems/16150/a8d28e72-29a9-4294-9bc9-65c9b1a8f069.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9hOGQyOGU3Mi0yOWE5LTQyOTQtOWJjOS02NWM5YjFhOGYwNjkucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=hsBJ3Fanj3ejEoSygXV2jmMbdlbfCjuBqjA~R9os0EvD2NfT3JvktgJdFE6d3OIC-p69ImujDyLCqwS126FayxQocNjvrM3xy87bR0XQcJ6NCbwAQmgyZORVbw4nT18PyR9OSYO5YyIgvy5E-DeMIdu~cPTrnsh4Y3ma4ajphxr4Q1UeeclzGpJmmOWNTVpAqzdGX6cvwNol0gy9bjXVGu7NclF766OTzmqF2Tkpu8goPuunUVVW7PwpMZlITotKSlDA53vzyODTujnZzgWQUUEQQ32LXAayCYk-V5vAM~rERahAAv74lJfzWXh95U437oEjauPUBhcxAPLWZRFlkw__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
Progress Steps 1 -5, Example of a component for less than five steps.  
  


### Steps 5 or more

When there are more than five steps the display is more simplifed with each step being a small dash line, supporting labels are removed.

As these steps are more condensed the user cannot click on each step to use through the flow. An additional button group would be required in the flow to account for this.

  
![Progress Steps 5+](https://studio-assets.supernova.io/design-systems/16150/6d37bc05-f7eb-4e14-ba2b-6a97cf61eaa5.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC82ZDM3YmMwNS1mN2ViLTRlMTQtYmEyYi02YTk3Y2Y2MWVhYTUucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=ifAYJqYUF7og4fz46X~zoRSdGZjimCRVgW04AzMIxl5QemsEK87p6MQOpdGBMvTSm9B2yq9wpXgh02KENc8yymv4JaM~3gjUyV0f7Kx1gURf3T3AeQq4DCrw2jy8M8TNDZy62zX5nvZjJs7ae5qikmj5Fs-xQV~PRpfFZZV6bQf-TDVt3Ns7UKjNFUaeXtae8mZnGSII9rgk22JfC73QnwC8Gu9EakoOMMePM9ZJKUJsrsvHVx9kJVG836OM0VcP4yx4hIrtzJHZFJMUyc3n2iPXMiRbpQUHXSExyzX1yS9c86eMoxu5sTTa0SizjJ5veNyqKw~F0Su-KelqDsZlmg__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
Progress Steps 5+, Example of a seven step flow.  
  


### States

Both components use the same colours to indidate the state of the component.

  
![States](https://studio-assets.supernova.io/design-systems/16150/02da553f-d5fc-45bd-8d01-d54c672af1c9.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8wMmRhNTUzZi1kNWZjLTQ1YmQtOGQwMS1kNTRjNjcyYWYxYzkucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=HFjJUm-P9W1OJXFAEqTBYWFvw2BbxxL6iSRduoe3g7BCcowuki7HFSHbxJk4BvzBRiAKP2Os3nNl-BOIZZ7AQy09n0QooesJwjN4-yMjXOiK4PrNtJzLVufosBgay7hEkdZrb~nqgQxXledjY9awS-6gbELu6LWYRjeooI14WVVJXLdlLjVHOZn1n0VEgIMpRoELhzSk6ojesE5lqIWrGMbrGro2jP7lg-fPinhxMIO736ojo8mfcTUb28hyy7iTwPbKsMVkOw39942knpvvQfxGe4kStvMxCwlCDoKrQ6Ro9XwfQXFtaAgxtoqjqL9JsOHnmA72vNoNo3T0rbl-CA__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
States, L to R: Icons for each of the states   
  
