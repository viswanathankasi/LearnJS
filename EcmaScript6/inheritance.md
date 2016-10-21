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

export class c extends b {
  constructor() {
    super();
    this.name = 'change the name';
  }  
}

export function generate() {
  return new c();
}
```
