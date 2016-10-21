Pre EcmaScript6
```js 
var car = function (opts) {
  this.name = opts.name;
}

car.protype.drive = function () {
  // code to move this car
}

car.prototype.start = function(key) {
  // code to start the engine
}
```

EcmaScript6
```js
class car {
  constructor(name) {
    this.name = name;
  }

  drive() {
    // code to move this car
  }
  
  start(key) {
    // code to start the engine
  }
}

```
