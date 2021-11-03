# Catálogo Chico Rei

## Tecnologias Utilizadas
- Laravel
- Vue.js
- Mysql
- Bem como outras utilizadas para utilização dos framworks...

## Requisitos
- Composer
- Node e Npm
- Mysql
- PHP
- APACHE
- Git

## API para Consumo

Link: https://rapidapi.com/okami4kak/api/scrapingant/

A api tem um limite grátis de 500 requisições, acessando a página deve ser extraído a Key e o Host afim de inserir posteriormente no projeto.

## Como utilizar

### Clone do Repositório

Primeiro deve-se clonar o repositório para utilização local na máquina, através de um terminal.

```sh
  git clone https://github.com/HyagoAssis/projeto-laravel-vuejs
```
Ou caso tenha key ssh:
```sh
  git clone git@github.com:HyagoAssis/projeto-laravel-vuejs.git
```
### Configuraçõese Iniciais

Devemos criar um arquivo .env copiado o arquivo .env.example e inserir os registro do nome do banco, de usuário e senha. Também no final do arquivo deve inserido a key e o host da api (Últimas duas linhas).

### Intalações

Agora vamos instalar as depêndencias necessárias e criar o build da interface.
```sh
  composer install
  npm install
  npm run dev
```
Gerar chave de autenticação
```sh
  php artisan key:generate
```

Rodar as migrações
```sh
  php artisan migrate
```
### Rodar
Para rodar o projeto bastar iniciar o servidor local

```sh
  php artisan serve
```