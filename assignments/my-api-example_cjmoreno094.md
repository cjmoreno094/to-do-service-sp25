# Code examples

### cURL command

```shell
curl http://localhost:3000/strategists
```

### cURL response

```shell
{
    "superhero_name": "Cloak and Dagger",
    "healing_type": "Hit Scan (with Auto Aim), Area of Effect",
    "damage_type": "Hit Scan (with Auto Aim), Projectile",
    "difficulty": "3",
    "id": 1
  },
  {
    "superhero_name": "Invisible Woman",
    "healing_type": "Projectile",
    "damage_type": "Projectile",
    "difficulty": "4",
    "id": 2
  },
  {
    "superhero_name": "Luna Snow",
    "healing_type": "Hit Scan, Healing Over Time",
    "damage_type": "Hit Scan, Projectile",
    "difficulty": "4",
    "id": 3
  },
  {
    "superhero_name": "Jeff the Landshark",
    "healing type": "Projectile, Area of Effect",
    "damage_type": "Hit Scan, Projectile",
    "difficulty": "2",
    "id": 4
  }
```

### Postman command

```shell
curl --location 'http://localhost:3000/strategists/'
```

### Postman response

```shell
[
    {
        "superhero_name": "Cloak and Dagger",
        "healing_type": "Hit Scan (with Auto Aim), Area of Effect",
        "damage_type": "Hit Scan (with Auto Aim), Projectile",
        "difficulty": "3",
        "id": 1
    },
    {
        "superhero_name": "Invisible Woman",
        "healing_type": "Projectile",
        "damage_type": "Projectile",
        "difficulty": "4",
        "id": 2
    },
    {
        "superhero_name": "Luna Snow",
        "healing_type": "Hit Scan, Healing Over Time",
        "damage_type": "Hit Scan, Projectile",
        "difficulty": "4",
        "id": 3
    },
    {
        "superhero_name": "Jeff the Landshark",
        "healing type": "Projectile, Area of Effect",
        "damage_type": "Hit Scan, Projectile",
        "difficulty": "2",
        "id": 4
    }
]
```
