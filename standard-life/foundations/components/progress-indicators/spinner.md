
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

![Img](https://studio-assets.supernova.io/design-systems/16150/13039fad-4838-4e19-9e28-38b588c4a8a7.jpg?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8xMzAzOWZhZC00ODM4LTRlMTktOWUyOC0zOGI1ODhjNGE4YTcuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=cqrO7bMHPgQR21a51slQ1FpnHi4o88jT3cZtgM-WWwRmvAZ0kYr1MF4liHiOgAOF2xuqpNaDana2~YBIfeXaW2x2XQ-W2DU~N4PXdkrwP0m1ISeu-HPdOc4BM5tEt2yG8A9yVnaArHOBbl~jTNObG1XsDmIxdQuOIJPP-Vdk66~EXl4AmgNs~VxMeqTNeXXfSO8vOpwR8gFcYuWhI~k27u5Gvqm11S9cTDbZaK-33Td5OD9JSA7zrJv0Iy4BBpd4v-my~KN0d1S91ThutBkwxKsF2z70WHXQg8gNFfGKfcgGCBvKTx5K3-Vs8XBRv6SLYup~0zEt~uiRMP002~bIAw__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

Spinners should be located in the center of thair containing area. This demonstrates to the user the size of the area needed for the content being loaded.

![Img](https://studio-assets.supernova.io/design-systems/16150/5d14ea05-5890-4403-9f83-2ab431f3ed60.jpg?Expires=1977609600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC81ZDE0ZWEwNS01ODkwLTQ0MDMtOWY4My0yYWI0MzFmM2VkNjAuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTc3NjA5NjAwfX19XX0_&Signature=ISSAr6rGrT3T0kjMb13bg7xzYaYlrHiS00HmiYNpl8G8cJBtmndvb8hX76MbB9IjKEXiOm-O~YNtx-kkeZwK5iR4F~Igv9~C7VNNur0v7Fn-WUUF84YF1~tDWBBf2mdudy0hiQn6qSish57jfAtvUxiscqOGUZqpxDG2eox3jRJwEmU8Vx27KE4CVtL5CRRXPd6V52tGeJUvOzhjyDs~4w~2ySaJbKszL5OYtF-jfw-dqPnGXLEGf-5iKDfUFKD0bmHeolGgHdILcUbvFQp2CxYigVR22U6x-TdzMqzSiKH0CCAetbIQ1s2HsFTkoXgcx7i4bCBeGOiIOCSxXgIBNA__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

Ideally there should only be one spinner per screen, however, this may not always be possible depending on processes being carried out.