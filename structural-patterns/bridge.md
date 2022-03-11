# Bridge
Decouples an abstraction from its implementation so that the two can vary independently
---
```mermaid
classDiagram
direction LR

Client --> Abstraction
Implementor <|-- ConcreteImplementorB
Implementor <|-- ConcreteImplementorA
Implementor --o Abstraction

class Client {
 }
class Abstraction {
    +Operation()
 }
class Implementor {
    +OperationImpl()
 }
class ConcreteImplementorA {
    +OperationImpl()
 }
 class ConcreteImplementorB {
    +OperationImpl()
 }

```
## implemetation in Python:
<a href="" target="_blank">WIKIPEDIA BUILDER PATTERN</a>
```python
# TODO
```
# Implementation in JavaScrip:

```js
// TODO
```

## [Back to main](../readme.md)