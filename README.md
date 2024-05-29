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

## Arquivo `app.py`

Contém a aplicação Flask que define as rotas e a lógica para as operações CRUD de tarefas.

## Arquivo `models/task.py`

Define a classe `Task`, que representa uma tarefa e possui métodos para converter a tarefa em um dicionário.

## Arquivo `test.py`

Contém testes para a API utilizando pytest e requests.

## Como Executar

### Pré-requisitos

- Python 3.x
- Flask
- Requests
- Pytest

### Clonando o Repositório

```bash
git clone https://github.com/seu_usuario/task-manager.git
```

