# Connect to container

```sh
docker-compose exec mongodb bash
```

# Connect with mongosh

```sh
mongosh "mongodb://root:admin%2410@localhost:27017/?authMechanism=DEFAULT"
mongosh "mongodb+srv://arnoladmin:5f6Gl4AmBjaORbgq@mongodb101.enavsxs.mongodb.net/test"
```

# commands

```sh
show dbs
show collections
use("platzi_store")
db.products.find()
```
