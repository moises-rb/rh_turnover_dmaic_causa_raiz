# 🟦 RH Analytics: Diagnóstico de Causa Raiz e Redução de Turnover (Metodologia DMAIC)

Este é um projeto simulado que faz parte da minha trilha prática em Ciência de Dados aplicada ao RH (People Analytics). O foco é aplicar a metodologia **DMAIC (Six Sigma)** com **Estatística Analítica** para migrar de uma abordagem de **Predição** para uma solução de **Melhoria Contínua** e **Causa Raiz** para o problema de *turnover* nos primeiros 90 dias.

---

## 🔗 Projeto Predecessor (Contexto Inicial)

Este projeto de Análise Estatística e DMAIC é uma evolução de um estudo inicial focado em Machine Learning:

* **Projeto Original (ML):** [Previsão de Turnover com Random Forest](**https://github.com/moises-rb/Previsao-de-Turnover**)
    * *O projeto original serviu para gerar a **Feature Importance** (Os X's) e a **Baseline** (Taxas de Turnover) que alimentam a **FASE MEASURE** e **ANALYZE** deste projeto DMAIC.*

---

## 🎯 Objetivo e Escopo (FASE DEFINE)

A meta é **reduzir a Taxa de Turnover de 90 dias nos departamentos de Finance e Marketing em 30%** nos próximos 6 meses.

O projeto foca em:

-   **Confirmação Estatística** dos fatores de risco (Regressão Logística).
-   **Quantificação do Risco** e da capacidade atual do processo (Baseline e RTY).
-   **Análise de Causa Raiz** e Priorização de Ações via DMAIC.
-   **Desenvolvimento de um Plano de Controle** para Sustentação do Ganho.

---

## 🧠 Contexto (Storytelling)

Após atuar em um diagnóstico inicial (o projeto predecessor de ML), a abordagem migrou para uma estrutura de **Melhoria Contínua** mais robusta. Minha missão é traduzir os *insights* de dados em **recomendações estatisticamente comprovadas** e um **Plano de Controle** (DMAIC) para a gestão de pessoas.

**Foco Corrigido:** A análise estatística será priorizada nos departamentos de **Finance** e **Marketing**, que apresentam o maior risco de *turnover* (acima da média global de 1,39%).

---

## 🔧 Tecnologias e Ferramentas Utilizadas

-   **Metodologia:** **DMAIC** (Define, Measure, Analyze, Improve, Control) e Six Sigma.
-   **Estatística:** **Regressão Logística** (para Análise de Causa Raiz e $P-Value$), Testes T.
-   **Lean:** Ishikawa, 5 Porquês, Pareto.
-   **Python** (como substituto do Minitab): **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**.
-   **Scikit-learn** (utilizado apenas para a ferramenta estatística Regressão Logística).
-   **Power BI** (Dashboard executivo).
-   **BPMN** (análise da jornada do colaborador).

---

## 🧪 Etapas do Projeto (Ciclo DMAIC)

| Etapa | Foco | Status |
|------|--------|--------|
| **DEFINE** (Objetivo e Escopo) | Definição do problema, Objetivo SMART e Project Charter | ✅ |
| **MEASURE** (Medir Desempenho) | Baseline (Taxas de Turnover) e Capacidade do Processo (RTY) | ✅ |
| **ANALYZE** (Causa Raiz Estatística) | **Regressão Logística** ($P-Value$, Coeficientes) e Ferramentas Lean | ⬜ |
| **IMPROVE** (Melhorar Processo) | Propostas de Ações Corretivas e Planos de Intervenção | ⬜ |
| **CONTROL** (Sustentar o Ganho) | Desenvolvimento do Plano de Controle e Gráficos de Controle | ⬜ |
| **ENTREGA** | Publicação de *case* e Dashboard no Power BI | ⬜ |

---

## 📌 Principais Entregáveis

-   **Análise de Causa Raiz (Regressão Logística):** Coeficientes e *P-Values* de fatores como Salário, Engajamento, Horas Extras, comprovando a significância estatística do risco.
-   **Baseline e RTY:** Medição da capacidade atual do processo de retenção.
-   **Plano de Ação e Controle:** Recomendações estratégicas e Plano de Monitoramento (DMAIC Fases Improve & Control).
-   Mapa da jornada do colaborador (BPMN).
-   Dashboard executivo.

---

## 📈 Impacto Esperado

-   **Redução de 30%** do turnover nos departamentos Finance e Marketing.
-   **Comprovação Estatística** dos principais fatores de risco.
-   **Otimização de Processos** de RH e Gestão de Pessoas.
-   **Redução do Custo de Não-Qualidade** (Custos de Contratação e Treinamento).

---

## 🤝 Autor

**Moisés Ribeiro**  
Especialista em Processos, Melhoria Contínua e Diagnóstico Operacional, com domínio em Dados, Python, SQL e Power BI. 

📎 [LinkedIn](https://www.linkedin.com/in/moisesrsjr/)  
💻 [GitHub](https://github.com/moises-rb)  
✍️ [Medium](https://medium.com/@moises.rsjr)

---

*Este projeto é uma simulação, mas segue práticas reais de People Analytics, Six Sigma e Gestão de Processos, agregando valor de **Melhoria Contínua** ao portfólio.*