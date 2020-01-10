# phpMyAdmin

## Mise à jour de version

### Variables d'environnements

* `USER_PHP` : Utilisateur qui exécute le code PHP (Défaut : `apache`)
* `PMA_LINK` : Nom du lien symbolique de phpMyAdmin (Défaut : `phpMyAdmin`)

### Utilisation

#### Avec wget

```sh

wget -o /dev/null -O - https://raw.githubusercontent.com/GeorgioLPB/utils/master/updates/phpMyAdmin/update | sh

```

#### Avec curl

```sh

curl https://raw.githubusercontent.com/GeorgioLPB/utils/master/updates/phpMyAdmin/update | sh

```
