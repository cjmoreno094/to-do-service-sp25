# Code examples

**Author:** Arielle Ang

## cURL example

**GET** example in cURL to retrieve the details of a specific user from the to-do service repo using the user ID.

### cURL command

```shell
curl http://localhost:3000/users/2
```

### cURL response

```shell
{
  "last_name": "Jones",
  "first_name": "Jill",
  "email": "j.jones@example.com",
  "id": 2
}
```

## Postman example

**GET** example in Postman to retrieve the details of a specific task from the to-do service repo using the task ID.

> **Base URL:** http://localhost:3000

### Request

**Method**:

```shell
{base_url}/tasks/3
```

### Postman response

```shell
{
    "user_id": 2,
    "title": "Oil change",
    "description": "5K auto service",
    "due_date": "2025-03-10T09:00",
    "warning": "-60",
    "id": 3
}
```
