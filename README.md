# Projeto EVG - Modelagem de Dados Dimensional

## Descrição do Projeto

Este projeto aplica os conceitos de modelagem de dados dimensional (Star Schema) sobre uma
base de dados pública de matrículas e cursos da Escola Virtual de Governo (EVG). A partir de
uma tabela desnormalizada (One Big Table), foram construídas uma tabela Fato e seis tabelas
Dimensão, com tratamento de dados realizado no Power Query e relacionamentos configurados
no Power BI.

## Perguntas de Negócio

1. **Quais são os cursos com maior número de matrículas?**
2. **Quais estados/municípios têm mais alunos matriculados?**

## Modelo Lógico

O modelo lógico foi desenhado utilizando a ferramenta DrawDB, identificando a Tabela Fato
(F_matriculas) e as Tabelas Dimensão (Dim_Curso, Dim_turma, Dim_Pessoa, Dim_poder,
Dim_esfera, Dim_localidade).

<img width="4608" height="2476" alt="ModeloLogico" src="https://github.com/user-attachments/assets/f4cc6ed0-b88a-4e7e-b4f0-fe606944f908" />

## Dashboard

O dashboard publicado pode ser acessado através do link abaixo:

https://app.powerbi.com/links/fDHahPOBks?ctid=dfb66dc4-3f3c-492c-991d-727dbd1c89d4&pbi_source=linkShare

## Tecnologias Utilizadas

- Power BI Desktop
- Power Query (ETL)
- DAX
- DrawDB (Modelagem Lógica)
- Git / GitHub
