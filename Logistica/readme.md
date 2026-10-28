# 🚚 Dashboard de Logística e Eficiência de Entregas (Power BI)

Este repositório contém um dashboard interativo focado na **gestão da cadeia de suprimentos e eficiência de entregas**, desenvolvido no **Power BI**. O objetivo do painel é monitorar a pontualidade da operação logística, avaliar canais de distribuição e medir o desempenho por equipes e regiões.

*Projeto desenvolvido por Victor Lima de Oliveira para composição de portfólio referente ao curso "Microsoft Power BI Para Business Intelligence e Data Science" da "data science academy"*

---

## 📌 Visão Geral do Dashboard

O painel oferece uma visão panorâmica sobre o cumprimento dos prazos de envio, sazonalidade das entregas e performance dos canais de distribuição para otimização de SLA (*Service Level Agreement*).

### 📊 Indicadores Principais (KPIs)

* **Total de Entregas:** `54 Mil` pedidos processados.
* **Total de Entregas no Prazo:** `47 Mil` entregas concluídas dentro do tempo estipulado (\~87% de pontualidade operacional).

---

## 🛠️ Análises & Visuais em Destaque

1. **Total de Entregas No Prazo por Canal de Entrega:**
   * Gráfico de área destacando a performance por canais (ex.: `Canal07`, `Canal19`, `Canal11` concentrando os maiores volumes de entregas no prazo).
2. **Percentual de Entregas por Equipe / Região:**
   * Distribuição das entregas por equipes regionais:
     * **Norte:** `27,44%`
     * **Sudeste:** `24,87%`
     * **Nordeste:** `16,72%`
     * **Sul:** `13,35%`
     * **Internet / Televendas / Outros:** Compõem a parcela complementar da operação.
3. **Percentual de Entregas por Status de Entrega:**
   * Classificação do status dos envios em três categorias principais:
     * **Antecipado** (maior volume)
     * **No Prazo**
     * **Atrasado**
4. **Sazonalidade e Tendência Mensal (Linha do Tempo):**
   * Gráfico de linha mostrando a variação de entregas de Janeiro a Dezembro, evidenciando pico operacional entre Fevereiro e Julho e queda no mês de Setembro.
5. **Avaliação por Vendedor e Cidades (Tabelas com Relação de Desempenho):**
   * Tabela com pontuação por estrelas (*Rating*) e total de entregas por vendedor.
   * Ranking de cidades por volume absoluto de entregas.
   * Filtro temporal dinâmico por ano (`2019` e `2020`).

---

## 🧠 Insights de Negócio

* **Concentração Regional:** As equipes do **Norte** e **Sudeste** representam juntas mais de **52%** de todas as entregas realizadas.
* **Eficiência Operacional:** A maioria das entregas com alto cumprimento de prazo está concentrada no **Canal07** e no status **Antecipado**, mostrando eficiência nas rotas principais.
* **Atenção à Sazonalidade:** O mês de **Setembro** apresentou uma queda expressiva no volume de entregas, exigindo análise de causa raiz para entender se houve gargalo logístico ou oscilação de demanda.

---

## 💻 Tecnologias Utilizadas

* **Microsoft Power BI Desktop**
* **DAX:** Criação de métricas de contagem, percentual de pontualidade e rankings de performance.
* **Data Visualization:** Design limpo e objetivo utilizando *cards* de KPI, gráficos de área, tabelas com sistema de avaliação por estrelas (*Rating*) e segmentação de dados temporais.

---

## 📂 Como Visualizar o Relatório

1. Clone o repositório para o seu ambiente local:
   ```bash
   git clone https://github.com/SEU_USUARIO/NOME_DO_REPOSITORIO.git
   ```
2. Abra o arquivo `.pbix` no **Power BI Desktop**.