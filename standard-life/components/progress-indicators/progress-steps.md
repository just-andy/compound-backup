
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

  
![Progress Steps 1 -5](https://studio-assets.supernova.io/design-systems/16150/57acebd1-8422-452e-a961-0c7cfc55b81e.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC81N2FjZWJkMS04NDIyLTQ1MmUtYTk2MS0wYzdjZmM1NWI4MWUucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=eexpuU~mA7vzyXYksoqByVdYuPBi~rz50RrHc0VXUFmz8SOuHJ3sn1R1FlGu7I7l~7u8I~XIz5hqLMcLfmRFyWvZfy~348aNIUiAkOxDVA5bcwg5koBR4-69o9tp774nOP~D1oEd-nwK9ZiIajQeXaNPD0DUZAvzwQTsXFoHjN~yh8h2Q4hHmZNNDaDB1V6jTNFRKDKh0dDRPz12syXr3LBCgwSxs9UW97PP~l2ebyNz0gfPimVouEhSOz0Z4a8yWLC4adgNzGdW~0CzAfl6wZZdJksuLQqDrpOeaTfuHQ5Z4rFGX3awHaDKyz2ZtNFMl6WQN7YULjaX3LsOLcxQLw__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
Progress Steps 1 -5, Example of a component for less than five steps.  
  


### Steps 5 or more

When there are more than five steps the display is more simplifed with each step being a small dash line, supporting labels are removed.

As these steps are more condensed the user cannot click on each step to use through the flow. An additional button group would be required in the flow to account for this.

  
![Progress Steps 5+](https://studio-assets.supernova.io/design-systems/16150/89a15415-330e-4cbe-8351-153c86109e3e.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC84OWExNTQxNS0zMzBlLTRjYmUtODM1MS0xNTNjODYxMDllM2UucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=LHk8Ni8A-k7PLETCTEB9iwDXGhVmzimhrFzT4FvjSoXg5sxLk1wfW3uLwdibIcR1E9LPqKaOP1DjS3Iwt8LbQu~pmEbxWPzXGzucRgyDCCh0dl1b2uqeAgWAVgldFFYj2psA2tRAxLC~gAUiqM75AgZjGY7drPX6WNKi7D0vlszxeAmavYTqKs8fbD0No-PJUtjYDL7b-3VEG9ZlubVQ2RkkiZG6tyoo1Ep2LgSlEvs3uJyOUSjBCrOv124Laax~fjp8jvoAzv-jx5TkJQwkK7U04vz3QKNlNW6wkZyxEDR3sb4zAuwMIfZBTxTunP~~IUNVhsaXfQGeW~p7aMFiaw__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
Progress Steps 5+, Example of a seven step flow.  
  


### States

Both components use the same colours to indidate the state of the component.

  
![States](https://studio-assets.supernova.io/design-systems/16150/5962695e-dd39-46b9-92d3-62b83ff98311.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC81OTYyNjk1ZS1kZDM5LTQ2YjktOTJkMy02MmI4M2ZmOTgzMTEucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=JhXCs7x-2dML95IO9FpKnzpa-gnw2TzDWjT78aKnigxjiRmEZovM5jvR~6vuq-s4G62UA7dfiT8hG7STFJuPtxZrGg3wIA3o8awY2imvsgAxv5eD77dEggi0bd--0A6L41GNf7oQAem1gXffXWgzBZGAD7MHCVoK-~RqUEWNeYur7NOHMSy1pcMGRVgMsaeTCDfwaseaaW-7glcff4UywlMlN2IIn82MM4y6NOXhmG65Sq2SOyd-G5nm7ecOIL3FZlTZ5I8~iRIg0E9iRWlYVda9Ze99lhqtiJMHy0fbZwOGSm12hUyYzCHpzJbe8Rn-0-sfHIxTShKjlMCoppP12g__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
States, L to R: Icons for each of the states   
  
