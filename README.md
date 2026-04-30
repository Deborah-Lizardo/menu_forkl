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

## 🛢️ Banco de Dados

```sql
CREATE TABLE pratos (
    id INT AUTO_INCREMENT PRIMARY KEY,
    nome VARCHAR(100) NOT NULL,
    preco DECIMAL(10,2) NOT NULL,
    tempo_preparo INT NOT NULL,
    descricao TEXT
);
