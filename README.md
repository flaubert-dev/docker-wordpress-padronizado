# Docker Compose p/ Devs WP

Este repositório tem o objetivo de facilitar / agilizar na criação do ambiente de desenvolvimento com WordPress utilizando o Docker e o Docker Compose. Se for utilizar o [Sage 10](https://github.com/roots/sage/tree/v10.7.0), altere o arquivo docker-compose.yml na linha 21 `image: 'wordpress:latest'` para `image: 'wordpress:php8.1'`.
<br/>

## (!) Importante

> 1. Necessário ter o **Docker** instalado na sua máquina.
> 2. Necessário ter o **Docker Compose** instalado na sua máquina.
> 3. Necessário colocar os arquivos: **uploads.ini** & **docker-compose.yml** na pasta raiz (root) do seu projeto.
> 4. Na pasta raiz (root) do seu projeto, executar o comando abaixo:

```shell
sudo docker-compose up -d 
```

> 5. Logo depois, aguarde as imagens do **WordPress**, **MariaDB** e **phpMyAdmin** serem baixadas.
> 6. Por fim, aguarde os containers subirem.

## Após a subida dos containers

> Para iniciar a instalação do WordPress acesse a porta `8000`, exemplo abaixo:<br/>
> `127.0.0.1:8000` ou `localhost:8000`

## Após a instalação do WordPress

> Poderá acessar o phpMyAdmin na porta *10777*, exemplo abaixo:<br/>
> `127.0.0.1:10777` ou `localhost:10777`

## Subir, reiniciar ou descer os containers

> 1. Subir os containers:
```shell
sudo docker-compose up -d
```
> 2. Reiniciar os containers:
```shell
sudo docker-compose down && sudo docker-compose up -d
```
> 3. Descer os containers:
```shell
sudo docker-compose down
```

## Conferir as portas e o nome de cada container

> Poderá utilizar o comando abaixo:

```shell
sudo docker ps
```

## Dicas e Sugestões

Caso tenha alguma dica ou sugestão entre em contato:

- Issues: https://github.com/Dev-Flaubert-Wordpress/docker-wordpress-padronizado/issues
- Linkedin: https://www.linkedin.com/in/flaubert-dev/

Que este simples repositório possa lhe ajudar de alguma forma na sua carreira como Desenvolvedor(a).
