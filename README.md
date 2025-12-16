# PipeFlow

## Descrição

Este repositório contém um projeto de **Business Intelligence (BI)** e **Análise de Dados** focado na criação de um **Dashboard de Vendas** interativo.

O projeto utiliza o **Microsoft Power BI** para visualização e análise, e é suportado por um conjunto de arquivos de dados em formato Excel (`.xlsx`) que representam um esquema de banco de dados relacional (modelo estrela ou *star schema*), comum em projetos de Data Warehousing.

O objetivo principal é transformar dados brutos de vendas em *insights* acionáveis, permitindo o acompanhamento de métricas de desempenho e a tomada de decisões estratégicas.

## Estrutura do Projeto

O projeto está organizado da seguinte forma, com foco nos arquivos de dados e no dashboard:

```
.
├── ProjetoFinalPowerBi.pbix  <- O Dashboard de Vendas do Power BI
├── dCategoria.xlsx          <- Tabela Dimensão: Categorias de Produtos
├── dCliente.xlsx            <- Tabela Dimensão: Clientes
├── dForma.xlsx              <- Tabela Dimensão: Formas de Pagamento
├── dFornecedor.xlsx         <- Tabela Dimensão: Fornecedores
├── dNota.xlsx               <- Tabela Dimensão: Notas Fiscais
├── dProduto.xlsx            <- Tabela Dimensão: Produtos
├── dVendedor.xlsx           <- Tabela Dimensão: Vendedores
└── fVendas (1).xlsx         <- Tabela Fato: Transações de Vendas
```

## Componentes Principais

### 1. Dashboard de Vendas (Power BI)

O arquivo `ProjetoFinalPowerBi.pbix` é o artefato central do projeto. Ele contém:

*   **Modelo de Dados:** O esquema relacional (Dimensões e Fato) construído a partir dos arquivos Excel.
*   **Medidas e Cálculos (DAX):** Métricas de vendas, lucro, margem, etc.
*   **Visualizações:** Gráficos, tabelas e cartões que apresentam os principais KPIs de vendas.

### 2. Dados de Suporte (Arquivos Excel)

Os arquivos `.xlsx` simulam um Data Warehouse e são a fonte de dados para o dashboard:

*   **Tabelas Dimensão (`d*`):** Contêm atributos descritivos (ex: nome do cliente, descrição do produto).
*   **Tabela Fato (`fVendas`):** Contém as transações de vendas e as chaves para as tabelas dimensão.

## Tecnologias Utilizadas

*   **Microsoft Power BI:** Para modelagem, análise e visualização de dados.
*   **Microsoft Excel:** Para armazenamento e simulação da fonte de dados.

## Como Visualizar

1.  **Instale o Power BI Desktop:** Certifique-se de ter o software instalado em sua máquina.
2.  **Clone o repositório:**
    ```bash
    git clone https://github.com/miguelcastell/PipeFlow.git
    cd PipeFlow
    ```
3.  **Abra o Dashboard:** Dê um duplo clique no arquivo `ProjetoFinalPowerBi.pbix`. O Power BI fará a conexão automática com os arquivos Excel locais.

## Contribuição

Este projeto é um portfólio de BI. Sugestões de melhorias no modelo de dados ou nas visualizações são bem-vindas.

## Autor

**Miguel Mantoan Castellani**
*   [GitHub](https://github.com/miguelcastell)
*   [LinkedIn](https://www.linkedin.com/in/miguel-mantoan-castellani-744304324) (URL obtida do perfil)
