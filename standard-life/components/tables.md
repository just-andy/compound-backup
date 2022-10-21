
# Tables

Our simple table components are specifically designed for static content which is best displayed in a table.

---

## Key Points

- These tables are not data grids, they only present static content

- The table headers have an optional icon button

- Cell content is left aligned for text and right aligned for numbers

## Usage

Tables are used to present tabular data in rows and columns. Each column has a header and the cells below display related content.

These tables are design for simple static content, not as a data grids. This means that the content is not sortable or filterable.

### Stacked Table

Our current implimentation of tables is based on our responsive guidelines. On smaller viewports each column is stacked as a collection of cards.

  
![Small Table](https://studio-assets.supernova.io/design-systems/16150/db36febc-d09a-4513-8fc1-05d87d5c76cc.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9kYjM2ZmViYy1kMDlhLTQ1MTMtOGZjMS0wNWQ4N2Q1Yzc2Y2MucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=gUpJeWa49hm9xFiaiuZ6dxeQQMCBVJc3MdxNhsTB0iFuL03zBnTPmsUl6gk1zLgMBGVnOC3qimcz-~29d~jhDvamkRopu~z2LP-LiUsH~AsRWTU7U4jXW67TWXeH7wOZoMnZVg4ovUpy~gza0AWAkep2iYHZgpYE~THORbetxcDQj2Z40AsQ5xXBBO7nWc1-fmbFfwZ5Njtwbpox3E5UBHC9JlqRcM4DbN4mPVs32rTPl1r4A7eg3zcyvpQtdEBLFVlD9BGgoksdLD8LHC8IaasKV9dYARpYGwmqBBUhkBXiYYuonKU1k06mRVWRpLEH85K1weUgNXhC0m4UWCuvzQ__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
Small Table, Example of the table stacked on smaller viewports  
  


On wider breakpoints each column is shown in a more familiar horizontal orientation.

  
![Large Table](https://studio-assets.supernova.io/design-systems/16150/63db717e-5239-4e66-af12-29160bd5e568.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC82M2RiNzE3ZS01MjM5LTRlNjYtYWYxMi0yOTE2MGJkNWU1NjgucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=czgKDxwgnW46vJjV8syRsEXBG-rT1L9fNteDUZNeOBIDD6Y3li8hFFNWjkaiYM4Gnq-76MShi0VQ~XYyIJ~r1gBy2~pk9kJkTW8yt4cVHZC9hmsBX85QHXCY~XcVZuU6-sYO6HLTBD1-HhAE5QjIo4LeNmqodC2la55IHNt6V0Fr~MRwmrIGAL7eDweNxWAZXtyrvvZ8Y5etCIEya06F19AAWBpBcC9PRkP-G5PDusgSUHSdAyaSSQN-eNkwH-8sRyquaLG7yS501lC-Hldr7ASYq6VTSIIXv00Kv5tEsLC1LzYFAM30~dLAVu-A-N9spfXqIVonIq3~Nw2QiNmpUQ__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
Large Table, Example of the table at the largest breakpoint  
  


## Elements

### Headers

Headers as you see from the layouts above can be used as the title of a column or cell. These cells are shaded to show the difference and also include an optional icon. 

Additionally, there is an optional icon button to the right. By default this defaults to an information icon but can be changed.

*Do not use* this button for sorting, as this is not a data grid component.

  
![Cell Headers](https://studio-assets.supernova.io/design-systems/16150/7eefc693-03cc-408a-8ac0-4617e9ee1fbe.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC83ZWVmYzY5My0wM2NjLTQwOGEtOGFjMC00NjE3ZTllZTFmYmUucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=btDelKr5Wak64DvqzGQ3W1GNlw1yKaRVrQMRv2Wj8~hR~m4CY4y7vskCLSrauqzlFcYOlwkaAQlPk7-h3Y7NbyWfaYMqcv4L9pXpCqUmFOuQxkEaFX3pmwCrOQpootGchGoXslBTwWEdIi0ZTXFA7uwZK1bzNd-7dowK1uRl84283bN1og9PTz6OSbWKLpO68-j8quH4p4fOci6iZ7yvgSxWpyuewB2Wtrt4J49nkFh8S5KaLqA5SDcPoaEv-txm44GSof~36stz078eL7jTFfPHpVsURcfp6A351QhH3O1Pxp7I7Hmo0oNhliYxVTYkALwoyHNL67A7xXlHPZqjgA__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
Cell Headers, Examples of the optional headers  
  


### Cells

Table cells have two variants; text and numerical. The text cells include an optional icon and the numerical cells are right aligned like a traditional spreadsheet.

  
![Table Cells](https://studio-assets.supernova.io/design-systems/16150/5e64c492-ec69-42cc-a347-d39abf020911.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC81ZTY0YzQ5Mi1lYzY5LTQyY2MtYTM0Ny1kMzlhYmYwMjA5MTEucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=RXzbnQhG3bcuGzuFl0f1tBlnCdrKgB96GdzfhBBULZC5Qcc6WKskv2rKepJx8QQ1HB~R8ggV9D~VGup1qqEVLPTn~az4w8jo61Ry9UeopZW5UBT1BCJ9vOQzQkapIiVQR97v4qEyL~FZfEqlD~TT9iYdDvt8VSfs6LykDd5iA6UQLH2nXK0oA7fAi9VRsydO547QLZhSP2y4iYldb4uq~6uTBMN5tMWXIyVO9LThWg6WLuiS2kL1aUR9374-vq9tLvLvCrkxcA1HQyZ5g0N2wIVfkyjOHwfMjU8m4FAsK8HVwWvOf2nKKJd2gHWF-Np6DEpQcVo9cCFo8xf09nCk6w__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)  
Table Cells, L to R: Text with an icon, text and numerical  
  


## Native Specific

There are currently no table components for the [Ionic Framework](https://ionicframework.com/) but they can be created using various other elements.

## File Links

  
[![Figma Components](https://studio-assets.supernova.io/design-systems/16150/a23d4acd-29c7-47f5-87a2-d04312e9408b.png?Expires=1980201600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdHVkaW8tYXNzZXRzLnN1cGVybm92YS5pby9kZXNpZ24tc3lzdGVtcy8xNjE1MC9hMjNkNGFjZC0yOWM3LTQ3ZjUtODdhMi1kMDQzMTJlOTQwOGIucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxOTgwMjAxNjAwfX19XX0_&Signature=J9FALmq25R3SdFi5mTG6MmIw9N1bhyk3~hp8hdYd50H6xDaslwWWcFNhHi7z4I6XLBuks1trb6zKMXiLeSr8clak27X-7tao0-iFYXhClUg30erhWW3bRVgHgwKj7oqhxv20wOD8vmCzZ9UvtOCXrJgvTv06UaiXnvnjwpB2VHD-eSPuqedTp7bh0UXA08qV-IXWlySSlfkKvEbxtrPx7h3Ii~bRMxPX5DO3iEaxOW7NWpMzRrtVJnf-f2w6bqIl2pDcDhJdpnSwPmW~A9OpEKI5nhZruAFlnEgQoehM0dg2opRpH3VpNT71ujzfem3rL-9iJTe3DWFjCdWfocgW7A__&Key-Pair-Id=APKAJGK34LCCAUR7N6LA)](https://www.figma.com/file/gsdAkfGKQFbUp4hL4Gi1P2/Tables)  
Figma Components, Table elements and compositions  
  
