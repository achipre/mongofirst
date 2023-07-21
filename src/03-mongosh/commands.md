# Connect to Container MongoDB
```sh
docker-compose exec mongodb bash
```
# Connet with mongosh
```sh
momngosh "mongodb://root:example@localhost:27017/?authMechanism=DEFAULT"
```
```sh
show dbs
show collections
```
```sh
use("chipre_store");
db.products.find();

```
