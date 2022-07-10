# SQL
Uso este repositório para salvar comandos e explicações sobre SQL

## Definições

- **Banco de dados**: Conjunto de tabelas onde possui uma certa quantidade de dados
- **Primary Key**: Chave primária e única de uma tabela
- **Foreign Key:** Chave estrangeira
- **Indice**: Ordenação de dados
- **View**: Agrupamento de tabelas
- **Procedures:** Função dentro do ambiente SQL
- **Trigger**: Alerta de erro ou ação

## Criação de um banco de dados

- **Estrutura**
    
    **CREATE DATABASE** NOME
    

## Deletando um banco de dados

- **Estrutura**
    
    **DROP DATABASE** NOME
    

## Selecionando dados

- **Estrutura**
    
    **SELECT** COLUNAS **FROM** TABELA
    
    Os itens sublinhados precisam ser descritos de acordo com o banco de dados que está sendo acessado
    
    - Dando nome aos campos
        
        **SELECT** COLUNA **AS** NOME **FROM** TABELA
        
    

## Tipos de dados

- Int
- Float
- Double
- Bit (0,1)
- Date (aaaa-mm-dd)
- Datetime (aaaa-mm-dd hh:mm:ss)
- Char(4) - (’aa’) → (’  aa’)
- Varchar(4) - (’aa) → (’aa”)
- Binary
- Text
- E-num

## Inserindo dados na tabela

- Estrutura
    
    I**NSERT INTO TABELA** (COLUNAS) **VALUES** (VALORES)
    

## Deletando dados da tabela

- Estrutura
    
    **DELETE FROM** TABELA **WHERE** PK
    

## Alterando registros

- Estrutura
    
    **UPDATE** TABELA **SET** COLUNA =  VALOR **WHERE** *PK*
    

## Primary Key

- Estrutura
    
    **ALTER TABLE** TABELA **ADD PRIMARY KEY** (COLUNA);
    

## Where

- Estrutura
    
    **SELECT** COLUNA **FROM** TABELA **WHERE** COLUNA = VALOR (PODE USAR >, <, =, <>, ≤, ≥
    

## Data

- Estrutura
    
    SELECT COLUNA FROM TABELA WHERE YEAR/MONTH(COLUNA DATA) = ANO/MÊS
    

## Seleção composta

- Estrutura
    
    **SELECT** COLUNA **FROM** TABELA **WHERE** COLUNA CONDIÇÃO **AND/OR** COLUNA CONDIÇÃO
