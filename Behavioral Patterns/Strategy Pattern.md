# Strategy Pattern
--
TODO
```mermaid
classDiagram
direction LR

Context *-- StrategyInterface
Context --> ConcreteStrategy1
Context --> ConcreteStrategy2

class Context {
  -strategy: StrategyInterface
  +setStrategy(strategy: StrategyInterface)
  +executeStrategy(): string
}

interface StrategyInterface {
  +execute(): string
}

class ConcreteStrategy1 {
  +execute(): string
}

class ConcreteStrategy2 {
  +execute(): string
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