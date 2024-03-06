# Docker Compose Wordpress


## Commande pour lancer la stack

`docker-compose up -d`

![](readme_docs/1728af82.png)

## Volumes

| Dossier     | Utilisation                                                               |
|-------------|---------------------------------------------------------------------------|
| `./wp-app`  | Contient les fichiers de wordpress                                        |
| `./config`  | Contient les fichiers de configurations des différents containers |
| `./db_data`   | Contient les fichiers de la base de données                               |
| `./backups` | Contient la sauvegarde de la base de données                              |

## Rappels des ports utilisés dans la stack

| Ports | Utilisation |
|-------|-------------|
| 8080  | Wordpress   |
| 8081  | PhpMyAdmin  |
| 3308  | MySQL       |



# Source

https://www.bitdoze.com/install-wordpress-docker/#3-setup-env-file