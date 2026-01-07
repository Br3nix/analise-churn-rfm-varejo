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
Utilizando a metodologia **RFM (Recência, Frequência e Monetário)**, a base de clientes foi segmentada em grupos estratégicos com comportamentos distintos de compra.

- **Hibernantes:**  
  Representam a maior parte da base, com mais de 3.000 clientes. São clientes que compraram poucas vezes e há muito tempo, encontrando-se atualmente inativos. Esse grupo exige uma decisão estratégica entre investir em ações de reativação ou priorizar segmentos mais rentáveis.

- **Fiéis:**  
  Segundo maior segmento, com pouco menos de 2.000 clientes. Compram com frequência e são fundamentais para a geração de receita recorrente, mesmo não apresentando níveis de gasto ou recência tão elevados quanto os Campeões.

- **Campeões:**  
  Grupo menor, com cerca de 750 clientes, composto por clientes de alto valor que compram frequentemente, gastam mais e realizaram compras recentes. Apesar de representarem uma parcela menor da base, são estratégicos e devem ser priorizados para retenção e expansão.

- **Novos Promissores:**  
  Menor segmento da base. São clientes recentes com potencial de crescimento, mas que ainda não demonstraram frequência ou valor elevado. O tamanho reduzido desse grupo pode indicar desafios na aquisição ou na retenção inicial de novos clientes.
*![Image Alt](https://github.com/Br3nix/analise-churn-rfm-varejo/blob/main/Clientes%20por%20Segmento.png?raw=true)*

### 2. Análise de Coorte (Retenção)
O heatmap de retenção revelou padrões críticos sobre o comportamento do consumidor e a saúde do negócio:

**1. O Fenômeno da "Ressurreição Sazonal":**
Identificamos um comportamento atípico na coorte de 2009-12. A retenção, que operava na casa dos 35%, saltou para **50% no 12º mês** (Dezembro/2010).
* **Conclusão:** O produto possui forte apelo sazonal (presentes). Clientes "hibernam" durante o ano e reativam organicamente no Natal.
* **Estratégia:** Concentrar o budget de retenção em campanhas de "Reativação Antecipada" em Outubro/Novembro.

**2. Degradação da Qualidade da Aquisição (Safra):**
Houve uma queda preocupante na qualidade dos novos clientes.
* **Safra 2009:** Retenção imediata de **35%**.
* **Safra 2010:** Retenção imediata de apenas **9%**.
* **Conclusão:** A estratégia de aquisição de 2010 trouxe volume, mas falhou em trazer clientes qualificados (LTV baixo).

**3. O Gargalo do Primeiro Mês:**
Em média, **80% dos clientes** não retornam após a primeira compra (Churn Imediato). Isso indica uma falha crítica no *Onboarding* ou na experiência inicial.
*![Image Alt](https://github.com/Br3nix/analise-churn-rfm-varejo/blob/main/Heatmap.jpeg?raw=true)*

## 🚀 Como Executar o Projeto
1. Clone este repositório.
2. Instale as dependências: `pip install pandas seaborn matplotlib openpyxl`.
3. O dataset utilizado é o **Online Retail II** (UCI Machine Learning Repository).
4. Execute o notebook `Projeto_Retencao_Churn.ipynb`.

---
**Autor:** Breno Martins
*Conecte-se comigo no [LinkedIn](https://www.linkedin.com/in/brenomartins31/)*
---
