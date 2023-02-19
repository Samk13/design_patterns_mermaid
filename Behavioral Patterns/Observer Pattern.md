# Observer Pattern
--
TODO
```mermaid
classDiagram
direction LR

Subject <|-- ConcreteSubject
Observer <|-- ConcreteObserver

Subject --> Observer
Subject --> detach()
Subject --> attach()

class Subject {
  -observers: Observer[]
  +attach(observer: Observer)
  +detach(observer: Observer)
  +notify()
}

class ConcreteSubject {
  +setState(state: any)
  +getState(): any
}

class Observer {
  +update()
}

class ConcreteObserver {
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