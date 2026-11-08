# Banco de Dados 1 — Exercício DQL: Banco `mercado`

Repositório com a resolução da atividade prática da disciplina **Banco de Dados 1**, desenvolvida utilizando **PostgreSQL** e **pgAdmin 4**. O exercício consiste na configuração do ambiente de banco de dados, criação e população do banco `mercado` por meio de scripts SQL fornecidos e resolução de questões utilizando consultas DQL (Data Query Language).

## Identificação

| Campo | Informação |
|---|---|
| **Aluno** | Theo de Melo Xavier |
| **RA** | 22650114 |
| **Curso** | Engenharia de Software |
| **Instituição** | CEUB — Campus Asa Norte |
| **Disciplina** | Banco de Dados 1 |
| **Professor(a)** | Pedro Henrique |
| **Data de entrega** | 07/11/2026 |
| **GitHub** | [@devxaviier](https://github.com/devxaviier) |

## O que foi feito

1. Instalação e configuração do PostgreSQL no computador.
2. Configuração do servidor PostgreSQL 18 no pgAdmin 4.
3. Criação do banco de dados `mercado`.
4. Execução do script SQL fornecido na atividade, responsável pela criação e população das tabelas.
5. Verificação da criação das tabelas e dos registros inseridos no banco de dados.
6. Desenvolvimento de consultas DQL para responder às questões propostas no exercício.
7. Organização das consultas em um único arquivo SQL, identificado por comentários para cada questão.
8. Publicação do arquivo `dql_parte1.sql` no GitHub utilizando Git pelo terminal do Windows.

## Estrutura do repositório

```text
ExercicioDB_1/
├── README.md
└── dql_parte1.sql
```

## Como reproduzir

**Requisitos:** PostgreSQL 18, pgAdmin 4 e Git instalados.

1. Instale o PostgreSQL e o pgAdmin 4.
2. Abra o pgAdmin 4 e conecte-se ao servidor PostgreSQL.
3. Crie um banco de dados com o nome `mercado`.
4. Selecione o banco `mercado` e abra o Query Tool.
5. Execute o script SQL fornecido na atividade, responsável pela criação das tabelas e inserção dos dados.
6. Verifique se as tabelas foram criadas e se os dados estão disponíveis.
7. Abra o arquivo `dql_parte1.sql` e execute as consultas individualmente para visualizar os resultados.

## Resolução do exercício

As consultas desenvolvidas estão organizadas no arquivo [`dql_parte1.sql`](dql_parte1.sql).

O arquivo contém as questões identificadas por comentários SQL, facilitando a localização e a execução de cada consulta.

Entre os conteúdos trabalhados estão:

- Contagem de registros e identificação de valores nulos.
- Contagem de valores distintos.
- Cálculo de faturamento e médias.
- Filtragem de informações com `WHERE`.
- Agrupamento de dados com `GROUP BY`.
- Aplicação de condições com `HAVING`.
- Ordenação de resultados com `ORDER BY`.
- Utilização de funções agregadoras como `COUNT`, `SUM` e `AVG`.
- Limitação de resultados com `LIMIT`.
- Análise de informações relacionadas a clientes, produtos, lojas e vendas.

## Tecnologias utilizadas

- **SQL** — Linguagem de consulta ao banco de dados.
- **PostgreSQL 18** — Sistema gerenciador de banco de dados relacional.
- **pgAdmin 4** — Ferramenta de administração e execução de consultas.
- **Git** — Sistema de controle de versão.
- **GitHub** — Plataforma de hospedagem do repositório.

## Contato

**Theo de Melo Xavier**

GitHub: [@devxaviier](https://github.com/devxaviier)

LinkedIn: [in/theoxaviier](https://www.linkedin.com/in/theoxaviier)
