<div style="display: flex; align-items: center;">
  <img src="https://github.com/abraao69/Setup-Docker-PHP-7.4/blob/master/logo.png" alt="Logo" width="200" height="100">
  <br><br>
</div>
<img src="https://tse1.mm.bing.net/th?id=OIP.FKz3rr0jQPeHTE_8Q-XyIgHaDt&pid=Api&P=0&h=180" alt="Logo" width="1000" height="400">
#Setup Docker Login e Register com Laravel-11 utilizando Breeze 
### Passo a passo
Clone Repositório
```sh
git clone https://github.com/especializati/forum-laravel-11.git
```
```sh

```

Suba os containers do projeto
```sh
docker-compose up -d
```


Crie o Arquivo .env
```sh
cp .env.example .env
```

Acesse o container app
```sh
docker-compose exec app bash
```


Instale as dependências do projeto
```sh
composer install
```

Gere a key do projeto Laravel
```sh
php artisan key:generate
```

OPCIONAL: Gere o banco SQLite (caso não use o banco MySQL)
```sh
touch database/database.sqlite
```

Rodar as migrations
```sh
php artisan migrate
```

Acesse o projeto
[http://localhost:8000](http://localhost:8000)
