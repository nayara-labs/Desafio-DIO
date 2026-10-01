# 📊 Projeto de Análise de Dados com Azure SQL e Power BI

## 📌 Descrição

Este projeto foi desenvolvido como parte do desafio da DIO, com o objetivo de aplicar as etapas de coleta, obtenção e transformação de dados com Power BI e MySQL na Azure.

Durante o desenvolvimento foram realizadas etapas de modelagem, criação de tabelas, inserção de dados e consultas SQL, além da construção de um relatório para análise dos dados.

---

## 🛠️ Tecnologias Utilizadas

- Azure SQL Database
- Azure Cloud Shell
- MySQL
- Power BI Desktop
- GitHub

---

## 🗄️ Estrutura do Banco de Dados

Foram criadas as seguintes tabelas:

- employee
- dependent
- departament
- dept_locations
- project
- works_on

---

## 📥 Inserção de Dados

Após a criação da estrutura do banco, foram inseridos os registros referentes a:

- Funcionários
- Dependentes
- Departamentos
- Localizações
- Projetos
- Alocação dos funcionários em projetos

---

## 🔍 Consultas SQL

Foram executadas consultas para:

- Recuperação de dados dos funcionários
- Análise de departamentos
- Relacionamentos entre funcionários e projetos
- Quantidade de dependentes
- Uso de operadores lógicos
- Alias e concatenação de campos
- Cálculos sobre salários

---

## 📊 Dashboard Power BI

O conjunto de dados foi importado para o Power BI Desktop para desenvolvimento de visualizações e análises.


---

## ⚠️ Desafios Encontrados

Durante o desenvolvimento foi necessário:

- Resolver problemas relacionados a Foreign Keys.
- Ajustar consultas SQL incompatíveis com versões mais recentes do MySQL.
- Corrigir diferenças entre nomes de tabelas utilizados no script original.
- Corrigir problemas de sintaxe causados por caracteres especiais em consultas SQL.

Esses desafios contribuíram para uma melhor compreensão da modelagem de dados e da linguagem SQL.

---

## 🎯 Aprendizados

Este projeto permitiu consolidar conhecimentos sobre:

- Modelagem de dados
- Relacionamentos entre tabelas
- Cardinalidade
- Constraints
- Chaves Primárias e Estrangeiras
- Consultas SQL
- Azure SQL Database
- Integração entre Banco de Dados e Power BI
- Criação de dashboards analíticos

---
## Mesclagem de Tabelas

A mesclagem entre as tabelas **Departament** e **Dept_Locations** utilizando o campo **Dnumber** como chave de relacionamento.


### Por que utilizar Mesclar e não Combinar?

Neste caso, foi utilizada a opção **Mesclar Consultas**, pois o objetivo era reunir informações complementares presentes em tabelas diferentes por meio de um campo em comum.

A opção **Combinar Consultas** não seria adequada, pois ela é utilizada para unir registros de tabelas com a mesma estrutura, empilhando linhas uma abaixo da outra. Como as tabelas Departament e Dept_Locations possuem informações diferentes e complementares, a mesclagem foi a abordagem correta para consolidar os dados.
## 👩‍💻 Autora

Projeto desenvolvido por **Nayara** como parte da formação em Análise de Dados da DIO.
