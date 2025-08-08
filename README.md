# Projeto Laravel - Alunos

Este projeto foi criado com o framework **Laravel 12**, utilizando o banco de dados **MySQL**. Ele tem como objetivo o gerenciamento de uma tabela chamada `alunos`.

---

## ✅ Pré-requisitos

- PHP (versão 8.1 ou superior)
- Composer instalado
- MySQL instalado e rodando
- Editor de código (recomendado: VS Code)
- Git (para versionamento)

---

## 📦 Instalação do Laravel

### 1. Criando o projeto Laravel

Navegue até a pasta do seu servidor (ex: `htdocs` no XAMPP) e execute o comando:

```bash
composer create-project laravel/laravel LaravelAlunos
```
<img width="634" height="84" alt="image" src="https://github.com/user-attachments/assets/108da07c-8ae4-4a94-b2ab-f05f3d55e6c9" />


### 2. Acessando o projeto
```bash
cd LaravelAlunos
```

### 3. Configuração do banco de dados
Crie um banco de dados no MySQL com o nome alunos_db e configure o arquivo .env do projeto com as credenciais:
``` bash
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=alunos_db
DB_USERNAME=root
DB_PASSWORD=
```

### 4.  Criando a Migration da tabela alunos
```bash
php artisan make:migration create_alunos_table
```

### 5. Rodando a Migration
```
php artisan migrate
```
<img width="725" height="47" alt="image" src="https://github.com/user-attachments/assets/5f6e3320-fa73-45f8-aaff-b27d4a8a2f34" />




