# GetKind

**URL** : `/api/items/kind`

**Method** : `GET`

**Auth required** : NO

**Data**: `{}`

## Success Response

**Code** : `200 OK`

**Content example**

```json
[
    "apple",
    "banana",
    "lime",
    "orange",
    "papaya"
]
```

## Error Response

**Code** : `400 BAD REQUEST`

**Content** :

```json
{
    "message": "Not found"
}
```
