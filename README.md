# Docker Compose com WordPress, MariaDB e phpMyAdmin
Docker Compose para Desenvolvedores(as) WordPress. 
Este repositório visa facilitar / agilizar na criação do ambiente de desenvolvimento com WordPress utilizando o Docker e o Docker Compose. 
Com apenas um comando simples, você criará todo um ambiente de desenvolvimento baseado em WordPress e com a possibilidade de fazer o upload dos Temas, Plugins e Imagens até **256mb** sem precisar mexer no **.htaccess** ou no **php.ini**

## Mini Tutorial (Informações Importantes)
- Necessário ter o **Docker** instalado na sua máquina.
- Necessário ter o **Docker Compose** instalado na sua máquina.
- Necessário colocar os arquivos: **uploads.ini** & **docker-compose.yml** na pasta raiz do seu projeto.
- Na pasta raiz do seu projeto, executar o comando: `docker-compose up -d`
- Logo depois, aguarde as imagens do **WordPress**, **MariaDB** e **phpMyAdmin** serem baixadas.
- Por fim, aguarde os containers subirem.

Após a subida dos containers, poderá iniciar a instalação do WordPress na porta **8000**:
- **127.0.0.1:8000** ou **localhost:8000**

Após a instalação do WordPress, poderá acessar o phpMyAdmin na porta **10777**:
- **127.0.0.1:10777** ou **localhost:10777**

Para subir, descer e reiniciar os containers: 
- Subir os containers: `docker-compose up -d`
- Reiniciar os containers: `docker-compose down && docker-compose up -d`
- Descer os containers: `docker-compose down`

Para conferir as portas e o nome de cada container, poderá utilizar o comando `docker ps`. Caso tenha alguma sugestão ou dificuldade entre em contato comigo via:
- Issues: https://github.com/Dev-Flaubert-Wordpress/docker-wordpress-padronizado/issues
- Linkedin: https://www.linkedin.com/in/flaubert-dev/

Que este simples repositório possa lhe ajudar de alguma forma em algum momento da sua carreira como Desenvolvedor(a).
