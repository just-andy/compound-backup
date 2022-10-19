
# Lists

Lists display a number of related items together as a collection. There are several list variants all with specific styles.

---

## Key Points

- The same list item should be used throughout a collection

- Lists have a specific heading component to be used

- Label text should wrap on to a new line if there is not enough space, it should not truncate

- Lists are available in the theme default and inverted colours schemes

## Usage

There are a number of different list styles and each is grouped by its use case. What is consistent across all of these is that each collection should use the same properties. These properties will vary based on the list component used and each can be activated/deactivated as required.

### Filters

List items containing checkboxes and radio button list items are most commonly used to present a range of options in a collection. 

The *whole list item is a hit state* and would activate the selected state of the radio and checkbox.

Just like the form elements [radio buttons]() are suited to single selections and [checkboxes]() multiple selections.

![Img](https://studio-assets.supernova.io/design-systems/16150/897eae52-b925-471c-b0a0-ca00419801f7.jpg?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC84OTdlYWU1Mi1iOTI1LTQ3MWMtYjBhMC1jYTAwNDE5ODAxZjcuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=YUDv19M402STiHRL99O2FwNq3UQEhy~1-qS5ES4awdfUI~J4L206ZW3kdaZEQaGJz2BglGgqUU9-XezXTvXIBcHTGLswL7wWskT-E~9uK5AynldB2jYziRgnsr8uFpFXs5iRbgsuKJiM81kaas~DGHBQhHIBeUZcgoY2Jj2AuqvJf3QkGMVE4adMVo2vQho1RfE2mGWR5iuOUbtjawVKdIodA-5RDCbCTYNDrz~M5UZwstf6wzwwzjxFUWJfVE78qugj5AL8C9qnXMmvdtANc6wGzYTenb0hVfkcyi89Fs8-nNvzj2XvEH491LSnWdx2--SSDCpfwn-9lSA1NGDD1g__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

### Navigational

Defined by the caret right icon these list items should be used when the component takes the user to a new page or point in the hierarchy.

Icons, subtitle and badges are all optional properties.

![Img](https://studio-assets.supernova.io/design-systems/16150/cabe3ddf-2637-4ec5-8965-f596683d50c4.jpg?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9jYWJlM2RkZi0yNjM3LTRlYzUtODk2NS1mNTk2NjgzZDUwYzQuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=l5n9uYhQZXxL8kl0c5maXZ31sjZS5fsSRprSSK~EMeOWMxjeCHpP2LZ5hAIvleHRf-8uEqwkOGwg8UbMdVgNajkk~oe4RIJJqc2d2joMlL7VwdEhb0gnuAltg00ABMP6U46qMtqMt6jWtXBQ2icGAimQMqiGN8yjOpQx6MH7i5jHv1OKgnkStvqmNLsjdOGGhXd87HceWSHX-e3CkPKH6HY52sWMDNDxBeBlPjGXwfQ841UHU65qCw2BSJOELgUfhXw-WbJ8lIFW2oA4mQDL2mHx2fhNaYoekHkvOsJNXVKfWmU2Sf0VVrbX7v03-LBojhvgm9Zps4fzV6qMxo1rFA__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

### Content

These should be specifically used for long body text items where styled lists are required, they do not replace bullet points or numbered lists.

The specifc lists are:

- *Progress Lists* - Used to show a customer's state in a process. For example, to set the expectation in the beginning of a journey or to explain what’s next when they complete a form.

- *Links* - Required when a link needs a supporting icon

- *Lists with an icon* - Can be configured to have icons, label and sub label.


Progress lists and lists with an icon should not be used for navigation, they are for static content only.

Progress lists use related to [progress steps]() and use the same styles to convey the user is working through a process.

![Img](https://studio-assets.supernova.io/design-systems/16150/52260882-fa97-4c3e-83d1-623bf5cf6037.jpg?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC81MjI2MDg4Mi1mYTk3LTRjM2UtODNkMS02MjNiZjVjZjYwMzcuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=XQAkbpXy2tiPJQ6hhhwUIYfA4i8tXCGuVcflCglX6y-zLvXgmx5WIsBtdGcTZCSUkq~2YEo4qHpqxYKaSBbbibPrxZ7pELm4m1fOFM4wxvLGN5icbvsrkYMiFDcDPSAouoMnYyIgrBorKpNq3P6EOke~z8bvx2-L9fd2B9t6j7HvsDTg91gwME6brj3zeS~hMWnX5LmsCy~VzuCv0diqVVEj2PTtfFzzTSAG~o~hnNjg4624Zk2eCS6IvNec72E4lpDRSbGjzKzRVInpqsTjr~9UYqoGwqSDuz6bgk65Azr5AWXc5-wz6efRlQzwDaDXdqnWuAsG2GUaiSg5l9cNwg__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

*Checklists*

Checklists are a specific type of list with an icon. They are used to indicate when something is included or highlight a benefit.
The check icon should always be used with the success colour for this type of list item. Do not use the same styles as the progress list.

> Some extra info:  
> In Figma change the icon colour to success (GR 70) and use the check icon.

![Img](https://studio-assets.supernova.io/design-systems/16150/a75bce25-ab2a-4a4c-bc0c-c1f62da55ff7.jpg?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9hNzViY2UyNS1hYjJhLTRhNGMtYmMwYy1jMWY2MmRhNTVmZjcuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=IvouZxgHXmmTnkBQ3Jy9GuZP2pGYKObVOGj0neDfG9yoIt-~4KjItlYC4UwQHSoFBat-F2qgCLgprv7XQuRW0KXE~VdjFmXzXS07iOHza-ZsK-1VoidTZ3PSK-YgVwDbUO2umDHGu9j1qBQeDeCSf0hsqht2xpKY98djmSoT2B~PzepOT0YMCdsodOHNQiBoW6zyM1UHa5~f-mZIZ998MYalsNzuUOVcwdjleKWWZ9B91~TqLJJL5WLW3mXWCFfoUfxq~hCzJ~u68JNBELoKOTVmYLscMfmNz2-j9CAJ7IrNQQNVaZBjZ0AecV11Kuyhp9pywrWtsj~I2Dt4STnSuA__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

## Nested Lists

The standard component items have a 16px space on the left, however in some situations where nests are listed the spacing should be removed for alignment, see below.

> Some extra info:  
> The Figma component does not have the padding as a component property, but the adjustment can be achieved by changing the left padding from 16px to 0px. 

![Img](https://studio-assets.supernova.io/design-systems/16150/1f72905c-8460-40b1-8ebc-58931a2e338f.jpg?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC8xZjcyOTA1Yy04NDYwLTQwYjEtOGViYy01ODkzMWEyZTMzOGYuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=ShuhIOiHd-lcH9~~htzBm0k952ZV92zKdYpB60NNwhHJlL214xPbaOnNvkqmwnv5GpBoNe2fLATCzbsoGksaT9uLF5KGhJzPZelmWqkYBMjLSKggMW2hJ1NOmOi9FSvaActhUm~-tjYKQFQij91gwECm8HmxCeMCAS0UPvP45tZUGZ7jv8Rggcy2v7cKtW~xb77k1VphtAOYIvQnzLnw6zpwupH4YqFagoC~M3YVb~D3cVqKd1vSo4GnzDG6lTuWI7W8euoMqjBtTV9ei6z2qtnXSVtFMLU7jTpISKPgw8U8eUObCZWgOB0GR8dwTLJqlalb5NdKKqB72rcLUeClmA__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

## Native Specific Variations

The radio and checkbox list items on the native platform are right aligned to meet the platform standards. They also do not contain the badge property.

![Img](https://studio-assets.supernova.io/design-systems/16150/73dfdea8-f37e-4c6c-8a6e-3b1c287ac084.jpg?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC83M2RmZGVhOC1mMzdlLTRjNmMtOGE2ZS0zYjFjMjg3YWMwODQuanBnIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=KBFLtE0Eh60BBR2j5l7yZ4p4L4Fu3YF3BeHdmVD9ycB0OYUYl48~7vU5ZkUYCi3zSKu0hTDcMSDd19grMkRPJvmENz8RDu9hoNUeHhUS0Qyf3v4evbxt6L60kv2sRgiTtE5-NmH0dmYQ22BbjQ5wnw~qVDw6CfSbz8taNpEUnVNWEsTXEeqL4DZqf~TBLF9xzA3TxA6OF1V~~E7LtvISntRlNkBn771~3PplXbql2-M~5NGz3AFa~NLJDUEtJ1u369RDBvKP1idkltSFNRPk71Rb5c5WoqBDPX7c-mCMguDn82uq5T9t7HdopO8T~3qd4We6Ga6M9cGYkAUry-QoGw__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)

## File Links

  
[![Figma Components](https://studio-assets.supernova.io/design-systems/16150/5798a4fb-3f5e-4ebb-ba5f-5d1942039ebc.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC81Nzk4YTRmYi0zZjVlLTRlYmItYmE1Zi01ZDE5NDIwMzllYmMucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=eMtm0v4Zp5HWYs9TSXuIf5UQHWv2oziMdxnA0LMXK4QC8acaf7qUTfWK4N7XDxkwToolMA9B2WG-tLPcbJmtiyPjSMwsh2OMemg~kwWjTMv~65lArqTc2ERqyc5oo3PEyWh68HbvYGD7sF-uzEzODcBeuWy8vAQY9yeeJnHaY7Igphl5rhnmjgeBDuUSogpsbdpqRTEXZfOqZUyrdtjJLbYyaluFO~h0DT5dsdoCrQUAe~rSNOobdsIdBLevDvtsnSVqbc7nRb8Aj6umVgnfflUMx8jvR-5gJlh7EdZxsKd~gtlD0SOS1FG8-pOSH9yahnkTvcZOjfzy7qggXlnYTg__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)](https://www.figma.com/file/KOt8FBbh4kFm143F36tpXT/Lists)  
Figma Components, List item components  
  
[![Annotations](https://studio-assets.supernova.io/design-systems/16150/65b5ed16-5946-41fd-baf9-21e2173ef9fb.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC82NWI1ZWQxNi01OTQ2LTQxZmQtYmFmOS0yMWUyMTczZWY5ZmIucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=EpHc-QnufRJFQPyA1JmvsoqxPi4rWf3nnPj8UGaQnk4HqLXQXoYctcrsl-I85quqp9DoQRAmKVl-4m0BgrH~o6HeJC2jD1wAs6BGPlsN0dvDn5Eeog7af96xGTJnruKFYVnyd6P-ZkZ5I1YANgeEMP5VxJu-oCU2Yq55~xqi78YlSC9-CqlKqBiaLx~y~enUwVu3EG53N3PSZA8wbOPA1bmiPsbh0UDbzYo6nm6zKtz24yY-G14elsJkWfDYcTX~Ju8kR0rZ1TOT2gxdcfNIW~1HvDJBn5wvhs8PV2EepgBmjGDqd0oFm2mQgawXQWzLLsv0Bi8yI--7iJII6iNKUw__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)](https://www.figma.com/file/nnHlTllfLFwl6yqjLvcMl6/Lists)  
Annotations, List Annotation Files  
  
