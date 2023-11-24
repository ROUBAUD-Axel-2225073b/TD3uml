# TD3uml

```mermaid
classDiagram
  class Article
  class Livre
  class CD
  class Client
  Class Commande
  Article <|-- Livre
  Article <|-- CD
  
  Client "0..n" o-- Commande
  Commande "0..1" o-- Article
```

```mermaid
classDiagram
  class CompagnieAerienne
  class Vol
  class Client
Client "0..n" o-- CompagnieAerienne
  CompagnieAerienne "0..1" o-- Vol
```


```mermaid
classDiagram
  class Personne
  class Mariage
  Personne o-- Mariage
  Personne o-- Mariage
```

```mermaid
classDiagram
  class Document
  class Imprimante
  Document o-- Imprimante
```
