# Decorator
Attaches additional responsibilities to an object dynamically
---
```mermaid
classDiagram
direction LR

Component --o Decorator
Component <|-- Decorator
Decorator <|-- ConcreteDecorator
Component <|-- ConcreteComponent


class Component {
    +Operation()
 }
class ConcreteComponent {
    +Operation()
 }
class Decorator {
   +Operation()
 }
class ConcreteDecorator {
    +Operation()
    +AddedBehavior()
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