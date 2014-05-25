# rest-store

[fluxxor store](http://fluxxor.com/) for REST APIs

## how to use

```
npm install --save rest-store
```

```
var RestStore = require('rest-store');
var Fluxxor = require('fluxxor');

var MyStore = RestStore('/people');

var actions = {...};
var stores = { MyStore: MyStore };

var flux = new Fluxxor.Flux(stores, actions);
```
