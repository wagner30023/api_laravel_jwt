# Construindo uma API com Laravel e JWT 


## Para rodar o projeto

Criar arquivo .env

``cp .env.example .env``

Subir o projeto

``make up``

Instalar dependências

``make composer``

``composer install --ignore-platform-reqs``

Criar chave da aplicação

``make php``

``php artisan key:generate``

Criar chave secreta para o JWT

``make php``

``php artisan jwt:secret``

## Links


[Zip com arquivos docker](https://bit.ly/vitor-laravel-jwt-utils)

[Documentação do JWT](https://jwt.io/)

[Lib do JWT utilizada](https://github.com/tymondesigns/jwt-auth)
