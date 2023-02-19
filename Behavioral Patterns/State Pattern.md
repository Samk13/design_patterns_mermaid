# State Pattern
--
TODO
```mermaid
classDiagram
direction LR

Context *-- StateInterface
Context --> ConcreteState1
Context --> ConcreteState2

class Context {
  -state: StateInterface
  +setState(state: StateInterface)
  +request()
}

interface StateInterface {
  +handle()
}

class ConcreteState1 {
  +handle()
}

class ConcreteState2 {
  +handle()
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