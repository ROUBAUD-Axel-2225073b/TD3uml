# TD3uml

```mermaid
class Livre {
  title: String
  auteur: String
  datePublication: Date
  genre: String
  numeroInventaire: Integer
  emprunter(): void
  restituer(): void
}
class Auteur {
  nom: String
  prenom: String
}
class Adherent {
  nom: String
  prenom: String
  dateNaissance: Date
  adresse: String
  numeroTelephone: Integer
  emprunter(): void
  restituer(): void
}
Livre "1..*" --> "1" Auteur
Livre "1..*" --> "1" Adherent

```
