# Search with date

**URL** : `/api/items/search`

**Method** : `POST`

**Auth required** : NO

**Data constraints**

```json
{
    "startDate": "[string date format <yyyy/mm/dd>]",
    "endDate": "[string date format <yyyy/mm/dd>]"
}
```

**Data example**

```json
{
    "startDate": "2021-02-18",
    "endDate": "2021-02-22"
}
```

## Success Response

**Code** : `200 OK`

**Content example**

```json
{
    "percentageLime": "18.52",
    "qtyLime": "80",
    "qtyNotLime": "352"
}
```
