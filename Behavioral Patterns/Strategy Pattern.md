# Strategy Pattern
--
TODO
```mermaid
classDiagram
direction LR

Context --> Strategy
Context *-- Client
Strategy <|-- ConcreteStrategyA
Strategy <|-- ConcreteStrategyB
Strategy <|.. StrategyInterface
  class Client {
  }
  class Context{
    -strategy:StrategyInterface
    +setStrategy(strategy: StrategyInterface)
    +doSomething()
  }
  class StrategyInterface{
    +doSomething()
  }
  class ConcreteStrategyA{
    +doSomething()
  }
  class ConcreteStrategyB{
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