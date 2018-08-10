# Setup

Outils : 
- Votre IDE java SE favori (projet réalisé avec Eclipse)
- Une base de données MySQL (projet réalisé avec WampServer 3)
- Git en cmd

## Télécharger le projet de base

Démarrez Eclipse, copiez le chemin du workspace
Allez dans le dossier de votre workspace avec cmd
Exécutez  ```git clone https://github.com/vithyaepsi/Battle-level0.git```
Un dossier portant le nom du git a été créé

## Importer le projet de base
Sur Eclipse
```File > Import```
Dans le champ de recherche, tapez ```maven```
Choisissez ``existing maven projects``

Allez chercher le répertoire créé par le ```git clone``` précédemment
Finissez l'import
Le projet vide est prêt à utiliser.

## Config
Dans ``src/main/resources/META-INF/persistence.xml``
Renseignez une base de données existante et le user et le mot de passe de votre base de données.