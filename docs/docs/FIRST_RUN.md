## Setup inicial do Ambiente (First Run)  
*Sequencia de passos para ambiente*  

# Exemplo (Excluir)
* `$ vagrant up`  
* `$ vagrant ssh`  
* `$ cd /var/www/public`  
* `$ composer install`  
* `$ npm install`  
* `$ grunt`  
* `$ mysql`  
* `$ create database projeto;`  
* `$ exit`  
* `$ cd /var/www/public/`  
* `$ bin/cake migrations migrate`  
* `$ bin/cake migrations seed`  
* Adicionar no hosts `192.168.33.30 projeto.local` [Ajuda](http://link_para_ajuda.com.br/)  
* Rodar no endereço `projeto.local/`  
* Configurar arquivo `/src/tal.php` com as variaveis de ambiente `X`  
