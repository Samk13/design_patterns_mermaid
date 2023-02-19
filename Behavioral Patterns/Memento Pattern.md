# Memento Pattern
--
TODO
```mermaid
classDiagram
direction LR

Originator <|-- Memento
Caretaker --> Originator
Originator --> Memento

class Originator {
  -state: string
  +createMemento(): Memento
  +restoreFromMemento(memento: Memento)
}

class Memento {
  -state: string
  +getState(): string
}

class Caretaker {
  -mementos: Memento[]
  +addMemento(memento: Memento)
  +getMemento(index: number): Memento
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