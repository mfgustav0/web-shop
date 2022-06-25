<p align="center">
	<img src="http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge"/>
</p>

## Sobre a aplicação

Projeto de Loja Online com Laravel 9 e Vue.js 3.

## ⚙ Requisitos
- ``php 8.0^``
- ``node 13.4^``

## 🔨 Tecnologias utilizadas
- ``Laravel 9``
- ``Vue.js 3``

## Instalação
```shell
git clone https://github.com/mfgustav0/web-shop.git
composer install
npm install
copy .env.example .env
php artisan key:generate
```

## Edite o arquivo .env
- Configure a url do projeto na variavel APP_URL

- Configure a conexão do banco no arquivo, após isso execute o comando
```shell
php artisan migrate
```
