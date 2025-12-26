# 🛡️ Customer Retention Analytics & Churn Strategy

## 📋 Visão Geral do Projeto
Este projeto investiga a **saúde da base de clientes** através de uma análise profunda do **Churn Histórico**.  
O objetivo é **diagnosticar os motivos de perda de clientes**, o **impacto financeiro das saídas** e a **eficácia das políticas de desconto**, servindo como base sólida para o desenvolvimento de **modelos de Machine Learning Preditivo**.

---

## 🔬 Fase 1: Diagnóstico de Churn de Clientes (Anual)
Nesta fase inicial, consolidamos os dados de movimentação de **2004 a 2025** para entender a **taxa de evasão de clientes únicos** ao longo do tempo.

---

## 📈 Principais Indicadores Estatísticos
Com base nos dados processados no notebook `churn-clientes-anual.ipynb`, identificamos:

| Métrica               | Valor    | Insight de Negócio                                                                 |
|----------------------|----------|------------------------------------------------------------------------------------|
| Média Histórica       | ~18%     | A empresa opera com um “vazamento” constante de quase **1/5 da base ao ano**.      |
| Churn 2025            | 22.28%   | **Pico crítico**: maior taxa de evasão da década.                                  |
| Ponto de Alerta (2020)| 12.38%   | **Menor churn histórico**; serve como benchmark de “ano ideal”.                   |
| Vida Média (LTV)      | 4.5 anos | Tempo médio que o esforço de vendas leva para ser “anulado” pelo churn.           |

---

## 🚨 Descobertas Estratégicas (Insights)

- **Acelerador de Churn em 2025**  
  Apesar de possuir a maior base histórica (**9.581 clientes**), o churn saltou drasticamente, sugerindo:
  - Entrada de clientes de **baixa qualidade**, ou  
  - **Atendimento e operação não escalando** no mesmo ritmo do crescimento.

- **Ciclo de Reposição**  
  A empresa precisa **renovar toda a base a cada 5 anos** apenas para manter o faturamento **estagnado**.

- **Volatilidade do Churn**  
  O churn não é estável e apresenta **picos recorrentes**, indicando sensibilidade a:
  - Fatores externos  
  - Mudanças em contratos e portfólio de serviços (**Alarme / CFTV**)

---

## 📂 Estrutura de Navegação do Projeto
O projeto é dividido em módulos para facilitar a evolução até **Machine Learning Preditivo**:

- `/analise-churn-clientes`  
  Análise de volume (Anual, Semestral, Trimestral, Mensal)

- `/analise-churn-faturamento` *(Próxima Fase)*  
  Impacto do churn em **MRR** e **LTV financeiro**

- `/churn-por-produto`  
  Análise de mix de contratos (**Alarme vs CFTV**)

- `/politica-descontos`  
  Correlação entre **descontos**, **tempo de retenção** e churn

---

## 🛠️ Stack Tecnológica

- **Linguagem:** Python 3.x  
- **Manipulação de Dados:** Pandas, NumPy  
- **Estatística & Survival Analysis:** SciPy, Lifelines  
- **Visualização:** Matplotlib, Seaborn, Plotly  
- **Banco de Dados:** PostgreSQL (via SQLAlchemy)

---

## 👤 Autor
**Fabio Pimentel**  
*Cientista de Dados focado em Estratégia de Negócio e Retenção de Clientes*
