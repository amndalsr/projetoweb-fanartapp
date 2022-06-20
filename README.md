<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

# README #

Projeto da Disciplina programação web - Portefolio host - http://fanartonline.herokuapp.com/

O projeto foi desenvolvido :

Front end: html 5-Com o content do Laravel blade; CSS- Com a biblioteca do Bootstrap, algumas adições classes quando houve necessidade JS e JQuery ,com a biblioteca do Bootstrap e do Pack do Node.JS,algumas funcionalidades feita por mim mesmo; Símbolos da biblioteca https://fontawesome.com/;. 
API Rest- Criada uma Api interna do proprio laravel para a pagina inical.

Back end: Php-Laravel como framework ; Modelo MVC; Migration Para modelar o banco de dados.

Banco de Dados: Mysql-phpmyadmin.

Run: git clone https://github.com/caco85/br.unicap.projetoweb-fanartapp.git

Run: cd br.unicap.projetoweb-fanartapp

Install Wamp Server ou xampp

Run : composer install (caso não tenha o composer baixe em https://getcomposer.org/download/)
caso der erro no install( Run: composer update)

Run: composer global require laravel/installer

Database: Este ponto vai ajustar seu banco de dados

Run: copy .env.example .env

Run: php artisan cache:clear

Run: php artisan config:clear

Run: php artisan key:generate

abrar o .env você tem que altear seu DB

DB_CONNECTION=mysql DB_HOST=127.0.0.1 DB_PORT=3306 (se usar outra porta altere aqui) DB_DATABASE=nome-exemple ou fanart DB_USERNAME=userExemple ou "root"
DB_PASSWORD=passwordExemple ou ""

depois vá em phpmyadmin add um BD com o seu nome ex: "fanart"

Para criar seu DB

Run: php artisan migrate --seed

Se ja existe migrate

Run: php artisan migrate:fresh --seed

isso ira inserir os registros iniciais na base de dados

obs foi alterado para postgre e caso use mysql na linha 18 do config/database.php altere 'pgsql'-> 'mysql'

Para habilitar o link do storage no laravel (habilitar o exebição das imagens)

Run : php artisan storage:link 
(caso bug a storage execute esses comando
cd public  ------

rm -r storage -------

cd..  

php artisan storage:link 

)

INICIANDO O SERVER
RUN: php artisan serve

abra o link em seu navegador in http://localhost:8000

<div align="center">
  <img src="https://user-images.githubusercontent.com/72527935/174625399-7b148a48-8509-4ca7-9bab-b0fcff552c41.png" >
  <img src="https://user-images.githubusercontent.com/72527935/174625262-4904eaf9-d521-4097-be54-9e7fd68b3227.png" >
  <img src="https://user-images.githubusercontent.com/72527935/174625488-d4e2503b-7644-4188-b438-3aaf3838bd2b.png" >
  <img src="https://user-images.githubusercontent.com/72527935/174625541-1b760f88-cd94-4ca2-8353-acb178f75cd4.png" >
</div>
