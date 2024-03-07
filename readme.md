# Simple Props

Vous pourrez faire apparaître des props dans le jeu avec différentes options : réseau, gel et entité de mission.

## Description
Ce script vous permet de faire apparaître des props dans le jeu avec diverses options, telles que le réseau, le gel et l'entité de mission. Vous pouvez configurer les props dans le fichier `config.lua` et les faire apparaître dans le jeu selon vos besoins.

## Utilisation
Assurez-vous d'inclure le fichier `client.lua` dans votre dossier de scripts client de votre ressource FiveM. Vous pouvez également personnaliser les props en modifiant le fichier `config.lua`.

## Configuration des Props
Vous pouvez configurer les props dans le fichier `config.lua`. Chaque props est défini avec un identifiant unique, des coordonnées de position, des options de réseau, de gel et d'entité de mission.

## Exemple de Configuration
```lua
Config.Props = {
    -- ATM
    {propnum = "prop_atm_02", coords = vec4(-82.50, 74.1552, 71.250, 241.7245), network = false, MissionEntity = true, freeze = true},

    -- Station essence
    -- Ajoutez ici d'autres configurations de props selon vos besoins
}
```

## Licence
Ce projet est sous licence MIT

## Support
Pour toute question ou assistance, veuillez ouvrir une issue dans ce dépôt.

## Contribuer
Les contributions sont les bienvenues ! N'hésitez pas à ouvrir une pull request pour proposer des améliorations ou des correctifs.

---
## Crédits
© 2024 ChouCookieSan