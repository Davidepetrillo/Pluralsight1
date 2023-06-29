Introduction to OOP

 ## Flowcharts

```mermaid
graph TB
    A[Start] --> B[Process]
    B --> C[Decision]
    C -- Yes --> D[Path 1]
    C -- No --> E[Path 2]
    D --> F[End]
    E --> F
 ```

 ## Class Diagram

 ```mermaid
 classDiagram
  class Person {
  +Id : int
  +FirstName : string
  +LastName : string
  -privateProperty : string
  #protectedProperty : string
  %InternalProperty : string
  }
 ```