


# crud-produtos

Descrição do Projeto
Este projeto é um sistema CRUD (Create, Read, Update, Delete) desenvolvido em Laravel para gerenciar produtos. Ele permite que usuários façam o cadastro, visualização, edição e exclusão de produtos de forma fácil e rápida, por meio de uma interface web simples e intuitiva.


# CRUD Produtos Laravel

Aplicação Laravel simples para gerenciar produtos com as operações de criar, listar, editar e excluir.

---

## Requisitos

- PHP 8.0 ou superior  
- Composer  
- Banco de dados MySQL ou MariaDB  
- Laravel 10 (compatível com PHP 8)  
- (Opcional) Node.js e npm para compilar assets, caso queira customizar frontend

---

## Como rodar o projeto

### 1. Clonar o repositório

```bash
git clone https://github.com/lazarosena/crud-produtos
cd seu-repositorio

_____________________
2. Instalar dependências PHP

bash

composer install


_____________________
3. Configurar o arquivo .env

Copie o arquivo de exemplo e configure o banco de dados:

bash

cp .env.example .env

Abra .env e ajuste as variáveis abaixo com suas credenciais:

ini

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=nome_do_banco
DB_USERNAME=seu_usuario
DB_PASSWORD=sua_senha


_____________________
4. Gerar a chave da aplicação
bash

php artisan key:generate


_____________________
5. Rodar as migrations
bash

php artisan migrate


_____________________



_____________________

Funcionalidades
Listar produtos

Criar novos produtos (nome, preço, descrição)

Editar produtos

Excluir produtos

Validação básica dos campos

Interface simples com Bootstrap


