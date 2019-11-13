# MongoPython

Jupyter notebooks demonstrating accessing MongoDB with Python

# MongoDB

- https://www.mongodb.com/

## Install MongoDB server in Ubuntu 18.04

```bash
$ sudo apt install mongodb
```

## Install MongoDB client in Ubuntu

```bash
$ sudo apt install mongodb-clients
```

## Run mongo client shell

```bash
$ mongo
```

### MongoDB Database Commands

- https://docs.mongodb.com/manual/introduction/
- can also play with online MongoDB shell on the site

```
> db
> show dbs
> use <database> 
    - database can be new or existing
> use students
> show dbs
    - will not list database until some records are inserted into a collection
use collection to insert document
> db.AdvPy.insertOne({fname: "John"})
> db.AdvPy.insertMany([{fname: "Jake"}, {fname: "Jen"}])

```
