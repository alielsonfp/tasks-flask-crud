# Task Manager API

O Task Manager é uma aplicação para gerenciar tarefas, permitindo a criação, leitura, atualização e exclusão de tarefas.

## Funcionalidades

- Criar novas tarefas.
- Visualizar todas as tarefas.
- Visualizar uma tarefa específica por ID.
- Atualizar uma tarefa existente.
- Deletar uma tarefa.

## Requisitos funcionais

- [✔] O usuário deve poder criar uma nova tarefa.
- [✔] O usuário deve poder visualizar todas as tarefas.
- [✔] O usuário deve poder visualizar uma tarefa específica.
- [✔] O usuário deve poder atualizar uma tarefa.
- [✔] O usuário deve poder deletar uma tarefa.

## Regras de negócio

- [✔] O usuário só pode visualizar tarefas existentes.
- [✔] O usuário só pode atualizar ou deletar tarefas existentes.

## Requisitos não-funcionais

- [✔] A aplicação deve responder em um tempo razoável para todas as operações CRUD.
- [✔] A aplicação deve ser testada automaticamente usando pytest.

## Especificações da API

Para detalhes completos das especificações da API, acesse a [documentação Swagger](https://app.swaggerhub.com/apis/AlielsonPequeno/api-de_gerenciamento_de_tarefas/1.0.0#/).

## Banco de dados

Nesta aplicação, as tarefas são armazenadas em memória (lista em Python).
