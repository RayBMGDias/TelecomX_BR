# 📊 Análise de Evasão de Clientes (Churn) - TelecomX

> Este projeto visa aprofundar a compreensão dos motivos que levam os clientes da TelecomX a cancelarem seus serviços. Através da análise dos dados, nosso objetivo é identificar os principais fatores de evasão (churn), traçar o perfil dos clientes que mais cancelam e, com base nesses insights, sugerir ações estratégicas para aumentar a retenção e reduzir o churn.
***
## Objetivo

- Identificar os principais motivos que levam os clientes a cancelarem.

- Analisar o perfil dos clientes com maior probabilidade de evasão.

- Propor ações estratégicas fundamentadas em dados para combater o churn.

***
## Estrutura do Projeto

- O projeto está estruturado em um único notebook, TelecomX_BR.ipynb, que abrange todas as fases da análise.
- *link do dado utilizado:* "https://raw.githubusercontent.com/ingridcristh/challenge2-data-science/refs/heads/main/TelecomX_Data.json"

## Limpeza e Tratamento de Dados

> Nesta etapa inicial, realizamos a correção de dados inconsistentes, como a conversão da coluna TotalCharges de texto para o formato numérico (float).

> Criação de Variáveis: Foram criadas novas variáveis para enriquecer a análise, como o total de gastos do cliente (Charges_Total) e a média de gastos diários (Contas_Diarias).

> Análise Exploratória de Dados (EDA): O notebook detalha a exploração dos dados, utilizando visualizações para identificar padrões, correlações e os principais fatores que influenciam a evasão.
  
***
## Principais Insight
  
*Contratos Mensais:* Clientes com contratos mensais apresentam o maior risco de cancelamento.

*Tempo de Contrato (Tenure):* Este é o fator mais relevante. Quanto maior o tempo de contrato, menor a probabilidade de evasão.

*Perfil do Cliente:* A variável SeniorCitizen tem pouca influência na decisão de churn.

*Correlações:* Foi identificada uma forte correlação de 0.83 entre o tempo de contrato (tenure) e o total de gastos (Charges_Total). Além disso, há uma correlação perfeita (1.0) entre Charges_Monthly e Contas_Diarias, indicando redundância.

***
## 💡 Conclusões e Recomendações
  
> Com base na análise, estas são as recomendações para reduzir o churn:

- Incentivar Contratos de Longo Prazo: Ofereça descontos ou benefícios exclusivos para clientes que optarem por contratos anuais ou bienais.

- Programas de Fidelização: Crie programas de fidelidade para engajar e reter novos clientes desde o início.

- Monitoramento de Clientes de Risco: Implemente um sistema de alertas para identificar e monitorar clientes com perfil de alto risco, permitindo ações proativas para evitar o cancelamento.

- Otimização de Pacotes: Avalie e simplifique as ofertas de serviços para melhorar a experiência do cliente e a retenção.

- Ajuste de Modelos Analíticos: Para futuras análises e modelos preditivos, remova variáveis redundantes e altamente correlacionadas para otimizar o desempenho.
  
***
## 🛠️ Tecnologias Utilizadas
  
- Linguagem: Python

- Bibliotecas: Pandas, NumPy, Matplotlib, Seaborn

- Ambiente: Google Colab

 *** 
#👤 Autor
Autor: Rayra Bandeira
