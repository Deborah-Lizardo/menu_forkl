# 🍽️ Cardápio Digital de Restaurante

Projeto acadêmico que integra estruturas de dados, CRUD com banco de dados (MySQL) e interface gráfica (JavaFX) para gerenciamento de um cardápio de restaurante.

## 🧠 Sobre o Projeto

O sistema permite gerenciar pratos com funcionalidades de cadastro, edição, remoção, busca e ordenação.

O objetivo é aplicar, na prática, conceitos de:
- Tabela Hash
- Algoritmos de ordenação (Bubble, Insertion e Quick Sort)
- CRUD com banco de dados
- Interface gráfica com JavaFX

## ⚙️ Tecnologias Utilizadas

- Java
- JavaFX
- MySQL
- JDBC

## 🧩 Conceitos Aplicados

- Tabela Hash para busca eficiente
- Algoritmos de ordenação:
  - Bubble Sort
  - Insertion Sort
  - Quick Sort (com recursividade)
- CRUD (Create, Read, Update, Delete)
- Arquitetura MVC

🗂️ Estrutura do Projeto
```
src/
├── controller/
├── dao/
├── model/
├── utils/
├── view/
└── Main.java
```

## 🚀 Funcionalidades
- Adicionar, editar e remover pratos
- Listar pratos do banco de dados
- Buscar pratos por nome usando Tabela Hash
- Ordenar pratos por:
- Nome
- Preço
- Tempo de preparo
- Comparar desempenho dos algoritmos de ordenação

## ▶️ Como Executar
- Configurar o banco de dados MySQL
- Ajustar as credenciais no ConnectionFactory
- Executar o projeto (Main.java ou aplicação JavaFX)
- Utilizar a interface para interagir com o sistema

## 🎯 Objetivo Acadêmico

Demonstrar a integração entre estruturas de dados, banco de dados e interface gráfica em uma aplicação prática.


## 🛢️ Banco de Dados

```sql
CREATE TABLE pratos (
    id INT AUTO_INCREMENT PRIMARY KEY,
    nome VARCHAR(100) NOT NULL,
    preco DECIMAL(10,2) NOT NULL,
    tempo_preparo INT NOT NULL,
    descricao TEXT
);
```
## 👥 Integrantes
- Deborah Lizardo
- Ana Julia
- Juliana Aparecida Vecchi



