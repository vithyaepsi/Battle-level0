# Setup

Outils : 
- Votre IDE java SE favori (projet r�alis� avec Eclipse)
- Une base de donn�es MySQL (projet r�alis� avec WampServer 3)
- Git en cmd

## T�l�charger le projet de base

D�marrez Eclipse, copiez le chemin du workspace
Allez dans le dossier de votre workspace avec cmd
Ex�cutez  ```git clone https://github.com/vithyaepsi/Battle-level0.git```
Un dossier portant le nom du git a �t� cr��

## Importer le projet de base
Sur Eclipse
```File > Import```
Dans le champ de recherche, tapez ```maven```
Choisissez ``existing maven projects``

Allez chercher le r�pertoire cr�� par le ```git clone``` pr�c�demment
Finissez l'import
Le projet vide est pr�t � utiliser.

## Config
Dans ``src/main/resources/META-INF/persistence.xml``
Renseignez une base de donn�es existante et le user et le mot de passe de votre base de donn�es.