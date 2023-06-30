**Class "Utilisateurs"**
- IDUtilisateur (Clé primaire)
- Nom
- Prénom
- Adresse
- AdresseEmail
- MotDePasse
- Table "Positions"


**Class "Positions"**

- IDPosition (Clé primaire)
- IDUtilisateur (Clé étrangère vers la table "Utilisateurs")
- Latitude
- Longitude
- DateHeure


**Class "LieuxInteret"**

- IDLieu (Clé primaire)
- NomLieu
- Latitude
- Longitude
- Description
- Catégorie

**Class "InstructionsVocales"**

- IDInstruction (Clé primaire)
- IDUtilisateur (Clé étrangère vers la table "Utilisateurs")
- Instruction
- DateHeure