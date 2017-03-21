# JSON-crud

TODO: Refactor for publish as npm package

Minimalist API for interacting with JSON data in the format. Currently it has `fs` and `underscore` as its dependencies. It's currently setup for use with `node` modules but can easily be modified to be independent of `node`.

```json
{
  "lastId": 0,
  "data": []
}
```

`lastId` is auto-incremented by the API starting at 0. The first `data` entry will have an idea of 1. `ID` continually increments. `data` is expected to be stored as objects. For example, here is JSON data containing 3 data with no data deleted:

```json
{
  "lastId": 3,
  "data": [
    { "id": 1, "task": "Task 1" },
    { "id": 2, "task": "Task 2" },
    { "id": 3, "task": "Task 3" }
  ]
}
```

## The API has the following properties and methods:

### Properties

#### JSONFilePath
#### tempStore

### Methods

#### init(filePath)
#### read() 
#### getLastId()
#### get(id)
#### getSanitized() 
#### put(data) 
#### set(input)
#### save(input)
#### delete(id) 
#### record() 
#### isUnique(field, value)
#### findOne(field, value) 
#### findMany(field, value)




