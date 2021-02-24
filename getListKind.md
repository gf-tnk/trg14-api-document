# GetListKind

**URL** : `/api/items/list/:kind`
**URL Parameters** : `kind=[string]` where `kind` is the kind of the items on the items table

**Method** : `GET`

**Auth required** : NO

**Data**: `{}`

## Success Response

**Code** : `200 OK`

**Content example**

```json
[
    {
        "id": 104,
        "found": "lime",
        "qty": 15,
        "created_at": "2021-02-24T03:23:16.000000Z",
        "updated_at": "2021-02-24T03:23:16.000000Z"
    },
    {
        "id": 71,
        "found": "lime",
        "qty": 1,
        "created_at": "2021-02-22T12:40:11.000000Z",
        "updated_at": "2021-02-23T14:28:37.000000Z"
    },
    {
        "id": 70,
        "found": "lime",
        "qty": 9,
        "created_at": "2021-02-22T07:34:01.000000Z",
        "updated_at": "2021-02-23T14:28:37.000000Z"
    },
    {
        "id": 38,
        "found": "lime",
        "qty": 6,
        "created_at": "2021-02-22T05:19:39.000000Z",
        "updated_at": "2021-02-23T14:28:37.000000Z"
    },
    {
        "id": 89,
        "found": "lime",
        "qty": 4,
        "created_at": "2021-02-21T17:30:01.000000Z",
        "updated_at": "2021-02-23T14:28:37.000000Z"
    },
    {
        "id": 65,
        "found": "lime",
        "qty": 5,
        "created_at": "2021-02-21T10:15:01.000000Z",
        "updated_at": "2021-02-23T14:28:37.000000Z"
    },
    {
        "id": 101,
        "found": "lime",
        "qty": 2,
        "created_at": "2021-02-21T07:28:59.000000Z",
        "updated_at": "2021-02-23T14:28:37.000000Z"
    },
    {
        "id": 18,
        "found": "lime",
        "qty": 10,
        "created_at": "2021-02-21T05:16:55.000000Z",
        "updated_at": "2021-02-23T14:28:37.000000Z"
    },
    {
        "id": 11,
        "found": "lime",
        "qty": 9,
        "created_at": "2021-02-20T15:38:54.000000Z",
        "updated_at": "2021-02-23T14:28:37.000000Z"
    },
    {
        "id": 57,
        "found": "lime",
        "qty": 3,
        "created_at": "2021-02-20T10:49:23.000000Z",
        "updated_at": "2021-02-23T14:28:37.000000Z"
    },
    {
        "id": 88,
        "found": "lime",
        "qty": 5,
        "created_at": "2021-02-20T06:19:20.000000Z",
        "updated_at": "2021-02-23T14:28:37.000000Z"
    },
    {
        "id": 66,
        "found": "lime",
        "qty": 5,
        "created_at": "2021-02-19T23:17:21.000000Z",
        "updated_at": "2021-02-23T14:28:37.000000Z"
    },
    {
        "id": 46,
        "found": "lime",
        "qty": 8,
        "created_at": "2021-02-19T23:13:42.000000Z",
        "updated_at": "2021-02-23T14:28:37.000000Z"
    },
    {
        "id": 9,
        "found": "lime",
        "qty": 9,
        "created_at": "2021-02-19T23:11:49.000000Z",
        "updated_at": "2021-02-23T14:28:37.000000Z"
    },
    {
        "id": 41,
        "found": "lime",
        "qty": 1,
        "created_at": "2021-02-19T21:53:01.000000Z",
        "updated_at": "2021-02-23T14:28:37.000000Z"
    },
    {
        "id": 10,
        "found": "lime",
        "qty": 8,
        "created_at": "2021-02-19T03:27:44.000000Z",
        "updated_at": "2021-02-23T14:28:37.000000Z"
    },
    {
        "id": 75,
        "found": "lime",
        "qty": 10,
        "created_at": "2021-02-18T08:10:07.000000Z",
        "updated_at": "2021-02-23T14:28:37.000000Z"
    },
    {
        "id": 3,
        "found": "lime",
        "qty": 1,
        "created_at": "2021-02-18T03:44:39.000000Z",
        "updated_at": "2021-02-23T14:28:37.000000Z"
    },
    {
        "id": 35,
        "found": "lime",
        "qty": 8,
        "created_at": "2021-02-17T19:52:33.000000Z",
        "updated_at": "2021-02-23T14:28:37.000000Z"
    },
    {
        "id": 63,
        "found": "lime",
        "qty": 3,
        "created_at": "2021-02-17T16:23:58.000000Z",
        "updated_at": "2021-02-23T14:28:37.000000Z"
    },
    {
        "id": 33,
        "found": "lime",
        "qty": 10,
        "created_at": "2021-02-17T14:22:06.000000Z",
        "updated_at": "2021-02-23T14:28:37.000000Z"
    }
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
