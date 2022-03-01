# Prototype
Specifies the kinds of objects to create using a prototypical instance and create new objects by copying this prototype
---
$~$
```mermaid
classDiagram
direction LR

Client --> Prototype
 Prototype <-- ConcretePrototype1
 Prototype <-- ConcretePrototype2


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
$~$
## implemetation in Python:
<a href="" target="_blank">WIKIPEDIA BUILDER PATTERN</a>
```python
# TODO
```
# Implementation in JavaScript:

```js
// TODO
```

## [Back to main](../readme.md)