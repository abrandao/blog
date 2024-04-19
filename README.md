# A simple blog platform

## Stack
 - Docker
 - Ruby on Rails 
 - HTML + CSS + JS + Bootstrap
 - PostgreSQL

## Arquitetura
  - Monolito

## Features

  - Área deslogada onde é possível: 

    1.  Ver os posts publicados por todos os usuários ordenados do mais novo para o mais antigo
    2.  Os posts publicados devem ter paginação ao atingirem 3 publicações, onde o 4º post irá para a página 2 e daí em diante, ou seja, cada página deverá ter até 3 posts
    3.  Fazer comentários anônimos
    4.  Cadastrar um novo usuário
    5.  Fazer login com um usuário cadastrado
    6.  Recuperar a senha do usuário
    7.  Área logada onde é possível: redigir e publicar um post
    8.  Editar e apagar posts já publicados pelo próprio usuário loggado
    9.  Fazer comentários identificados através do login
    10. Editar o seu cadastro de usuário
    11. Alterar a senha do usuário loggado

  - Opcionais:
    1. Se conseguir, escrever testes automatizados simples;
    2. Se conseguir, implemente internacionalização;
    3. Se conseguir, adicione tags aos seus post, assim como filtros para utilizar as tags cadastradas. As tags deverão ser implementadas como uma nova tabela no seu modelo, associada aos posts;

  - SUPER DIFERENCIAL:
  1. Se conseguir, crie a possibilidade de upload de arquivo TXT para criação de um ou mais posts, ou criação de múltiplas tags, utilizando Sidekiq para processamento assíncrono.
  2. Quanto a infra-estrutura, a sua aplicação deve estar publicada no Fly.io e seu código deve estar acessível em sua conta do Github. Não iremos considerar a entrega de uma aplicação que não esteja publicada e de um código que não esteja no Github, de modo que possamos avaliar a evolução do seu código, ou seja, não aceitaremos a entrega funcionando apenas em Localhost. 

  > Caso não esteja habituado com o Fly.io (https://fly.io/), segue link para o tutorial de utilização do mesmo com Rails: https://fly.io/docs/rails/

  # README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
