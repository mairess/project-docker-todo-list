# <p align="center">Projeto Docker Todo-List</p>

## Contexto

O objetivo desse projeto é realizar a `conteinerização` de uma aplicação full-stack de gerenciamento de tarefas, uma to-do list. A infraestrutura é composta por front-end, back-end e um aplicativo de teste para validar a comunicação entre eles. A tarefa inclui a criação de arquivos de configuração `Dockerfile` específicos, garantindo a `orquestração` entre as partes e a criação de comandos de CLI do docker. Todos os comandos criados estão no diretório `./docker/docker-commands`.

<details>

<summary><strong>Rode o projeto conteinerizado</strong></summary><br>

> ⚠️ É preciso ter o [Docker](https://www.docker.com/get-started/) instalado em sua máquina.

> ⚠️ É preciso ter o [Node](https://nodejs.org/en) instalado em sua máquina.

Clone o repositório:

```JSON
git clone git@github.com:mairess/project-docker-todo-list.git
```

O `docker compose` está em `project-docker-todo-list/docker` é preciso entrar nesse diretório:

```JSON
cd docker
```

Suba o container:

```JSON
docker compose up -d
```

O front estará disponível na porta `3000`:

```HTML
http://localhost:3000
```

O back estará disponível na porta `3001`:

```HTML
http://localhost:3001/tasks
```

</details>

## Competências desenvolvidas

- Compreensão e utilização de `docker-compose`.
- Compreensão e utilização de `dockerfile`.
- Compreensão e utilização de `comandos docker`.
- Compreensão de `orquestração de containers`.
