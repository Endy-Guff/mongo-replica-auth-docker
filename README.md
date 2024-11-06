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

**Прописать в etc/hosts**
```
sudo nano /etc/hosts

127.0.0.1       host.docker.internal
```