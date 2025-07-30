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

Acessar o diretório da ferramenta a ser implantada (exemplo):
```
cd docker-compose-recipes/apache-php
```

Iniciar os containers
```
docker-compose up -d
```

## Lista de Ferramentas


* [**apache-php**](https://github.com/leomanfredini/docker-compose-recipes/tree/main/apache-php) - Servidor web Apache com suporte a PHP.
* [**apache-php-ssl**](https://github.com/leomanfredini/docker-compose-recipes/tree/main/apache-php-ssl) - Servidor web Apache com suporte a PHP e HTTPS.
* [**metube**](https://github.com/leomanfredini/docker-compose-recipes/tree/main/metube) - Interface web para o yt-dlp (um fork do youtube-dl), que permite baixar vídeos e áudios de diversas plataformas, como YouTube, de forma simples e personalizável.
* [**nginx-proxy-manager**](https://github.com/leomanfredini/docker-compose-recipes/tree/main/nginx-proxy-manager) - Facilita a configuração e gerenciamento de proxies reversos, redirecionamentos, certificados SSL e hosts com o Nginx. 
* [**paperless-ngx**](https://github.com/leomanfredini/docker-compose-recipes/tree/main/paperless-ngx) - Sistema de gerenciamento de documentos auto-hospedado que digitaliza, organiza e permite a busca eficiente de arquivos digitalizados por meio de OCR.
* [**tinyfilemanager**](https://github.com/leomanfredini/docker-compose-recipes/tree/main/tinyfilemanager) - Gerenciador de arquivos baseado na Web em PHP. É um gerenciador de arquivos simples, rápido e pequeno com um único arquivo. 
* [**upsnap**](https://github.com/leomanfredini/docker-compose-recipes/tree/main/upsnap) - Permite ativar remotamente dispositivos na rede local utilizando Wake-on-LAN (WOL), com suporte a agendamento de eventos e interface web para gerenciamento.
* [**uptime-kuma**](https://github.com/leomanfredini/docker-compose-recipes/tree/main/uptime-kuma) - ferramenta para monitorar sites, aplicativos e monitorar também serviços através de HTTP/S, TCP, DNS, e alguns outros protocolos.


