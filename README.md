
# 📘 Planejamento Semanal – Engenharia de Dados (Zureta)

---

## 📅 Semana 1 – Fundamentos e primeiros passos

### 🎯 Objetivo:
- Reforçar fundamentos de Python e SQL
- Iniciar o estudo de dados reais

---

### 🟧 Segunda, Quarta e Sexta – Python
- Variáveis, tipos de dados, estruturas condicionais
- Listas, dicionários, funções
- Leitura de CSV com `pandas`
- Limpeza básica: renomear colunas, tratar nulos, padronizar tipos

### 🟦 Terça e Quinta – SQL
- SELECT, WHERE, ORDER BY
- COUNT, AVG, GROUP BY, HAVING
- JOINs básicos (INNER JOIN)
- Consultas em bases públicas do Kaggle ou SQLite

---

## 📅 Semana 2 – Prática com dados reais

### 🎯 Objetivo:
- Consolidar conhecimento com um dataset real
- Montar uma mini análise e trabalhar com transformação de dados

---

### 🟧 Segunda, Quarta e Sexta – Python
- Leitura de CSVs reais (Brazilian E-commerce Dataset)
- `merge`, `groupby`, `pivot_table`
- Exploração dos dados: valores únicos, tipos, estatísticas com `describe()`
- Visualizações simples com `matplotlib` ou `seaborn`

### 🟦 Terça e Quinta – SQL
- Subqueries
- Joins múltiplos
- CASE WHEN
- Criação de tabelas (`CREATE TABLE`)
- Inserção de dados (`INSERT INTO`)

---

## 📅 Semana 3 – Mini projeto local + DuckDB (BigQuery like)

### 🎯 Objetivo:
- Montar uma pipeline completa: carregar, transformar, salvar e consultar
- Entender schema e tipos de dados
- Aprender a usar DuckDB localmente

---

### 🟧 Segunda – Python
- Estrutura de projeto real: `load.py`, `transform.py`, `main.py`
- Organização de pasta: `data/`, `scripts/`, `output/`

### 🟦 Terça – SQL
- Tipos de dados SQL: `INT`, `VARCHAR`, `FLOAT`, `DATE`
- Entender schema
- Criar estrutura fictícia de tabela

### 🟧 Quarta – DuckDB
- `pip install duckdb`
- Consultas SQL direto sobre arquivos
- Leitura de CSV com DuckDB

### 🟦 Quinta – Consultas no DuckDB
- `GROUP BY`, `JOIN`, `AGGREGATE`
- Exportar resultados com `COPY TO`

### 🟧 Sexta – Pipeline completo
- Executar script `main.py` com etapas organizadas
- Separar transformações e salvar resultado final

---

## 📅 Semana 4 – Projeto completo + automações + introdução à nuvem

### 🎯 Objetivo:
- Criar um projeto completo simulando uma empresa
- Automatizar a execução do pipeline
- Entender como seria esse fluxo na nuvem

---

### 🟧 Segunda – Projeto e Dados
- Simular empresa de e-commerce
- Usar dados: `orders`, `customers`, `products`
- Estrutura do projeto com pastas

### 🟦 Terça – SQL no estilo DW
- Pensar em dimensões e fatos
- Consultas: total por cliente, ticket médio por categoria

### 🟧 Quarta – Pipeline automatizado
- Função `run_pipeline()` com `load → transform → query → save`

### 🟦 Quinta – Introdução à Cloud
- Conceitos: Storage, Data Warehouse, Pipelines
- Simular estrutura com DuckDB

### 🟧 Sexta – Agendador com Python
- Usar `schedule` para simular cron
- Executar `run_pipeline()` diariamente

---

## ✅ Observações

- O plano é flexível: pode ser adaptado conforme o ritmo
- Ao final, gerar um README com explicações e preparar um portfólio

---

