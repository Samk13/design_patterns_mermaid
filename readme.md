# Design Patterns Cheat Sheet using mermaid mermaid

## Creational Patterns

### [Abstract Factory](creational-patterns/abstract_factory.md)
### [Builder](creational-patterns/builder.md)
### [Factory Method](creational-patterns/factory_method.md)
### [Prototype](creational-patterns/prototype.md)
### [Singleton](creational-patterns/singleton.md)

## Structural Patterns

### [Adapter](structural-patterns/adapter.md)
### [Bridge](structural-patterns/bridge.md)
### [Composite](structural-patterns/composite.md)
### [Decorator](structural-patterns/decorator.md)
### [facade](structural-patterns/facade.md)
### [flyweight](structural-patterns/flyweight.md)
### [Proxy](structural-patterns/proxy.md)
### [Proxy](structural-patterns/proxy.md)

## Behavioral Patterns

### [Chain of Responsibility](behavioral_patterns/chain_of_responsibility.md)
### [Command Pattern](behavioral_patterns/command_pattern.md)
### [Interpreter Pattern](behavioral_patterns/interpreter_pattern.md)
### [Iterator Pattern](behavioral_patterns/iterator_pattern.md)
### [Mediator Pattern](behavioral_patterns/mediator_pattern.md)
### [Memento Pattern](behavioral_patterns/memento_pattern.md)
### [Observer Pattern](behavioral_patterns/observer_pattern.md)
### [State Pattern](behavioral_patterns/state_pattern.md)
### [Strategy Pattern](behavioral_patterns/strategy_pattern.md)
### [Template Pattern](behavioral_patterns/template_method_pattern.md)
### [Visitor Pattern](behavioral_patterns/visitor_pattern.md)

## UML class diagran

### [UML](uml-diagram/uml.md)

# mermaid arrows explaination:
In Mermaid diagrams, arrows represent the relationship between two elements. They indicate the direction of the relationship and can be customized with different arrow types.

There are several types of arrow directions and styles you can use in Mermaid:

`-->` : The standard arrow, indicating a one-way relationship from the left element to the right element.

`---` : A two-way relationship, indicating that both elements have a relationship with each other.

`-->|` : A dashed arrow indicating a one-way relationship from the left element to the right element.

`---|` : A dashed two-way relationship between two elements.

`--x` : An arrow with a crossbar, indicating a relationship that has been terminated.

`--o` : An arrow with a circle, indicating a relationship that has been looped back to the starting point.

`--|>`: An arrowhead is a closed triangle, this Represent an inheritance or implementation relationship between classes or interfaces.

```mermaid
graph LR
A-->|The standard arrow, indicating a one-way relationship from the left element to the right element.|B
C---|A two-way relationship, indicating that both elements have a relationship with each other.|D
E-->|A dashed arrow indicating a one-way relationship from the left element to the right element.|F
G---|A dashed two-way relationship between two elements.|H
I--x|An arrow with a crossbar, indicating a relationship that has been terminated.|J
K--o|An arrow with a circle, indicating a relationship that has been looped back to the starting point.|L;
M --|> |Closed triangle, inheritance or implementation relationship between classes or interfaces.|O

```