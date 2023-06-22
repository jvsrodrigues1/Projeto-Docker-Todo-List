# Boas vindas ao repositório do projeto <b>Docker Todo-List</b>!

Esse projeto foi desenvolvido durante o módulo de Backend na Trybe! #vqv 

Aqui você vai encontrar os detalhes de como foi o desenvolvimento do projeto e quais foram os requisitos técnicos necessários para a entrega do desafio.

---

# Habilidades desenvolvidas

Neste projeto, fui capaz de:

- Conteinerizar aplicações;
- Criar uma conexão entre elas;
- Orquestrar seu funcionamento.

---

# Funcionamento da aplicação

Para iniciar o projeto, é necessário possuir o [Docker](https://docs.docker.com/engine/install/ubuntu/) instalado.

Após clonar o projeto em seu computador, para iniciá-lo é necessário executar o comando
```
cd docker && docker-compose up -d && cd todo-app/front-end && npm install && npm start
```

na pasta raíz do projeto. Isso fará com que os containers docker sejam orquestrados e a aplicação esteja disponível.

O projeto trata-se de um desafio para consolidar o aprendizado com os comandos básicos de Docker e criação de container, bem como a criação de Dockerfiles para montar imagens e a utilização de Docker-compose para orquestrar esses Dockerfiles de forma a subir uma aplicação inteira com Docker totalmente containerizada! Para isso, o frontend (disponibilizado pela Trybe) conta uma Lista de Tarefas em que você pode adicionar, editar e remover tarefas!

---
