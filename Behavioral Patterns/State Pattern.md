# State Pattern
--
TODO
```mermaid
classDiagram
direction LR

Context --> State
Context *-- Client
State <|.. StateInterface
State <|-- ConcreteStateA
State <|-- ConcreteStateB
  class Client {
  }
  class Context{
    -state:StateInterface
    +setState(state: StateInterface)
    +doSomething()
  }
  class StateInterface{
    +doSomething()
  }
  class ConcreteStateA{
    +doSomething()
  }
  class ConcreteStateB{
    +doSomething()
  }

```

## implemetation in python:
```python
TODO
```
# JavaScrip implementation:

```js
TODO
```

## [Back to main](../readme.md)