# 👥 Dashboard de People Analytics & Perfil Colaborativo (Power BI)

Este repositório contém um dashboard focado em **People Analytics / Recursos Humanos**, projetado para analisar a composição do quadro de colaboradores, distribuição por funções técnicas de dados, engajamento no trabalho e disponibilidade para horas extras.

*Projeto desenvolvido por Victor Lima de Oliveira para composição de portfólio referente ao curso "Microsoft Power BI Para Business Intelligence e Data Science" da "data science academy"*

---

## 📌 Visão Geral do Dashboard

O objetivo principal deste painel é fornecer à gestão de RH e lideranças técnicas uma visão clara sobre o perfil demográfico, salarial e de engajamento da equipe de tecnologia e dados.

### 📊 Indicadores Principais (KPIs)

* **Total de Funcionários:** `1.400` colaboradores.
* **Experiência Média:** `11,29 anos`.
* **Salário Médio Geral:** `R$ 6.927,51` (com filtro dinâmico por faixa etária de 18 a 60 anos).
* **Distribuição por Gênero:**
  * **Masculino:** `838` colaboradores (`59,86%`).
  * **Feminino:** `562` colaboradoras (`40,14%`).

## 🛠️ Análises & Visuais em Destaque

1. **Total de Funcionários por Função (Gráfico de Barras):**
   * Mapeia as funções com maior volume na área de dados:
     * **Cientista de Dados:** 638 colaboradores.
     * **Analista de Dados:** 246 colaboradores.
     * **Engenheiro de IA:** 176 colaboradores.
     * **Arquitetoto de Dados:** 139 colaboradores.
     * **Engenheiro de Dados:** 125 colaboradores.
     * **Engenheiro Analítico:** 76 colaboradores.

2. **Envolvimento no Trabalho (Gráfico de Rosca com Total Centralizado):**
   * Avalia o nível de engajamento da equipe:
     * **Médio:** 826 colaboradores.
     * **Baixo:** 356 colaboradores.
     * **Alto:** 139 colaboradores.
     * **Ruim:** 79 colaboradores.

3. **Disponibilidade para Hora Extra (Gráfico de Pizza):**
   * **Não disponíveis:** `71,57%`
   * **Disponíveis:** `28,43%`

## 🧠 Insights de Negócio

* **Diversidade de Gênero:** Há uma predominância masculina (~59,86% vs ~40,14%), indicando oportunidades contínuas para ações de inclusão e atração de talentos femininos.
* **Retenção & Engajamento:** A maioria da equipe possui um envolvimento **médio/alto** (965 pessoas), porém 435 colaboradores (baixo + ruim) demandam estratégias de engajamento por parte do RH.
* **Capacidade Operacional:** Cerca de ~28,4% da equipe está disponível para horas extras, dado fundamental para alocação de squads e gestão de prazos sem gerar *burnout*.

## 💻 Tecnologias & Recursos Utilizados

* **Microsoft Power BI Desktop**
* **DAX:** Métricas para cálculo de médias salariais, percentuais de representatividade por gênero e distribuições.
* **Data Visualization / UI:** Layout moderno em *cards* arredondados, paleta de cores corporativa e aproveitamento do espaço central no gráfico de rosca.

## 📂 Como Visualizar o Relatório

1. Clone o repositório ou baixe o arquivo `.pbix`:
   ```bash
   git clone https://github.com/SEU_USUARIO/NOME_DO_REPOSITORIO.git
   ```
2. Abra o arquivo no **Power BI Desktop**.