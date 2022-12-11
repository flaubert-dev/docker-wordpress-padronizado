# Docker Compose para Desenvolvedores(as) WordPress
Este repositório visa facilitar (agilizar) na criação do ambiente de desenvolvimento com WordPress utilizando o Docker e o Docker Compose.

## (!) Importante
1. Necessário ter o **Docker** instalado na sua máquina.
2. Necessário ter o **Docker Compose** instalado na sua máquina.
3. Necessário colocar os arquivos: **uploads.ini** & **docker-compose.yml** na pasta raiz (root) do seu projeto.
4. Na pasta raiz (root) do seu projeto, executar o comando: 
```shell
docker-compose up -d 
```
5. Logo depois, aguarde as imagens do **WordPress**, **MariaDB** e **phpMyAdmin** serem baixadas.
6. Por fim, aguarde os containers subirem.

## Após a subida dos containers

Para iniciar a instalação do WordPress acesse a porta *8000*:

- **127.0.0.1:8000** ou **localhost:8000**

## Após a instalação do WordPress

Poderá acessar o phpMyAdmin na porta *10777*:

- **127.0.0.1:10777** ou **localhost:10777**

## Subir, reiniciar ou descer os containers

1. Subir os containers:
```shell
docker-compose up -d
```
2. Reiniciar os containers:
```shell
docker-compose down && docker-compose up -d
```
3. Descer os containers:
```shell
docker-compose down
```

## Conferir as portas e o nome de cada container

Poderá utilizar o comando:

```shell
docker ps
```

## Dicas e Sugestões

Caso tenha alguma dica ou sugestão entre em contato:

- Issues: https://github.com/Dev-Flaubert-Wordpress/docker-wordpress-padronizado/issues
- Linkedin: https://www.linkedin.com/in/flaubert-dev/

Que este simples repositório possa lhe ajudar de alguma forma na sua carreira como Desenvolvedor(a).
