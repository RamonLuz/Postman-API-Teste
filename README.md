🧪 Testes da API - Livrotech

Este diretório contém a coleção Postman utilizada para validação manual e automatizado dos endpoints da API Livrotech.

Ferramenta utilizada
Postman
Arquivos
APIs.postman_collection.json

Coleção contendo todos os endpoints da aplicação:

Books
Customer
Employee
Sales
APIs.postman_environment.json

Variáveis de ambiente utilizadas durante os testes.

Cenários testados
📚 Books
Sucesso
Criar livro
Buscar livro por ID
Listar livros
Atualizar livro
Remover livro
Validações
Livro duplicado
Preço inválido
Body vazio
Campos obrigatórios não preenchidos
👥 Customer
Sucesso
Criar cliente
Buscar cliente por ID
Listar clientes
Atualizar status do cliente
Remover cliente
Validações
CPF duplicado
CPF inválido
Body vazio
ID inválido
👨‍💼 Employee
Sucesso
Criar funcionário
Buscar funcionário por ID
Listar funcionários
Validações
CPF inválido
Body vazio
🛒 Sales
Sucesso
Registrar venda
Buscar venda por ID
Listar vendas
Validações
Cliente inexistente
Funcionário inexistente
Livro inexistente
Body vazio
Status dos testes
Módulo	Situação
Books	✅
Customer	✅
Employee	✅
Sales	✅
Objetivo

Garantir o comportamento esperado dos endpoints da API, validando tanto cenários positivos quanto negativos através de testes manuais realizados no Postman.