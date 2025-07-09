# Patch user by ID

Update specific fields of an existing user resource.

This endpoint allows partial updates — only the fields provided in the request body will be updated. All other user fields remain unchanged.

## URL

```shell

PATCH {server_url}/users/{id}
```

## Parameters

| Parameter name | Type | Description |
| -------------- | ------ | ------------ |
| `id` | number | The record ID of the user to update |

## Request headers

None

## Request body

{
        "last_name": "Smith",
        "first_name": "Ferdinand",
        "email": "f.smith@example.com"
}

## Return body

```js
[
    {
        "last_name": "Smith",
        "first_name": "Ferdinand",
        "email": "f.smith@example.com",
        "id": 1
    }
]
```

## Return status

| Status value | Return status | Description |
| ------------- | ----------- | ----------- |
| 200 | Success | Requested data returned successfully |
| 404 | Error | Specified user record not found |
|  ECONNREFUSED | N/A | Service is offline. Start the service and try again. |