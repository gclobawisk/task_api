<h1 style="align-center"> API LARAVEL + JWT </h1>

## Requerimentos:
* LARAVEL 9+
* PHP 8+
* MYSQL OU MARIADB
* COMPOSER
* JWT-AUTH 2.0.0: documentação -> https://jwt-auth.readthedocs.io/en/develop


# TUTORIAL DE INSTALAÇÃO DA API

# PASSO 1: CONFIGURAÇÃO DO BANCO DE DADOS.

Exporte ou Execute uma Query com o arquivo contido no repositório chamado: task_api.sql no MYSQL



# PASSO 2: CONFIGURAÇÃO DO AMBIENTE DE DESENVOLVIMENTO.

Crie uma nova pasta acessa a mesma e clone o repositório através do comando abaixo:

``` git clone https://github.com/gclobawisk/task_api.git ```

Agora vamos configurar o LARAVEL instalando as dependências:

Necessário possuir PHP versão 8.0+

``` composer install ```


Ao inserir o comando composer
todas as dependências serão instaladas, inclusive o tymon/jwt-auth que será utilizado para autenticação do usuário

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
