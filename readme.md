## Sobre o projeto

Blog desenvolvido com laravel
- clone o projeto, acesse a pasta do projeto e execute o comando cp .env-example .env.
- Requer o composer e php 7.2.
- rode o comando na raiz do projeto composer install.
- apos finalizar configure no .env as informaçoes do banco de dados, crie a database no banco.
- apos isso rode o comando php artisan migrate --seed.
- Irá criar 3 usuarios, admin@admin.com, leitor@leitor.com, revisor@revisor.com. Todos com a senha padrao 123456.
- O sistema consiste em tratar esses 3 niveis de usuario no painel admin.