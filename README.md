# 🐾 Petshop SQL

Sistema de banco de dados para gerenciamento de um Petshop, desenvolvido utilizando **SQL** com foco em modelagem relacional, criação de tabelas e operações de manipulação de dados.

---

## 📌 Sobre o projeto

Este projeto tem como objetivo simular o funcionamento de um **Petshop**, permitindo o gerenciamento de informações como:

* Clientes
* Pets
* Produtos
* Serviços
* Agendamentos

O sistema foi construído utilizando **SQL puro**, explorando conceitos fundamentais de bancos de dados relacionais como DDL e DML, essenciais para manipulação de dados em sistemas reais ([Docsity][1]).

---

## 🧠 Funcionalidades

✔️ Criação do banco de dados
✔️ Criação de tabelas com relacionamentos
✔️ Inserção de dados (INSERT)
✔️ Consultas (SELECT)
✔️ Atualização de dados (UPDATE)
✔️ Remoção de dados (DELETE)
✔️ Relacionamentos entre entidades (chaves primárias e estrangeiras)

---

## 🗂️ Estrutura do projeto

```
Petshop-Sql/
│
├── database.sql        # Script principal para criação do banco
├── inserts.sql         # Inserção de dados de exemplo
├── queries.sql         # Consultas SQL
└── README.md           # Documentação do projeto
```

*(Os nomes podem variar conforme seu repositório — ajuste se necessário)*

---

## 🧱 Modelagem do Banco

O banco de dados foi estruturado com base em entidades comuns de um sistema de Petshop:

* **Cliente**
* **Pet**
* **Produto**
* **Serviço**
* **Agendamento**

Essas entidades se relacionam entre si para representar o funcionamento real de um sistema de gestão.

---

## ⚙️ Tecnologias utilizadas

* SQL (Structured Query Language)
* MySQL / PostgreSQL *(ajuste conforme você usou)*

---

## 🚀 Como executar o projeto

1. Clone o repositório:

```bash
git clone https://github.com/EduGomes221/Petshop-Sql.git
```

2. Abra o seu gerenciador de banco de dados:

* MySQL Workbench / DBeaver / PgAdmin

3. Execute o script principal:

```sql
SOURCE database.sql;
```

4. (Opcional) Execute os inserts:

```sql
SOURCE inserts.sql;
```

5. Execute as consultas:

```sql
SOURCE queries.sql;
```

---

## 💡 Exemplos de consultas

```sql
-- Listar todos os clientes
SELECT * FROM cliente;

-- Buscar pets de um cliente específico
SELECT * FROM pet WHERE cliente_id = 1;

-- Listar agendamentos
SELECT * FROM agendamento;
```

---

## 🏗️ Conceitos aplicados

* Modelagem de dados
* Normalização
* Chaves primárias e estrangeiras
* Integridade referencial
* CRUD completo
* Relacionamentos entre tabelas

---

## 📚 Objetivo acadêmico

Este projeto foi desenvolvido com fins educacionais, visando praticar:

* Estruturação de banco de dados
* Escrita de queries SQL
* Organização de projetos no GitHub

---


