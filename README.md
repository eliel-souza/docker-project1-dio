# Curso Docker Projeto 1

**Criando um Container de uma Aplicação WEB**

Neste projeto foi utilizado o Docker Compose para executar uma aplicação HTML em um Container Apache.

Para isso, tinhamos algumas definições:

1. Criar um arquivo YML com as definições de um servidor apache (httpd);
2. Especificar no arquivo YML o local onde os arquivos da aplicação estarão. A aplicação pode ser um simples Hello World.
3. Subir o arquivo YML e a aplicação para um repositório no GitHub;


**Rodando a Aplicação**

```bash

# Iniciar o container
$ docker-compose up

# Remover o container
$ docker-compose down

```
