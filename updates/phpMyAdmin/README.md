# phpMyAdmin

## Mise à jour de version

### Variables d'environnements

* `USER_PHP` : Utilisateur qui exécute le code PHP (Défaut : `apache`)
* `PMA_LINK` : Nom du lien symbolique de phpMyAdmin (Défaut : `phpMyAdmin`)

### Utilisation

#### Avec wget

```bash

wget -o /dev/null -O - https://raw.githubusercontent.com/GeorgioLPB/utils/master/updates/phpMyAdmin/update | bash

```

#### Avec curl

```bash

curl https://raw.githubusercontent.com/GeorgioLPB/utils/master/updates/phpMyAdmin/update | bash

```
