# TD3uml

```mermaid
classDiagram
  class Article
  class Livre
  class CD
  class Client
  class CompagnieAerienne
  class Vol
  class Personne
  class Mariage
  class Document
  class Imprimante

  Article <|-- Livre
  Article <|-- CD
  Client o-- Article
  CompagnieAerienne o-- Vol
  Personne o-- Mariage
  Personne o-- Mariage
  Document o-- Imprimante
```
