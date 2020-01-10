# phpMyAdmin

## Mise à jour de version

### Variables d'environnements

| Variables  | Défauts      | Utilisations                         |
|------------|--------------|--------------------------------------|
| `USER_PHP` | `apache`     | Utilisateur qui exécute le code PHP  |
| `PMA_LINK` | `phpMyAdmin` | Nom du lien symbolique de phpMyAdmin |


### Utilisations

#### Avec wget

```bash

# Utilisation normal
wget -o /dev/null -O - https://raw.githubusercontent.com/GeorgioLPB/utils/master/updates/phpMyAdmin/update | bash

# Utilisation en mode debug
wget -o /dev/null -O - https://raw.githubusercontent.com/GeorgioLPB/utils/master/updates/phpMyAdmin/update | bash -x

```

#### Avec curl

```bash

# Utilisation normal
curl -Ns https://raw.githubusercontent.com/GeorgioLPB/utils/master/updates/phpMyAdmin/update | bash

# Utilisation en mode debug
curl -Ns https://raw.githubusercontent.com/GeorgioLPB/utils/master/updates/phpMyAdmin/update | bash -x

# Utiliser sans cache web :
curl -Ns -H 'Cache-Control: no-cache' https://raw.githubusercontent.com/GeorgioLPB/utils/master/updates/phpMyAdmin/update | bash

```
