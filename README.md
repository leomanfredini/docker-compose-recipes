# Docker Compose Recipes

Lista de "receitas" para deploy de ferramentas via *docker compose*.

## Requisitos

Docker and Docker Compose rodando em um sistema Linux.

> Guia para instalação em um sistema Debian Linux: [https://www.manfredini.net.br/posts/docker-compose-portainer/](https://www.manfredini.net.br/posts/docker-compose-portainer/)

## Uso

Clonar o repositório
```
git clone https://github.com/leomanfredini/docker-compose-recipes.git
```

Acessar o diretório da ferramenta a ser implantada
```
cd docker-compose-recipes/apache-php
```

Iniciar os containers
```
docker-compose up -d
```