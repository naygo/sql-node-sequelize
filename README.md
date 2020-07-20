# SQL no Node.js com Sequelize
#### Rocketseat - Masterclass #01



## Níveis de abstração
>Formas de se comunicar com o banco de dados

+ 1º nível: **Postgres**
    - querys dentro do banco de dados
+ 2º nível: **Knex**
    - query builder
    - suporte para as **_migrations_**
        - _migrations:_ como o banco de dados vai se comportar em tempo de vida da aplicação 
    - Histórico de dados
+ 3º nível: **Sequelize**
    - ORM para escrever menos código
    - define models
    - tem um query builder por baixo dos panos
    - **_sequelize-cli_**: interface de linha de comandos


+ yarn sequelize db:create 
+ yarn sequelize migration:create --name=create-nomeTabela
+ yarn sequelize migration:create --name=add-nomeColuna-field-to-nomeTabela
+ yarn sequelize db:migrate
+ yarn sequelize db:migrate:undo
+ yarn sequelize db:migrate:undoall 
