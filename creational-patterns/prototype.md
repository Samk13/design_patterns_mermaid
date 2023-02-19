# Prototype
Specifies the kinds of objects to create using a prototypical instance and create new objects by copying this prototype
---
```mermaid
classDiagram
direction LR

Client --> Prototype
 Prototype <|-- ConcretePrototype1
 Prototype <|-- ConcretePrototype2


class Prototype {
    +Clone()
  }

class ConcretePrototype1{
    +Clone()
}

class ConcretePrototype2{
    +Clone()
}

```
## implemetation in Python:
<a href="" target="_blank">WIKIPEDIA BUILDER PATTERN</a>
```python
import copy

class Prototype:
    def __init__(self):
        self._objects = {}

    def register_object(self, name, obj):
        self._objects[name] = obj

    def unregister_object(self, name):
        del self._objects[name]

    def clone(self, name, **kwargs):
        obj = copy.deepcopy(self._objects.get(name))
        obj.__dict__.update(kwargs)
        return obj

class Product:
    def __init__(self, name):
        self.name = name

    def __str__(self):
        return f"Product: {self.name}"

if __name__ == "__main__":
    prototype = Prototype()
    prototype.register_object("product", Product("Default Product"))

    product = prototype.clone("product")
    print(product)

    product = prototype.clone("product", name="Custom Product")
    print(product)

```
# Implementation in JavaScript:

```js
class Prototype {
  constructor() {
    this.objects = {};
  }

  registerObject(name, obj) {
    this.objects[name] = obj;
  }

  unregisterObject(name) {
    delete this.objects[name];
  }

  clone(name, additionalProps = {}) {
    const obj = { ...this.objects[name] };
    return { ...obj, ...additionalProps };
  }
}

class Product {
  constructor(name) {
    this.name = name;
  }

  toString() {
    return `Product: ${this.name}`;
  }
}

// Usage
const prototype = new Prototype();
prototype.registerObject("product", new Product("Default Product"));

let product = prototype.clone("product");
console.log(product.toString());

product = prototype.clone("product", { name: "Custom Product" });
console.log(product.toString());

```

## [Back to main](../readme.md)