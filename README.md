# Desafio 1 - Iniciativa DevOps - Docker


Aplicação node.js

Passos realizados 

- Criar DockerFile

- docker build -t patriciapadilha/conversao-temperatura:v1 .

- docker container run -d -p 8080:8080 patriciapadilha/conversao-temperatura:v1

- docker container ls

- Acessar localhost 8080 - Rodando


- docker login

- docker push patriciapadilha/conversao-temperatura:v1

- docker tag patriciapadilha/conversao-temperatura:v1 patriciapadilha/nconversao-temperatura:latest

- docker push patriciapadilha/conversao-temperatura:latest

Para testar:
- remover images e contaeiner

Rodando container usando a imagem criada
- docker container run -d -p 8080:8080 patriciapadilha/conversao-temperatura:v1
