# Projeto PySpark no Databricks - Tabela SalesOrderItems

## Descrição

Este projeto utiliza PySpark no Databricks Community Edition para realizar a transformação de dados em três etapas principais: `source_to_transient`, `transient_to_bronze` e `bronze_to_silver`. O objetivo é demonstrar o fluxo de dados desde a fonte até a camada Silver, utilizando boas práticas de engenharia de dados.

## Estrutura do Projeto

- **source_to_transient**: 
  - Descrição: Carrega os dados da fonte e realiza as transformações iniciais.
  - Notebook: [source_to_transient - vendas - SAP - tb_fat_sales_order_items.ipynb]

- **transient_to_bronze**: 
  - Descrição: Processa os dados para a camada Bronze, armazenando-os em um formato bruto.
  - Notebook: [transient_to_bronze - vendas - SAP - tb_fat_sales_order_items.ipynb]

- **bronze_to_silver**: 
  - Descrição: Realiza a limpeza e transformação dos dados da camada Bronze para a camada Silver.
  - Notebook: [bronze_to_silver - vendas - SAP - tb_fat_sales_order_items.ipynb]

## Pré-requisitos

- Conta no [Databricks Community Edition](https://community.cloud.databricks.com/)
- Conhecimento básico em PySpark
- Familiaridade com Git e GitHub

