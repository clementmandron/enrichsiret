# Chercher les codes communes dans l'API Sirene

La clé [API Sirene](https://api.insee.fr/catalogue/site/themes/wso2/subthemes/insee/pages/item-info.jag?name=Sirene&version=V3&provider=insee) est à mettre dans un fichier `local.config.json` sur la base du `template.config.json`

## Structure du .csv de données d'entrée

Le .csv de données d'entrée doit s'appeler `enrichsiret.csv`

Voici la strcuture qu'il peut avoir (le principal est d'avoir les SIRET en première colonne, les autres colonnes sont optionnelles).

| SIRET           | Entreprise     |
| --------------- | -------------- |
| 82379887100013  | Datactivist    |
| 89018373400015  | Entreprise B   |
