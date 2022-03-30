# Nova Vision

## Descrição

- ![Logo Victor 3D](./docs/assets/victor_3d.png)

Desenvolvimento de um sistema CRUD para solitações de serviços na empresa Nova Vision.

- Visão geral do projeto

- ![Visão geral do projeto]()

## Tecnologias utilizadas

### Arquitetura do projeto

#### Stack de desenvolvimento

- Versionamento
    - Possibilidade 00
        1. Git.

- Conteinerização do ambiente de desenvolvimento
    - Possibilidade 01
        1. Docker.
        1. Docker-Compose.

    - Possibilidade 02
        1. Podman (apenas para Linux).
        1. Shell Script.

- Sistema de gerenciamento de banco de dados
    - Possibilidade 01
        1. MySQL.

    - Possibilidade 02
        1. PostgreSQL (PGAdmin 4).

- Backend
    - Possibilidade 01
        1. Java JDBC.

    - Possibilidade 02
        1. Java SpringBoot.

    - Possibilidade 03
        1. TypeScript Sequelize.

- Frontend
    - Possibilidade 01
        1. NextJS, TypeScript e Styled-Components.

    - Possibilidade 02
        1. NextJS, JavaScript e Styled-Components.

    - Possibilidade 03
        1. HTML, CSS (Bootstrap) e JavaScript.

- Automação da qualidade de software
    - Possibilidade 01
        1. Python.

- Gerenciamento do progresso de features
    - Possibilidade 01
        1. JIRA

    - Possibilidade 02
        1. Trello

#### Stack de produção

- Servidor de dados
    - Possibilidade 01
        1. ???

    - Possibilidade 02
        1. ???

- Servidor de hospedagem
    - Possibilidade 01
        1. [Netlify](https://www.netlify.com/).

    - Possibilidade 02
        1. [Vercel](https://vercel.com/).

    - Possibilidade 03
        1. [Byet Host](https://byet.host/).

    - Possibilidade 04
        1. [WebHost](https://www.000webhost.com/).

## Organização do projeto

### Git

- Git branches

|Nome                   |Descrição
|---                    |---
|Main                   |Versão estável do sistema
|development_backend    |Desenvolvimento do backend
|development_frontend   |Desenvolvimento do frontend
|planning               |Esboço do projeto
|testing                |Verificação de erros

- Ciclo de vida do desenvolvimento do projeto

- ![](./docs/assets/)

### Banco de dados

#### Esquema do banco de dados

- tabela_usuario

|???    |???        |???
|---    |---        |---
|PK, AI |Number     |id
|-      |String     |nome
|-      |String     |sobrenome
|-      |String     |data_nascimento
|-      |Timestamp  |data_cadastro

- tabela_orcamento

|???    |???    |???
|---    |---    |---
|PK, AI |Number |id
|-      |String |servico
|-      |Number |preco
|-      |Number |desconto_a_vista
|-      |String |descricao

- tabela_pedido

|???    |???    |???
|---    |---    |---
|PK, AI |Number |id
|FK     |Number |id_usuario
|FK     |Number |id_orcamento

#### Relacionamento das tabelas do banco de dados

- ![Relacionamento normalizado das tabelas](./docs/assets/)

## Equipe de desenvolvedores

- Quadro de desenvolvedores e suas respectivas responsabilidades

|Membros            |Responsabilidade atribuída
|---                |---
|Guilherme Carini   |Automação do teste de software
|Gustavo Scarpim    |Desenvolvimento do frontend
|Henrik Beck        |Desenvolvimento do backend
|Micael Trivelato   |Desenvolvimento do backend
|Victor H. Ranalli  |Engenharia de software