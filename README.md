# JSAPI - JSON Simple API

## Success Response
```json
{
    "status" : "success",
    "date": "2019-07-08T02:28:17.081Z",
    "data": {
        "users" : [
            { "id": 1, "name": "Jane Doe", "group": 1 },
            { "id": 2, "name": "John Doe", "group": 2 }
        ],
        "groups": [
            { "id": 1, "name": "Administrator" },
            { "id": 2, "name": "User" }
        ]
     }
}
```

## Error Response
```json
{
    "status" : "error",
    "date": "2019-07-08T02:28:17.081Z",
    "code": "ERR-500",
    "message": "Cannot establish the backside connection"
    "
}
```

## Failed Response
```json
{
    "status" : "failed",
    "date": "2019-07-08T02:28:17.081Z",
    "code": "RUL-001",
    "message": "The email column is invalid in format"
}
```
