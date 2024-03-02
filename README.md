# Docker-cohort-2.0


Slides Link : https://projects.100xdevs.com/tracks/YOSAherHkqWXhOdlE4yE/sql-11

TERMINAL COMMANDS:

sudo docker run -e POSTGRES_PASSWORD=pass -d -p 5432:5432 postgres

sudo docker exec -it 28c9df52d6e5 /bin/bash

root@28c9df52d6e5:/# psql -h localhost -d postgres -U postgres

$postgres --------> /q
$root     --------> exit

npm init -y

npx tsc --init

npm install pg

npm i @types/pg
