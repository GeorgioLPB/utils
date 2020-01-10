# phpMyAdmin

## Mise à jour de version

### Variables d'environnements

| Variables  | Défauts      | Utilisations                         |
|------------|--------------|--------------------------------------|
| `USER_PHP` | `apache`     | Utilisateur qui exécute le code PHP  |
| `PMA_LINK` | `phpMyAdmin` | Nom du lien symbolique de phpMyAdmin |

### Utilisation

#### Avec wget

```bash

wget -o /dev/null -O - https://raw.githubusercontent.com/GeorgioLPB/utils/master/updates/phpMyAdmin/update | bash

```

#### Avec curl

```bash

curl -Ns https://raw.githubusercontent.com/GeorgioLPB/utils/master/updates/phpMyAdmin/update | bash

```
