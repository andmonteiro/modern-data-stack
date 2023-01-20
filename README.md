# modern-data-stack

Repositório para armazenar os artefatos do Pipeline utilizando Modern Data Stack com AirByte + DBT + Airflow + SnowFlake + Metabase

## Tarefas:

### Infraestrutura:

- [x] Setup do ambiente de desenvolvimento (Hardware, Software - Linux, Python, Docker, Curl, Pip, Git, Npm, etc...) 
- [x] Setar as Permissoes do Gitpod ao Repositorio no Github 
- [x] Subir o Airbyte via docker 
- [x] Subir o Airflow via docker 
- [x] Subir o Metabase via docker 
- [x] Criar o script de execução 
- [x] Testar a Execução 

#### Snowflake Data Warehouse:

- [x] Criar a Conta no SnowFlake 
- [x] Verificar a existência das tabelas 
- [x] Obter os links de conexão e nome da conta 

### Extração:

#### No Airbyte:

- [x] Conectar com as origens baseadas nos Csvs 
- [x] Criar as entidades no snowflake através do script base da documentação 
- [x] Conectar o destino no snowflake 
- [x] Criar as conexões do airbyte associando as origens ao destino 
- [x] Testar as conexões 

### Preparação:

#### No Airbyte (Destination Loading Method):

- [x] Local Staging (Ambiente de Desenvolvimento) 
- [x] Cloud Staging (Ambiente de Produção) 

### Transformação:

#### No Dbt:

- [x] Criação da Conta 
- [x] Conexão com o Github 
- [x] Criação do Dbt Project 
- [x] Criação do Profile de conexão com o snowflake 
- [x] Criação do Schema 
- [x] Criação dos Modelos Base 
- [x] Criação do Modelo Relacionado 
- [x] Visualização gráfica do modelo 
- [x] Teste de execução 
- [x] Commits, Branches, Pull Requests, Merges no Github 
- [x] Obtenção do link de conexão com o Airbyte 

### Orquestração:

#### No Airflow:

- [x] Criar a dag 
- [x] Criar a Docker network 
- [x] Incluir nos composes a network criada 
- [x] Setup Up no serviço 
- [x] Testar a conexao entre os containers do airflow e do airbyte 
- [x] Criar as conexões com o Airbyte através do script 
- [x] Testar a execução do pipeline 

### Visualização:

#### No Metabase:

- Conectar Metabase com o Snowflake
- Criar uma Question
- Criar um Dashboard
- Adicionar uma Question
- Visualizar o Resultado