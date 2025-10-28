# nexcloud-all-in-one
nexcloud con postgres + onlyoffyce


entrar docker exec -it app-server bash

para agregar ip o dominios
php occ config:system:set trusted_domains 1 --value="10.0.1.71"
php occ config:system:set trusted_domains 2 --value="midominio.com"

colcoar JWT  que se colcoa en docker compose en el archivo bash
