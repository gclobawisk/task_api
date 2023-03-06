<h1 style="align-center"> API LARAVEL + JWT </h1>

# TUTORIAL DE INSTALAÇÃO DA API

Export ou Execute uma Query com o arquivo contido no repositório chamado: task_api.sql

git clone https://github.com/gclobawisk/task_api.git
composer install

Ao inserir o comando composer
todas as dependências serão instaladas, inclusive: tymon/jwt-auth

Renomeie a .env.example para .env

configure a ENV

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=task_api
DB_USERNAME=root
DB_PASSWORD=

php artisan key:generate

php artisan jwt:secret
pegar a imagem php artisan jwtsecret


php artisan serve
