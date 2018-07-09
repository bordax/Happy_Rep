# Instalação
É necessário instalar um ambiente para usar o Laravel.

#### Windows
 - Siga [este tutorial](https://www.webhostface.com/kb/knowledgebase/install-laravel-windows/) até a seção "Composer from Windows CMD" (incluindo esta seção). 
 - Siga também [este tutorial](https://santiagobambui.wordpress.com/2013/02/06/ativando-o-postgresql-no-xampp/) para ativar o driver do Postgreql no seu xampp.
 - Clone esse repositório na pasta 'www' do seu servidor

#### Linux
 - Execute 'sudo apt-get install lamp-server^' (com o acento circunflexo no final)
 - Instale o PHP composer com o comando abaixo
```
curl -sS https://getcomposer.org/installer | sudo php -- --install-dir=/usr/local/bin --filename=composer'
```
 - Clone o projeto dentro de /var/www/html

### Geral
Após a instalação do ambiente, execute as seguintes etapas:
 - Execute 'composer install' de dentro da pasta do projeto
 - Inicie o server com 'php artisan serve' de dentro da pasta do projeto
 - Navegue para [localhost:8000/test-conn](localhost:8000/test-conn)
 - Se aparecer os dados de 'Luciana' e 'Lucas', deu certo

