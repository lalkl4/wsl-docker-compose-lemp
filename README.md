# wsl-docker-compose-lemp (линуха+нжинкс+мариядб+пхпмайадмин)
## lemp-сервер

я юзал все команды на вслке v2

ставим докер и докер композ 

клонируем реп 

меняем в настройке нжинкса server name на свой адрес сервака

запускаем 

"docker-compose up -d" 


убить контейнеры 
"docker-compose stop"
"docker-compose rm --all"

креденшлы:

phpmyadmin: сервер - mysql; пользователь - root; пароль - admin;

mariadb: root; admin

сайт - пхпшный, директория - ./public/*    ,   Если что там index.php хранится 

логи (err, access) нжинкса - в ./logs
