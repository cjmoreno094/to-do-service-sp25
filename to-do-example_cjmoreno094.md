# Code examples

**Author:** Cameron Moreno

## cURL example

This cURL command will bring up the 4th user.

### cURL command

```shell
curl http://localhost:3000/users/4
```

### cURL response

```shell
{
  "last_name": "Bailey",
  "first_name": "Bill",
  "email": "b.bailey@example.com",
  "id": 4
}
```

## Postman example

This Postman request shows the same example (4) using Postman as the test.

### Request

**Method**:

```shell
curl -d "last_nameBailey&first_name=Bill&email=b.bailey@example.com"-X POST http:/localhost:3000/users
```

### Postman response

```shell
{
  "last_nameBailey": "",
  "first_name": "Bill",
  "email": "b.bailey@example.com",
  "id": 5
}
```
