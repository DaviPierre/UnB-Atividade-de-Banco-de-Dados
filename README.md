# Sistema de Banco de Dados para E-commerce - SBD1

Este repositório contém a modelagem e implementação física de um banco de dados relacional voltado para a gestão de um e-commerce de componentes eletrônicos (focado em fontes e LEDs). O projeto foi desenvolvido para a disciplina de Sistemas de Bancos de Dados 1 da UnB.

## Funcionalidades e Estrutura

O sistema gerencia as principais operações de um e-commerce através das seguintes entidades:

- **Gestão de Clientes:** Armazenamento de dados pessoais, credenciais e endereços.
- **Controle de Estoque (Armazéns):** Monitoramento de capacidade e localização dos centros de distribuição.
- **Catálogo de Produtos:** Registro detalhado de itens com especializações para:
  - **Fontes:** Controle de voltagem e potência.
  - **LEDs:** Especificações de tamanho e cor.
- **Operações Logísticas:** Relacionamento entre fornecedores, armazéns e produtos disponíveis.
- **Vendas e Pedidos:** Vinculação de pedidos entre clientes e produtos adquiridos.

## Conteúdo do Repositório

- `SQL.txt`: Scripts DDL para criação de tabelas e DML para inserção de dados de teste.
- `sqlite.db`: Banco de dados SQLite pronto para uso e consultas.
- `DER.md` e `MER.md`: Documentação da modelagem conceitual e lógica (Entidade-Relacionamento).

## Como Usar

1. Utilize o arquivo `SQL.txt` para replicar a estrutura em qualquer SGBD compatível com SQL.
2. O arquivo `sqlite.db` pode ser visualizado diretamente em ferramentas como **DB Browser for SQLite** ou via linha de comando.
