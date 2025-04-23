# AlgaComments

O **AlgaComments** é um sistema distribuído baseado em microsserviços com o objetivo de gerenciar comentários de usuários de forma moderada e segura. Ele permite o envio de comentários, realiza a validação de conteúdo com base em regras pré-estabelecidas e armazena apenas os comentários aprovados.

Este projeto foi idealizado para promover uma experiência de moderação eficiente, garantindo que apenas conteúdos adequados sejam armazenados e exibidos em sistemas que dependam de interações textuais dos usuários.

## Estrutura do Projeto

O sistema é composto por dois microsserviços distintos, organizados como submódulos neste repositório principal:

- 🔗 [CommentService](https://github.com/cadugr/comment-service)  
  Responsável por receber, moderar e armazenar comentários aprovados.

- 🔗 [ModerationService](https://github.com/cadugr/moderation-service)  
  Responsável por validar o conteúdo dos comentários, identificando textos inadequados com base em uma lista fixa de palavras proibidas.

Cada microsserviço possui seu próprio repositório com código-fonte, instruções de execução e testes específicos. O repositório principal tem o propósito de unificar e representar o sistema como um todo.

## Sobre o Projeto

Este projeto foi desenvolvido por Carlos Eduardo Guerra Resende como parte de um desafio proposto no curso **Especialista Spring REST e Microsserviços** da [Algaworks](https://algaworks.com). Ele representa a aplicação prática dos conhecimentos adquiridos no Nível 1 do curso sobre arquitetura de microsserviços, comunicação síncrona e boas práticas com Spring Boot.

---
