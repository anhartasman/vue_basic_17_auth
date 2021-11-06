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

## 261. Adding an Authentication Page (Login & Signup)

Menambah halaman login dan signup

## 262. Preparing Vuex

Menyiapkan vuex

baca Firebase Auth REST API

## 263. Adding a "Signup" Action & Flow

Menambah flow signup
