# Docker Compose for Assignment #4: Forum App

Code untuk file `docker-compose.yml` di project Assignment #4: Forum App.
Letakkan sejajar dengan direktori service-service yang lain (jangan di dalamnya).

```
Wrapper/Root Directory
│
├── forumapp-api-gateway
│
├── forumapp-replies
│
├── forumapp-threads
│
├── forumapp-users
│
└── docker-compose.yml # di sini
```

Terdapat 2 versi file docker compose, perbedaannya hanya pada MongoDB yang digunakan.
1. `docker-compose.yml` : untuk deployment service yang menggunakan [MongoDB Atlas](https://www.mongodb.com/products/platform/atlas-database).
2. `docker-compose-v2.yml` : untuk deployment service yang menggunakan [mongo image](https://hub.docker.com/_/mongo).

Gunakan salah satu sesuai kebutuhan.
