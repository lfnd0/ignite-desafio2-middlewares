# Rocketseat :rocket:

## Ignite – Trilha Node.js

### Desafio 2 – Trabalhando com *middlewares* (ToDos API)

#### :computer: Descrição
Esta é uma API para gerenciar tarefas (em inglês *todos*), em que é permitida a criação de um usuário com `name` e `username` bem como fazer o CRUD (*Create*, *Read*, *Update* *and* *Delete*) de *todos*. Neste projeto são trabalhados os *middlewares* da API.

#### :hammer_and_wrench: Funcionalidades
- Criar um novo *todo*.
- Listar todos os *todos*.
- Alterar o `title` e `deadline` de um *todo* existente.
- Marcar um *todo* como feito.
- Excluir um *todo*.

#### :link: Rotas
- POST `/users`: cria um novo usuário.
- GET `/todos`: retorna uma lista com os *todos* de um usuário.
- POST `/todos`: cria um novo *todo*.
- PUT `/todos/:id`: atualiza o `title` e o `dealine` de um *todo*.
- PATCH `/todos/:id/done`: finaliza o `done` de um *todo*.
- DELETE `/todos/:id`: remove um *todo*.

#### :memo: Execução da API
- Instalação das dependências:
  > yarn

- Execução da API:
  > yarn dev

- Execução dos testes:
  > yarn test
