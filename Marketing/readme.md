# 📊 Dashboard Analytics: Análise de Comportamento do Cliente e Vendas

Este repositório contém um projeto interativo desenvolvido em **Power BI** focado na análise do perfil demográfico dos clientes, padrões de consumo, conversão de campanhas e distribuição geográfica das vendas.

*Projeto desenvolvido por Victor Lima de Oliveira para composição de portfólio referente ao curso "Microsoft Power BI Para Business Intelligence e Data Science" da "data science academy"*
---

## 📌 Visão Geral do Projeto

O objetivo deste painel é fornecer *insights* estratégicos sobre a base de clientes para otimizar campanhas de marketing, identificar perfis com maior propensão de compra e entender o impacto de variáveis como escolaridade, estado civil e estrutura familiar nas vendas.

### 💡 Principais Métricas (KPIs)
* **Total de Clientes:** `1.999`
* **Média de Salário Anual:** `R$ 51,98 Mil`
* **Volume de Compras na Loja:** `12 Mil`
* **Volume de Compras no Catálogo:** `5.270`
* **Volume de Compras na Web:** `8.147`
* **Compras com Desconto:** `4.661`

---

## 📂 Estrutura do Dashboard

O painel está dividido em páginas estratégicas:

### 1. Perfil Demográfico do Cliente
* **Escolaridade:** Distribuição de clientes por nível de instrução (*Curso Superior, Doutorado, Mestrado, Segundo Grau, Primeiro Grau*).
* **Estado Civil:** Análise da base focada em *Solteiros*, *Casados* e *Divorciados*.
* **Segmentação Geográfica:** Filtros por países como *Alemanha, Argentina, Brasil, Chile, Espanha, Estados Unidos e Portugal*.

### 2. Análise Renda vs. Comportamento de Gastos
* **Dispersão (Gastos x Salário):** Correlação direta entre a faixa salarial do cliente e o total gasto na plataforma.
* **Árvore de Decomposição (Decomposition Tree):** Detalhamento dos gastos totais por nível educacional e estado civil (com maior concentração no público de *Curso Superior* - R$ 617,55 Mil).
* **Impacto Familiar nos Gastos:**
  * **Gastos por Filhos em Casa:** Clientes sem filhos concentram o maior volume de gastos (> R$ 1,0 Mi).
  * **Gastos por Adolescentes em Casa:** Redução progressiva de gastos à medida que o número de adolescentes na residência aumenta.

### 3. Conversão e Eficiência de Compras
* **Taxa de Conversão ("Comprou"):**
  * **Não compraram:** `1.679` clientes (84%).
  * **Compraram:** `320` clientes (16%).
* **Perfil Financeiro x Compra:** Clientes que efetuaram compras possuem uma média salarial superior (~R$ 60 Mil) em relação aos que não compraram (~R$ 50 Mil).
* **Matriz de Conversão:** Cruzamento entre nível escolar e conversão de vendas.

### 4. Categorias de Produtos e Evolução Temporal (2018 - 2023)
* **Gastos por Categoria e País:** Avaliação de categorias de produtos (*Alimentos, Brinquedos, Eletrônicos, Móveis, Utilidades e Vestuário*) por país.
  * *Destaque:* Os **Estados Unidos** lideram com folga o volume total de vendas e contagem de clientes.
* **Evolução Histórica (2018–2023):** Acompanhamento do crescimento de vendas por país ao longo dos anos, destacando a liderança contínua dos EUA e Espanha.

---

## 🔍 Principais Insights Obtidos

1. **Público-Alvo Prioritário:** O perfil de cliente com maior LTV (Lifetime Value) é composto por indivíduos com **Curso Superior/Pós-Graduação**, sem filhos e com renda média superior a **R$ 60 Mil**.
2. **Impacto da Dependência Familiar:** A presença de filhos ou adolescentes em casa correlaciona-se inversamente com o volume total de compras.
3. **Concentração Geográfica:** Os mercados dos **Estados Unidos e Espanha** representam a maior fatia da receita em praticamente todas as categorias de produtos.

---

## 🛠️ Tecnologias e Ferramentas Utilizadas

* **Power BI Desktop** — Construção de modelos de dados, DAX e visualizações.
* **DAX (Data Analysis Expressions)** — Criação de métricas de agregação e formatos dinâmicos.
* **Power Query (M)** — Limpeza, transformação e estruturação da base de dados.

---

## 🚀 Como Visualizar o Projeto

Como o projeto está disponível em formato nativo do Power BI:

1. Baixe o arquivo `.pbix` localizado na raiz deste repositório.
2. Certifique-se de ter o [Power BI Desktop](https://powerbi.microsoft.com/pt-br/desktop/) instalado no seu computador.
3. Abra o arquivo `.pbix` para navegar interativamente por todos os filtros e relatórios.

---
