# 🟦 RH Analytics – Diagnóstico de Causa Raiz de Turnover (Metodologia DMAIC)

Este é um projeto simulado que faz parte da minha trilha prática em Ciência de Dados aplicada ao RH (People Analytics). O objetivo é aplicar a metodologia **DMAIC (Six Sigma)** com foco em **Estatística Descritiva e Analítica** (similar ao Minitab) para resolver o problema de alta taxa de desligamento (*turnover*) nos primeiros 90 dias.

O projeto combina **Análise Estatística, DMAIC e Causa Raiz** para migrar de um problema de **Predição** (Machine Learning) para uma solução de **Melhoria Contínua** (Processos e RH).

---

## 🎯 Objetivo e Escopo (FASE DEFINE)

A meta é **reduzir a Taxa de Turnover de 90 dias nos departamentos de Finance e Marketing em 30%** nos próximos 6 meses.

O projeto foca em:

- **Confirmação Estatística** dos fatores de risco (Regressão Logística).
- **Quantificação do Risco** e da capacidade atual do processo (Baseline e RTY).
- **Análise de Causa Raiz** e Priorização de Ações via DMAIC.
- **Desenvolvimento de um Plano de Controle** para Sustentação do Ganho.

---

## 🧠 Contexto (Storytelling)

Após uma análise inicial que identificou a **Taxa de Turnover de 90 dias** como a **Métrica Primária (Y)**, a abordagem migrou para uma estrutura mais robusta e focada em processos, utilizando o **DMAIC**. Minha missão é traduzir os *insights* de dados em **recomendações estatisticamente comprovadas** e um **Plano de Controle** para a gestão de pessoas.

**Foco Corrigido:** A análise estatística será priorizada nos departamentos de **Finance** e **Marketing**, que apresentam o maior risco de *turnover* (acima da média global de 1,39%).

---

## 🔧 Tecnologias e Ferramentas Utilizadas

- **Metodologia:** **DMAIC** (Define, Measure, Analyze, Improve, Control) e Six Sigma.
- **Estatística:** **Regressão Logística** (para Análise de Causa Raiz e $P-Value$), Testes T.
- **Lean:** Ishikawa, 5 Porquês, Pareto.
- **Python** (como substituto do Minitab): **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**.
- **Scikit-learn** (utilizado apenas para a ferramenta estatística Regressão Logística).
- **Power BI** (Dashboard executivo).
- **BPMN** (análise da jornada do colaborador).

---

## 📁 Estrutura do Projeto

📦 turnover-dmaic-project
├── data/ # Dados brutos e tratados
├── notebooks/ # EDA, Análise (Regressão Logística) e visualizações
├── dmaic_documents/ # **Documentos de Causa Raiz, Ishikawa e Plano de Controle**
├── dashboard/ # Arquivos do Power BI
├── models/ # Modelo de RF e Regressão Logística (para reuso)
└── README.md # Documentação geral do projeto

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

- **Análise de Causa Raiz (Regressão Logística):** Coeficientes e *P-Values* de fatores como Salário, Engajamento, Horas Extras, comprovando a significância estatística do risco.
- **Baseline e RTY:** Medição da capacidade atual do processo de retenção.
- **Plano de Ação e Controle:** Recomendações estratégicas e Plano de Monitoramento (DMAIC Fases Improve & Control).
- Mapa da jornada do colaborador (BPMN).
- Dashboard executivo.

---

## 📈 Impacto Esperado

- **Redução de 30%** do turnover nos departamentos Finance e Marketing.
- **Comprovação Estatística** dos principais fatores de risco.
- **Otimização de Processos** de RH e Gestão de Pessoas.
- **Redução do Custo de Não-Qualidade** (Custos de Contratação e Treinamento).

---

## 🤝 Autor

**Moisés Ribeiro**  
Especialista em Processos, Melhoria Contínua e Diagnóstico Operacional, com domínio em Dados, Python, SQL e Power BI. 

📎 [LinkedIn](https://www.linkedin.com/in/moisesrsjr/)  
💻 [GitHub](https://github.com/moises-rb)  
✍️ [Medium](https://medium.com/@moises.rsjr)

---

*Este projeto é uma simulação, mas segue práticas reais de People Analytics, Six Sigma e Gestão de Processos, agregando valor de **Melhoria Contínua** ao portfólio.*