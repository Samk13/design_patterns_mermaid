# Mediator Pattern
--
TODO
```mermaid
classDiagram
direction TB

Mediator <|-- ConcreteMediator
Colleague <|-- ConcreteColleague1
Colleague <|-- ConcreteColleague2

class Mediator {
  +send(message: string, colleague: Colleague)
}

class ConcreteMediator {
  -colleague1: ConcreteColleague1
  -colleague2: ConcreteColleague2
  +send(message: string, colleague: Colleague)
}

class Colleague {
  +send(message: string)
  +receive(message: string)
}

class ConcreteColleague1 {
  -mediator: Mediator
  +send(message: string)
  +receive(message: string)
}

class ConcreteColleague2 {
  -mediator: Mediator
  +send(message: string)
  +receive(message: string)
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