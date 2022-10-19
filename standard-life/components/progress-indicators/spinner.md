
# Spinner

---

# Spinners

Spinners are used to indicate when a process of an indeterminate length is still being processed. The use of animation indicates to the user that an action is still taking place.

## Key Points

- Only use if the wait time is expected to be longer than a second

- This component should be used on indeterminate processes, use a [progress bar]() for indeterminate processes

- The component should always use the theme highlight colour 

- Use the appropriate size of spinners and place them centrally in the middle of the containing area

## Usage

Spinners use their rotation animation as an indication that an indeterminate process is running, there is no supporting value. This provides the flexibility for the process duration to vary.

Spinners come in a range of sizes and the correct size should be used to support the context of the data.

![Img](https://studio-assets.supernova.io/design-systems/16150/13039fad-4838-4e19-9e28-38b588c4a8a7.jpg?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8xMzAzOWZhZC00ODM4LTRlMTktOWUyOC0zOGI1ODhjNGE4YTcuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=DVCIBJ2Lq5mn32uJleUqvt57TtQpEHdl2kSEs54HoeyjwjpHAlr~5KmghUaKUYEsD3CKnaAlxOYe-cx3MY1iNhdNwpN9I~eo6flTg6QqLw9kAAS~V4tM81HGE7~grmkXBM2XOGqnyU~vKkkBZ~R1GMYTrhjd5Y-0Mawqgp50ssVjih2uTUQLkTy5Wuz--3m8c0l~sQMajNN0DLvEnq9oDadDHStRRh5WhM~mZ-DwhuNBLtfWL0W-qK-YWU1lZwDZ5Ig7fOZvXCJ8lHUZM3SljmogdgTVVjyD4yM0FRZ31desnZXt3FznfOHjwju99p8O1-AYGL8kRyXS4ozIYx52bQ__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

Spinners should be located in the center of thair containing area. This demonstrates to the user the size of the area needed for the content being loaded.

![Img](https://studio-assets.supernova.io/design-systems/16150/5d14ea05-5890-4403-9f83-2ab431f3ed60.jpg?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC81ZDE0ZWEwNS01ODkwLTQ0MDMtOWY4My0yYWI0MzFmM2VkNjAuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=jDFaH~zt~9rYtHcn7Ei13LwxPHX86WBax7hBKvYXtw0mOvj7SlcHlO8FY0HCUQsOwCabCbLamcpkwFuj4fe9cWCGoqN7cz-Mm8p--BZIxXyNl5S4uDBvJK5JKKq0KlLvB1YsVxyJ9l~1g-jNyRO0n2bYoG8Bkg5S7fYonAGJviOetRrwpK4HVQnd4HWxMAlziETfkJnucuqt-xHcpcMqyF4f32IItxySx2mt6nsvGMqnVu799jTu3bHTzXs5wlh78GSBNcI8gEkw4SS8eCrL2GFbmgs7OzGjWlPXIPsveRPu5xxE4V7-oofFZwtvKzwLUKbU6jAhYZlGlAem-NGglA__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

Ideally there should only be one spinner per screen, however, this may not always be possible depending on processes being carried out.