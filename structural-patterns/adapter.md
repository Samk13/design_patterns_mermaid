# Adapter
Converts the interface of a class into another interface clients expect

---
```mermaid
classDiagram
direction LR

Client --> Target
Target <|--Adapter
Adapter -->Adaptee


class Client {
 }
class Target {
    +Request()
 }
class Adapter {
    +Request()
 }
class Adaptee {
    +SpecificRequest()
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