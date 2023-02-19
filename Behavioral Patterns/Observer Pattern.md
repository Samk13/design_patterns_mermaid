# Observer Pattern
--
TODO
```mermaid
classDiagram
direction LR

Subject <|-- ConcreteSubject
Subject *-- Observer
Observer <|-- ConcreteObserverA
Observer <|-- ConcreteObserverB
  class Subject{
    -observers: Observer[]
    +attach(observer: Observer)
    +detach(observer: Observer)
    +notify()
  }
  class ConcreteSubject{
    +getState()
    +setState(state: any)
  }
  class Observer{
    +update()
  }
  class ConcreteObserverA{
    +update()
  }
  class ConcreteObserverB{
    +update()
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