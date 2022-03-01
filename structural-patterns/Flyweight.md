# Flyweight
Uses sharing to support large numbers of fine-grained objects efficiently
---
$~$
```mermaid
classDiagram
direction LR

Client --> FlyweightFactory
Client --> flyweight
Client --> UnsharedFlyweight
 Flyweight --o FlyweightFactory
 UnsharedFlyweight --|> Flyweight
flyweight --|> Flyweight

class Client {
    +GetFlyweight(key)
 }
class UnsharedFlyweight {
  +Operation(state)
 }
class FlyweightFactory {
    +GetFlyweight(key)
 }
class flyweight {
  +Operation(state)
 }
class Flyweight {
  +Operation(state)
 }
class UnsharedFlyweight {
  +Operation(state)
 }
```
$~$
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