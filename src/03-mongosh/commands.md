## Connect to contianer 

```sh
docker-compose exec mongodb bash
```

## Connect with mongosh

```sh
mongosh "mongodb://root:root123@localhost:27017/?tls=false"
mongosh "mongodb+srv://admin:admin@mongodb101.zl5qf9z.mongodb.net/"
```
```sh
show dbs
show collections
```
```sh
use("platzi_store")
db.products.find()
```