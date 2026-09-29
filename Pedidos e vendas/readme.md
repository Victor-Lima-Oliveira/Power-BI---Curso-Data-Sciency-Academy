# 📈 Dashboard de Análise Global de Vendas, Margem & Logística (Power BI)

Este repositório contém um projeto de Business Intelligence desenvolvido para analisar a performance comercial global, rentabilidade e eficiência logística de vendas. O projeto engloba desde a **modelagem de dados dimensional (Star Schema)** até a criação de visualizações estratégicas e métricas de desempenho.

*Projeto desenvolvido por Victor Lima de Oliveira para composição de portfólio referente ao curso "Microsoft Power BI Para Business Intelligence e Data Science" da "data science academy"*
---

## 📌 Sumário

* [Visão Geral](#-visão-geral)
* [Arquitetura & Modelagem de Dados](#-arquitetura--modelagem-de-dados)
* [Estrutura do Dashboard & Métricas](#-estrutura-do-dashboard--métricas)
* [Principais Insights](#-principais-insights)
* [Tecnologias Utilizadas](#-tecnologias-utilizadas)
* [Como Visualizar o Projeto](#-como-visualizar-o-projeto)

---

## 📸 Visão Geral

O objetivo principal deste relatório é monitorar a evolução temporal das margens de lucro, avaliar a rentabilidade por categoria de produto, mapear custos de envio internacionais e analisar o volume de vendas por modalidade de entrega.

---

## 🏗️ Arquitetura & Modelagem de Dados

O modelo de dados foi desenvolvido seguindo as melhores práticas de **Business Intelligence**, utilizando a arquitetura em estrela (**Star Schema**). A centralização das transações na tabela fato garante alta performance nas consultas DAX e facilidade de filtragem cruzada.

```
       +------------------+             +------------------+
       |     Clientes     |             |     Pedidos      |
       +------------------+             +------------------+
       | ID Cliente (PK)  |             | ID Pedido (PK)   |
       | Nome, Cidade...  |             | Data, Modo...    |
       +--------+---------+             +--------+---------+
                | 1                              | 1
                |                                |
                | *                              | *
       +--------+--------------------------------+---------+
       |                         Vendas                    | (Tabela Fato)
       +---------------------------------------------------+
       | Cliente (FK) | Pedido (FK) | Produto (FK)         |
       | Lucro | MargemLucro | Custo Envio | Valor Venda   |
       +---------------------------------------------------+
                                * |
                                  | 1
                        +---------+--------+
                        |     Produtos     |
                        +------------------+
                        | ID Produto (PK)  |
                        | Categoria...     |
                        +------------------+
```

### Tabelas do Modelo:
1. **`Vendas` (Tabela Fato):** Registra as métricas quantitativas e financeiras (*Valor Venda*, *Lucro*, *MargemLucro*, *Custo Envio*).
2. **`Clientes` (Dimensão):** Informações geográficas e demográficas (*ID Cliente*, *Nome*, *Cidade*, *Estado*, *País*, *Região*, *Mercado*, *Segmento*).
3. **`Produtos` (Dimensão):** Hierarquia de produtos (*ID Produto*, *Nome Produto*, *Categoria*, *SubCategoria*).
4. **`Pedidos` (Dimensão):** Atributos temporais e operacionais do pedido (*ID Pedido*, *Data Pedido*, *Data Envio*, *Modo Envio*, *Prioridade Pedido*).

---

## 🚀 Estrutura do Dashboard & Métricas

O painel foi desenhado de forma intuitiva, combinando diferentes tipos de visuais estratégicos:

### 1. 🎛️ Indicadores de Desempenho (KPIs & Gauges)
* **Média de Valor Venda (Medidor Gauge):** Exibe o ticket médio atual de **R$ 246,49**, posicionado em relação ao intervalo meta configurado de **0,00 a 400,00**.

### 2. 📦 Rentabilidade por Categoria (Gráfico de Pizza)
* **Média de Lucro por Categoria:**
  * **Tecnologia:** Lidera a rentabilidade média com **46,5%** (R$ 417,85).
  * **Móveis:** Representa **41,4%** do lucro médio (R$ 371,66).
  * **Material de Escritório:** Corresponde a **12,05%** (R$ 108,13).

### 3. 🚚 Análise Logística & Custos de Envio (Treemap & Waterfall)
* **Média de Custo Envio por Mercado (Treemap):** Mapeia os custos médios de frete globais, destacando **APAC** ($29,14$) e **US** ($28,94$) com os maiores custos por remessa, seguidos por **EU**, **LATAM**, **Africa**, **EMEA** e **Canada**.
* **Soma de Valor Venda por Modo Envio (Gráfico de Cascata / Waterfall):** Evidencia a composição do volume total de vendas através do tipo de frete, onde a **Classe Padrão** representa a esmagadora maioria do volume financeiro, seguida pela *Segunda Classe*, *Primeira Classe* e *Mesmo Dia*.

### 4. 📈 Tendência Temporal (Gráfico de Linha)
* **Evolução da Margem de Lucro (2011 - 2014):** Acompanhamento histórico mostrando crescimento consistente da *Soma de MargemLucro* ao longo dos anos, superando a marca de **R$ 150 mil a R$ 200 mil** no último período analisado.

---

## 💡 Principais Insights

* **Carro-Chefe Financeiro:** A categoria de **Tecnologia** gera a maior margem de lucro individual por venda, tornando-a essencial para estratégias de expansão de margem.
* **Dominância Operacional:** O frete **Classe Padrão** absorve o maior volume financeiro, sendo o meio preferencial dos clientes, apesar dos custos logísticos variarem significativamente entre mercados como APAC e EMEA.
* **Trajetória de Crescimento:** O histórico de 2011 a 2014 revela forte sazonalidade anual com picos crescentes de lucro no final de cada exercício.

---

## 🛠️ Tecnologias Utilizadas

* **Microsoft Power BI Desktop:** Construção das visuais e modelagem.
* **Modelagem Dimensional:** Star Schema (Fato e Dimensões com relacionamentos $1 : *$).
* **DAX (Data Analysis Expressions):** Criação de medidas agregadas de Lucro, Valor Venda e Margens.

---

## 📂 Como Visualizar o Projeto

1. Baixe o arquivo `.pbix` disponível no repositório.
2. Abra através do **Power BI Desktop**.
3. Interaja com os seletores de filtro de **Ano** e **Mês** no topo do relatório para análises dinâmicas.

---

