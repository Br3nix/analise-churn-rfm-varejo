# 📊 Análise de Retenção e Segmentação de Clientes (RFM & Cohort)

## 📌 Visão Geral
Este projeto analisa dados transacionais de um e-commerce do Reino Unido (2009-2011) para identificar padrões de comportamento de compra, segmentar clientes e calcular métricas de retenção.
O objetivo é fornecer insights acionáveis para times de Marketing e CRM reduzirem o Churn e aumentarem o LTV (Lifetime Value).

## 💼 Problema de Negócio
A empresa possui uma base de +800 mil transações, mas carecia de visibilidade sobre:
1. Quem são os clientes mais valiosos?
2. Qual é a taxa de retenção mensal (Cohorts)?
3. Quais clientes estão prestes a abandonar a marca (Churn)?

## 🛠️ Tecnologias Utilizadas
* **Python 3.10**
* **Pandas & Numpy:** Limpeza e manipulação de dados.
* **Matplotlib & Seaborn:** Visualização de dados.
* **Técnicas:** Análise de Coorte (Cohort Analysis) e Segmentação RFM.

## 🔍 Principais Insights

### 1. Segmentação RFM
Utilizando a metodologia RFM (Recência, Frequência, Monetário), dividimos a base em grupos estratégicos.
* **Campeões:** Compram frequentemente e gastaram muito recentemente.
* **Em Risco:** Clientes antigos de alto valor que pararam de comprar.
* **Hibernantes:** Clientes de baixo valor e inativos.
*(Aqui você pode colocar o seu gráfico de barras)*

### 2. Análise de Coorte (Retenção)
A análise de Heatmap revelou que:
* A retenção imediata (Mês 1) caiu drasticamente de 2009 para 2011, indicando problemas na aquisição recente.
* Existe uma **sazonalidade anual forte**: Clientes tendem a retornar no mês 11/12 (Novembro/Dezembro), sugerindo comportamento de compra natalina.

## 🚀 Como Executar o Projeto
1. Clone este repositório.
2. Instale as dependências: `pip install pandas seaborn matplotlib openpyxl`.
3. O dataset utilizado é o **Online Retail II** (UCI Machine Learning Repository).
4. Execute o notebook `Projeto_Retencao_Churn.ipynb`.

---
**Autor:** Breno Martins
*Conecte-se comigo no [LinkedIn](https://www.linkedin.com/in/brenomartins31/)*
---
