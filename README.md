# conversao-temperatura

Este projeto é um desafio do curso Kubedev.

Está criado um arquivo Dockerfile para criar a imagem.

Executar o comando para criar a imagem:
docker build -t conv-temp .
- usar outro nome no lugar de conv-temp se desejar

Executar o comando para criar o container:
docker container run -d -p 8080:8080 conv-temp:latest 

Abrir um navegador e digitar
http://localhost:8080

A aplicação estará rodando
