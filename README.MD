# Ambiente de desenvolvimento em docker PHP + MYSQL + PHPMYADMIN


## 1. Conteúdo do Projeto

| 📂 AMBIENTE PHP (raiz)    	|                                                  	|
|---------------------	|--------------------------------------------------	|
| 📁 phpdocker        	| - Contem as conf. do nginx  e php              	|
|                     	|                                                  	|
| 📁 Public          	|  - pasta para o seu projeto                    	|
|                     	|                                                  	|
| 📄docker-compose.yml 	| - Arquivo para configuração do Docker.           	|
|                     	|                                                  	|
| 📄.env               	| Variáveis e de ambiente                          	|


## 2. O que contem ao certo aqui?
* Um ambiente de desenvolvimento em php+mysql+phpmyadmin pronto para seu trabalho

## 3. Instalação

OS X - Linux - Windows:

✅ primeiro você precisa ter o docker instalado, caso não tenha acesse esse link e siga o passo a passo: https://docs.docker.com/get-docker/

✅ Faça download do Repositório ou clone com seu git

🖊️ agora na raiz de nosso projeto digite em seu terminal ou no prompt caso esteja no windows:

```sh
docker-compose build 
```
🖊️ Feito isso a build de nosso projeto está pronta para ser executada então agora digite em seu terminal ou no prompt caso esteja no windows:

```sh
docker-compose up -d
```

## 4. Como usar

Com isso o nginx deverá abrir seu projeto em:


```sh
http://localhost:80
```
🖊️ phpmyadmin

```sh
http://localhost:8080
```

Caso queira alterar as portas use o .env, eu sempre uso por questões de segurança é bem fácil configurar as senhas e tudo mais por meio dele.
dúvidas, estou a disposição um abraço.





## Autor

🧑🏻‍💻 Elvis Gonçalves
elvisgoncalves@outlook.com
(94) 992615575

[npm-image]: https://img.shields.io/npm/v/datadog-metrics.svg?style=flat-square
[npm-url]: https://npmjs.org/package/datadog-metrics
[npm-downloads]: https://img.shields.io/npm/dm/datadog-metrics.svg?style=flat-square# ambiente-php
