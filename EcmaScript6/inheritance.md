```js
class a {
  constructor(name) {
     this.name = name;
  }
}

class b extends a {
  constructor() {
    super("some value");
  }  
}

class cextends b {
  constructor() {
    super();
    this.name = 'change the name';
  }  
}

```
