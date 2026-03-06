# PWIII---Camilla.Vitoria
Aulas de Programação Web III com o professor João Siles.

## Qual é o intuito deste repositório?
Este repositório será utilizado para armazenar conteúdos e atividades que serão passados durante as aulas de Programção Web III.

---

# Guia de Uso do Laravel

Este projeto utiliza o **Laravel**, um framework PHP moderno e robusto para desenvolvimento web.  
Aqui você encontrará instruções para configurar, rodar e entender a estrutura básica do projeto.

---

## Instalação

### Pré-requisitos
- PHP >= 8.1  
- Composer  
- MySQL ou outro banco de dados compatível  
- Node.js e NPM  

### Criando o projeto
```bash
composer create-project laravel/laravel nome-do-projeto
cd nome-do-projeto
php artisan serve

APP_NAME="MeuProjeto"
APP_ENV=local
APP_KEY=base64:...
APP_DEBUG=true
APP_URL=http://localhost

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=meu_banco
DB_USERNAME=root
DB_PASSWORD=senha

php artisan key:generate

## Configuração
 - APP_NAME="MeuProjeto"
 - APP_ENV=local
 - APP_KEY=base64:...
 - APP_DEBUG=true
 - APP_URL=http://localhost
 - DB_CONNECTION=mysql
 - DB_HOST=127.0.0.1
 - DB_PORT=3306
 - DB_DATABASE=meu_banco
 - DB_USERNAME=root
 - DB_PASSWORD=senha

## Estrutura do Projeto
-   **Rotas** → `routes/web.php`
  
-   **Controllers** → `app/Http/Controllers`
    
-   **Models** → `app/Models`
    
-   **Views (Blade)** → `resources/views`

## Banco de Dados
 - **Criar migration:** php artisan make:migration create_posts_table
 
 - **Rodar migrations:** php artisan migrate
 
 - **Criar model:** php artisan make:model Post

## Front-end
 - **Instalar dependências:** npm install
 
 - **Compilar assets:** npm run dev

## Comandos úteis
 - **Criar Controller:** php artisan make:controller NomeController
 
 - **Criar Seeder:** php artisan make:seeder NomeSeeder
 
 - **Popular banco:** php artisan db:seed


