# wsl-docker-compose-lemp (линуха+нжинкс+мариядб+пхпмайадмин)
## lemp-сервер

ставим линух (я юзнул всл v2) 

ставим докер и докер композ 

клонируем реп 

меняем в настройке нжинкса server name на свой адрес сервака

запускаем 

"docker-compose up -d" 


если пхпмайадмин выеживается на дбшку, тогда стопаем контейнеры 

"docker-compose stop" 

потом запускаем дбшку сами 

"docker run --name mariadb -e MARIADB_ROOT_PASSWORD=admin -d mariadb --port 3306" 

и потом композим опять 

"docker-compose up -d" 
--------
убить контейнеры "docker-compose rm --all"
