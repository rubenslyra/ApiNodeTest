# AppLogin v1.0.0 | Criação 🔨

## Descrição

O projeto é composto por uma Api — que gerencia os serviços, conexão com banco, repositórios, etc — e uma aplicação (appClient) que consome os serviços da Api.

Na versão **1.0.0**, o projeto será construído de maneira rudimentar, não considerando os princípios do S.O.L.I.D.

A partir da versão **2.0.0**, o projeto deve ser estrutura com testes, domínio principal, subdomínio, repositórios, interfaces e um ORM.

A versão **3.0.0-release**, além de microsserviços, deve apresentar, também, uma Api Gateway, Load Balancer e containers.

## Base do projeto

- backend:
  - api/
- frontend:
  - appClient/

## Pacotes:

Servidor node:

- npm i express --save

Para rodar o projeto em tempo real:

- npm i nodemon --save

Para evitar problemas de requisições por origens diferentes:

- npm i cors --save

## Versionamento

Para controle de versão, commits, features, etc, será utilizado Git-Flow e Conventional Commits.

### Padrão de commit

Os commits deve seguir a referência do Conventional Commits, composta por:

    <tipo>[escopo opcional]: <descrição>
    [corpo opcional]
    [rodapé opcional]

Obervações:

- o tipo deve ser claro e seguir o padrão proposto pelo Conventional Commits;
- a descrição deve começar com um verbo no imperativo;
- o Body e o Footer são opcionais neste projeto.

### Release

A release deve ser entregue atendendo aos seguintes requisitos:

- deve ser multiplataforma;
- deve apresentar a versão do node necessária para o build;
- deve apresentar as mudanças ocorridas e os impactos em versões anteriores;
- deve ser revisada e fechada por agente de gerenciamento do projeto.

Referências:

- [Conventional Commits Pattern, Victor Ribeiro](https://medium.com/linkapi-solutions/conventional-commits-pattern-3778d1a1e657)

- [How to Write a Git Commit Message](https://cbea.ms/git-commit/#imperative)

- [Conventional Commits](https://www.conventionalcommits.org/pt-br/v1.0.0-beta.4/#especifica%C3%A7%C3%A3o)

- [Git Flow: entenda o que é, como e quando utilizar](https://www.alura.com.br/artigos/git-flow-o-que-e-como-quando-utilizar)

- [✨Git Commit message Emoji🔖](https://gist.github.com/parmentf/035de27d6ed1dce0b36a)
