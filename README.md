# wsl-docker-compose-lemp (линуха+нжинкс+мариядб+пхпмайадмин)
## lemp-сервер \n

ставим линух (я юзнул всл v2) \n

ставим докер и докер композ \n

клонируем реп \n

меняем в настройке нжинкса server name на свой адрес сервака \n

запускаем \n

"docker-compose up -d" \n


если пхпмайадмин выеживается на дбшку, тогда стопаем контейнеры \n

"docker-compose stop" \n

потом запускаем дбшку сами \n

"docker run --name mariadb -e MARIADB_ROOT_PASSWORD=admin -d mariadb --port 3306" \n

и потом композим опять \n

"docker-compose up -d" \n
