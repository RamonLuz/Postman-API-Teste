# 🧪 Testes da API - Livrotech

Este diretório contém a coleção do **Postman** utilizada para validar manualmente os endpoints da API **Livrotech**, garantindo o comportamento esperado em cenários de sucesso e de falha.

## 🔧 Ferramenta Utilizada

* Postman

## 📁 Arquivos

### `APIs.postman_collection.json`

Coleção contendo todos os endpoints da aplicação:

* 📚 Books
* 👥 Customer
* 👨‍💼 Employee
* 🛒 Sales

### `APIs.postman_environment.json`

Arquivo com as variáveis de ambiente utilizadas durante a execução dos testes.

---

## 📚 Books

### Cenários de Sucesso

* Criar livro
* Buscar livro por ID
* Listar livros
* Atualizar livro
* Remover livro

### Validações

* Livro duplicado
* Preço inválido
* Body vazio
* Campos obrigatórios não preenchidos

---

## 👥 Customer

### Cenários de Sucesso

* Criar cliente
* Buscar cliente por ID
* Listar clientes
* Atualizar status do cliente
* Remover cliente

### Validações

* CPF duplicado
* CPF inválido
* Body vazio
* ID inválido

---

## 👨‍💼 Employee

### Cenários de Sucesso

* Criar funcionário
* Buscar funcionário por ID
* Listar funcionários

### Validações

* CPF inválido
* Body vazio

---

## 🛒 Sales

### Cenários de Sucesso

* Registrar venda
* Buscar venda por ID
* Listar vendas

### Validações

* Cliente inexistente
* Funcionário inexistente
* Livro inexistente
* Body vazio

---

## 📊 Status dos Testes

| Módulo   | Situação    |
| -------- | ----------- |
| Books    | ✅ Concluído |
| Customer | ✅ Concluído |
| Employee | ✅ Concluído |
| Sales    | ✅ Concluído |

---

## 🎯 Objetivo

Garantir a qualidade e a confiabilidade dos endpoints da API, validando cenários positivos e negativos por meio de testes manuais realizados no Postman.
