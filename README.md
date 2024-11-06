```
docker compose up -d
```

**Подключение**
```
mongosh --port 27017 --username root --password root --authenticationDatabase admin
# Or via URL string:
mongosh "mongodb://root:root@localhost:27017/?authSource=admin"
# or
mongodb://root:root@localhost:27017/<DB_NAME>?replicaSet=rs0&authSource=admin
```
