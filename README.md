# vue_basic_17_auth

## 260. Locking / Protecting Backend Resources

Melindungi data backend

Mengature rule firebase

```
{
  "rules": {
    "coaches":{
      ".read":true,
        ".write":"auth != null"
    },
      "requests":{
      ".read":"auth != null",
        ".write":true
      },
  }
}
```
