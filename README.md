# plantumltest

```mermaid
  graph TD;
      A-->B;
      A-->C;
      B-->D;
      C-->D;
```

```plantuml
@startuml component
actor client
node app
database db

db -> app
app -> client
@enduml
```
