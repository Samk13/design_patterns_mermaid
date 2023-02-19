# Chain of Responsibility

<!-- TODO -->
--

```mermaid
classDiagram
direction TB

Context --> Expression
Context o--> TerminalExpression
Context o--> NonterminalExpression

class Context {
  -input: string
  -output: string
  +getInput()
  +getOutput()
  +setOutput(string)
}

class Expression {
  +interpret(Context)
}

class TerminalExpression {
  +interpret(Context)
}

class NonterminalExpression {
  -left: Expression
  -right: Expression
  +interpret(Context)
}

class TerminalExpressionA {
  +interpret(Context)
}

class TerminalExpressionB {
  +interpret(Context)
}

class NonterminalExpressionA {
  +interpret(Context)
}

class NonterminalExpressionB {
  +interpret(Context)
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