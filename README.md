# Docker Todo List
> Criação e orquestração de containers com Docker.

## 💻 Projeto

"Conteinerização" de aplicações de frontend, backend e testes com o uso de Docker, criando uma conexão entre elas e orquestrando seu funcionamento.

## 🚀 Tecnologias
> Este projeto foi desenvolvido com as seguintes tecnologias:

- Bash
- Docker

## 📌 Habilidades

> Neste projeto, desenvolvi as seguintes habilidades:

- Usar comandos Docker na CLI;
- Criar imagens Docker de aplicações;
- Criar e executar contêineres Docker;
- Orquestrar contêineres utilizando o Docker Compose.

## ⬇️ Instalando dependências

```bash
npm install
cd docker
``` 

## ⚡ Executando a aplicação

Inicialmente fazemos o build das imagens de back-end, front-end e testes:
```bash
docker image build -t todobackend ./todo-app/back-end
docker image build -t todofrontend ./todo-app/front-end
docker image build -t todotests ./todo-app/tests
``` 
Então subimos e orquestramos os containers:

```bash
docker-compose up -d
``` 
Para executar a aplicação, basta acessar o endereço http://localhost:3000 no browser.

## 🧪 Executando os testes

Para rodar os testes:

```bash
docker attach docker_todotests_1
```
## 💬 Contatos

<div align="center" style="display: inline_block">
  <a href="https://www.linkedin.com/in/lucas-da-cunha-moreti/" target="_blank"><img height="28rem" src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a> 
  <a href = "mailto:lucasdacunha00@gmail.com"><img height="28rem" src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
</div>
