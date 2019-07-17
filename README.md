# JSAPI - JSON Simple API

## Success Response
```json
{
    "status": "success",
    "date": "2019-07-15T17:40:55.682+08:00",
    "data": {
        "users": [
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
    "status": "error",
    "date": "2019-07-15T17:40:55.682+08:00",
    "code": "ERR-500",
    "message": "Cannot establish the backside connection"
}
```

## Failed Response
```json
{
    "status": "failed",
    "date": "2019-07-15T17:40:55.682+08:00",
    "code": "RUL-001",
    "message": "The email column is invalid in format"
}
```

## Database
```json
{
    "status": "success"
    "date": "2019-07-15T17:40:55.682+08:00",
    "data": {
        "fields": [
            { "type": "String", "id": "name" },
            { "type": "String", "id": "department" },
            { "type": "String", "id": "post" }
        ],
        "records": [
            { "name": "Chris Wong", "department": "Marketing", "post": "Consultant" },
            { "name": "Tom Chu", "department": "Information Technology", "post": "Programmer" },
            { "name": "Jack Lau", "department": "Human Resources", "post": "Officer" }
        ]
     }
}
```
