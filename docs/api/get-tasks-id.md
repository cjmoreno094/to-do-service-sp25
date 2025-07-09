# `GET` task ID

This call allows the user to retrieve the user ID.

## Request URL

To discover a user ID, complete the following steps:

**URL**: `{{base_url}}/tasks/{taskid}`

## Parameters

**cURL command**

```bash
cURL --location 'http://localhost:3000/id/2/`
```

**cURL Response**

```json
[
  {
    "superhero_name": "Cloak and Dagger"
    "healing_type": "Hit Scan (with Auto Aim), Area of Effect"
    "damage_type": "Hit Scan (with Auto Aim), Projectile"
    "difficulty": "3"
    "id": "2"
  }
]
```

