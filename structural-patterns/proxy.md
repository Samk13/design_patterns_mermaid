# Proxy
Provides a surrogate or placeholder for another object to control access to it
---
$~$
```mermaid
classDiagram
direction LR

Proxy --> RealSubject
 Client --> Subject
RealSubject --|> Subject
Proxy --|> Subject


class Client {
 }
class Subject {
  +Request()
 }
class Proxy {
+Request()
 }
class RealSubject {
+Request()
 }
```
$~$
## implemetation in Python:
<a href="" target="_blank">WIKIPEDIA BUILDER PATTERN</a>
```python
# TODO
```
# Implementation in JavaScrip:

```js
// TODO
```

## [Back to main](../readme.md)