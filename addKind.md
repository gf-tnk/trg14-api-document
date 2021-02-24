# AddKind

**URL** : `/api/items/kind`

**Method** : `POST`

**Auth required** : NO

**Data constraints**

```json
{
    "kind": "[string]",
    "qty": "[int]"
}
```

**Data example**

```json
{
    "kind": "lime",
    "qty": "99"
}
```

## Success Response

**Code** : `200 OK`

**Content example**

```json
{
  "message": "Create successfully"
}
```

## Error Response

**Condition** : If 'kind' and 'qty' is wrong.

**Code** : `400 BAD REQUEST`

**Content** :

```json
{
    "message": "Create failed"
}
```
