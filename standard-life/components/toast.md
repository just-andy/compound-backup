
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

![Img](https://studio-assets.supernova.io/design-systems/16150/4fa94308-4d2d-4436-9fa0-49bbac5147e4.jpg?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC80ZmE5NDMwOC00ZDJkLTQ0MzYtOWZhMC00OWJiYWM1MTQ3ZTQuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=Xb596IkX0sJ0xBtljKJhtrXF3AHbYdrZxnMqIJv8dm0yTKoJIuxO3SmVT~iGXBNSreyFyCsh4dX85ItF~z-NcG1R5~kEuNIWWx5~MIT9J85n8WRemOLJUHmuFC~E8eRqfF0S7-wFrnnuPXLGaGQyjgpacvGtIfjYAoPxOo4gsS3-kjGxEGKW8CvYnxUrZN87wFdEaZPdnZbF5VRuLr1TbWffamB-37vSYIFOfn5SY25STHwAmpiq3g0bWwNMnzxpBd9s93uEXWpfBN9nWlFI0JjHGaoIGxRNHeyt0vwEtnSnX2sJNTkflcwlsQLGoe3GvYM5iYFI~4Ol~bY9Pp2~tA__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

### Success

If a process has successfully been completed then the success variant should be used.

![Img](https://studio-assets.supernova.io/design-systems/16150/705fd48d-70c5-44e7-aa4e-2a4f8f775f78.jpg?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC83MDVmZDQ4ZC03MGM1LTQ0ZTctYWE0ZS0yYTRmOGY3NzVmNzguanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=id2SfpmPD2z-waaycyK9Cuk997qi5xQ5pE1cmOh8v0LUa9zjpH8spgCE2P6t2rAHVjSLJLaK96eaDURQzod1ZYtF5-AI8ms2fSWrDb3LHcWYMI8j7NTyYJj4R-wFO2xwpq4pF8MycupFeO0tb~RRdHs9hdGcC-5fy-HqzCRxpf3mHnPoMarBk96Dn1dAU7Zl62mXoHKq7DUw27rJoBLyeoe25bWCwqZrsEPwKxWVC5LpKX~H3K0le3Q3FmUb~Q6MhPF3-kD9uQBpkQ9~jQ7aRSqGEez1xrCc-3Si58ZR2PAyeFZ30MsM30PEhYtCrXWglE4joT89~FIZkWI94787PQ__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

## Error

If a process has failed then the error variant should be used. The label should indicate where the process has failed but not attempt to display multiple error messages.

This component could be used on [long forms]() where there is likely to be inline errors outside of the viewport.

![Img](https://studio-assets.supernova.io/design-systems/16150/f9c48915-14d7-4dcd-b4dd-1f40c7eaf78a.jpg?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9mOWM0ODkxNS0xNGQ3LTRkY2QtYjRkZC0xZjQwYzdlYWY3OGEuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=Z0QyCUy~VonVF1g2BXcyA0NRRQoh4F5GrgaoDBU29ukZYbIU~ad07H3SoMfK6KMw9vsIyU3BCO6JIErNuBaFjda44c78OSczvtVdk-0WG5CzEvGc2rqTFaVCMa5XFxdyH7P~qgMOP99jGGkUY4FnBbngA9YkLPrnaB6kg3FXEr6rfVN~uQJ1jFY6NGKkGu-55NhtWaCf9rj29lZLs9GhqrkiCvx4Jp~7rGM21WVaSvzp4JwM5c0FJdHAb-ozBpnjKXe9Y7n-jkNwoqUGTLY~UEh37om62rS347UsFHGdDdatf7S1N2JWdYVQShOJNeryfd-dJFya-1f1v1mMYCeYog__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

## Positioning

> Please note:  
> How toasts should be positioned across platforms and viewports has still to be agreed.

## File Links

  
[![Figma Components](https://studio-assets.supernova.io/design-systems/16150/e5997e9e-c604-40be-bb82-7ba8df459167.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9lNTk5N2U5ZS1jNjA0LTQwYmUtYmI4Mi03YmE4ZGY0NTkxNjcucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=HcW0o7YeGZIKDbqm~q7AJZfAYfOM5m1iHdA7OmZqryoDpve4Y3x5RgWGh6jhsL81KUaIteOWY7ptE~TjiT1YpqaYPYQPxbT3dpHr3qihwhqjRvXJjUpwCgpeeQ4Bp93HCzerQikTRaf7izqjOETfnfQCJl-UUilFBN4OhSdQgzWDHR~onxee7uc8FhmGRqMNi4OggSTM0WTSNUh2Gycf5jsKkkAWyU~jFE-zhALLPrBXDq8Rvd6J~XWnquxSdw6VAs9022qM7tCHpjw3aessrDy8etcl1iMt-Yl91ukhKIhQ85oQwPzy8H84x3MElk~csVZtd69lUXRtBphdY5j6qw__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)](https://www.figma.com/file/CK2yCzWcnw8Uns15A2OpTA/Toast)  
Figma Components, Toast components  
  
