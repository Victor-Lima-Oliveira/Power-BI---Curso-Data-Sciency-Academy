# 📊 Dashboard de Análise de Vendas & Performance Regional (Power BI)

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Data Analytics](https://img.shields.io/badge/Data_Analytics-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Status](https://img.shields.io/badge/Status-Concluído-brightgreen?style=for-the-badge)

Este repositório contém um projeto de Business Intelligence voltado para a análise estratégica de vendas, distribuição por fabricantes, categorias, canais e áreas geográficas. O relatório foi construído para fornecer insights acionáveis com o suporte de recursos avançados de Inteligência Artificial do Power BI.

*Projeto desenvolvido por Victor Lima de Oliveira para composição de portfólio referente ao curso "Microsoft Power BI Para Business Intelligence e Data Science" da "data science academy"*
---

## 📌 Sumário
- [Visão Geral](#-visão-geral)
- [Funcionalidades & Páginas](#-funcionalidades--páginas)
- [Principais Insights](#-principais-insights)
- [Tecnologias e Recursos Utilizados](#-tecnologias-e-recursos-utilizados)
- [Como Visualizar o Projeto](#-como-visualizar-o-projeto)

---

## 📸 Visão Geral

O objetivo principal deste dashboard é acompanhar o desempenho comercial em diferentes eixos:
1. **Performance por Fabricante e Categoria**
2. **Impacto dos Segmentos nas Vendas (Key Influencers)**
3. **Distribuição do Fluxo de Vendas por Ponto de Venda/Loja**
4. **Geolocalização do Volume de Vendas por Vendedor e Estado**

---

## 🚀 Funcionalidades & Páginas

### 1. 🧠 Narrativa Inteligente (Smart Narrative)
- **Geração Automática de Texto:** Texto dinâmico que sumariza as variações de vendas por fabricantes e categorias.
- **Distribuição por Segmento:** Gráfico de pizza destacando o segmento *Doméstico* com maior representatividade (~71.47%), seguido pelo *Corporativo* (~25.03%) e *Industrial* (~3.49%).
- **Ranking de Fabricantes:** Análise gráfica liderada pela **Brastemp** (R$ 93 mil), seguida por **Samsung** (R$ 83 mil) e **Consul** (R$ 59 mil).
- **Funil por Categoria:** Visualização do volume de receita:
  - Eletrodomésticos: **R$ 193,32 Mil**
  - Celulares: **R$ 98,60 Mil**
  - Eletrônicos: **R$ 48,33 Mil**
  - Eletroportáteis: **R$ 19,06 Mil**

### 2. 🔍 Principais Influenciadores (Key Influencers)
- **Análise Causal:** Utilização do algoritmo nativo do Power BI para identificar o que faz o *Valor de Venda* **diminuir** ou **aumentar**.
- **Fatores Negativos/Redutores:** Identificação de que pertencimento ao segmento **Doméstico** e à categoria de **Eletroportáteis** atua como um forte fator redutor no ticket médio quando comparado aos demais segmentos (Corporativo e Industrial).

### 3. 🔀 Faixa de Vendas por Categorias e Pontos de Venda (Sankey / Ribbon)
- **Mapeamento de Fluxo:** Relação visual de como os volumes das categorias (*Eletrodomésticos*, *Celulares*, *Eletrônicos*, *Eletroportáteis*) se distribuem entre os pontos de venda e códigos de lojas (ex: `SP8822`, `SP8821`, `R1296`, `B7659`, etc.).

### 4. 🗺️ Performance de Vendas por Região (Geolocalização)
- **Distribuição Geográfica:** Mapeamento espacial das vendas focando na região Sudeste (com destaque para as capitais São Paulo e Rio de Janeiro e suas regiões metropolitanas).
- **Análise por Vendedor:** Desmembramento em gráfico de pizza sobre as coordenadas geográficas mostrando a atuação de vendedores como *André Pereira*, *Artur Moreira* e *Josias Silva*.

---

## 💡 Principais Insights

- **Liderança em Categoria & Fabricantes:** A categoria de *Eletrodomésticos* domina o volume de receitas, com a *Brastemp* liderando o ranking de fabricantes com um valor $1.286,94\%$ superior à *Electrolux*.
- **Oportunidade no Segmento Corporativo:** Embora o segmento *Doméstico* tenha maior volume acumulado de pedidos, o segmento *Corporativo* apresenta o maior ticket médio/venda média, representando uma oportunidade para estratégias B2B.
- **Concentração Geográfica:** A maior densidade de volume de vendas está concentrada no eixo SP–RJ, exigindo atenção logística e tática dedicada a essas praças.

---

## 🛠️ Tecnologias e Recursos Utilizados

- **Microsoft Power BI Desktop:** Modelagem de dados, DAX e criação de visuais.
- **Power BI AI Visuals:** *Smart Narrative* e *Key Influencers*.
- **Custom Visuals:** Visual de mapa de bolhas geográfico e diagramas de fluxo.

---

## 📂 Como Visualizar o Projeto

1. Baixe o arquivo `.pbix` presente neste repositório.
2. Abra no **Power BI Desktop** (atualizado).

---
