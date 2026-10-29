# analise-custo-energia-2025-2027
Projeto de Análise Preditiva e Sazonal do Custo de Energia Elétrica (2025-2027).
# Análise Preditiva e Sazonal do Custo de Energia Elétrica (2025-2027)

* **Curso/Módulo:** Google Looker Studio para Análise de Dados[cite: 2]
* **Projeto de Parceria:** Semantix[cite: 2]
* **Aluno:** [Seu Nome Completo][cite: 2]

---

## 📋 Etapa 1: Definição do Problema e Objetivo

### 1. Definição do Problema
O desafio central do consumidor reside na imprevisibilidade dos gastos variáveis com energia elétrica. A dificuldade em prever o valor da próxima conta de luz impede o controle orçamentário eficaz, levando a picos de despesa inesperados. O cliente não consegue discernir se esses picos são causados por maus hábitos, falha de equipamento ou sazonalidade climática[cite: 2].

### 2. Objetivo do Projeto
O objetivo principal é aprimorar o planejamento financeiro do consumidor, transformando dados variáveis em informações previsíveis[cite: 2]:
* **Previsão de Alto Nível:** Criar um modelo preditivo capaz de estimar o consumo de energia e o custo total para o período futuro (2025-2027)[cite: 2].
* **Validação de Causa:** Identificar e quantificar o Fator Chave que impulsiona a variação do consumo mensal[cite: 2].
* **Ferramenta Interativa:** Desenvolver um Dashboard no Looker Studio que apresente a análise de forma clara, visual e interativa[cite: 2].

### 3. Insight Inicial e Hipótese
* **Insight Inicial:** O consumo de energia está diretamente relacionado à sazonalidade do clima, devido ao uso de aparelhos de refrigeração e aquecimento[cite: 2].
* **Hipótese Central:** Existe uma correlação positiva extremamente forte entre a Temperatura Média Mensal e o Consumo de Energia (kWh)[cite: 2].

---

## 📊 Etapa 2: Metodologia de Dados

* **Ferramenta de Geração:** Python (simulação de dados para o período de Janeiro de 2025 a Dezembro de 2027)[cite: 2].
* **Tarifas de Energia:** Simulação com valor fixo de R$ 0,70/kWh (base ANEEL) para isolar o impacto da variação do consumo[cite: 2].
* **Dados Climáticos:** Simulação sazonal via função senoidal (base INMET) recriando picos de verão e vales de inverno[cite: 2].

---

## 📈 Etapa 3: Dashboards Interativos (Looker Studio)

Você pode acessar os relatórios interativos desenvolvidos para este projeto através dos links abaixo:
* [Visualização de Dados - Looker Studio (Link 1)](https://lookerstudio.google.com/reporting/d959ac76-5afc-4eef-b479-9f5b62af2a70/page/5lwcF)[cite: 1]
* [Visualização de Dados - Looker Studio (Link 2)](https://lookerstudio.google.com/reporting/c9067f61-7102-4460-9c84-3edd325ba20d/page/p_8qbikdb8wd)[cite: 1]
* [Visualização de Dados - Looker Studio (Link 3)](https://lookerstudio.google.com/reporting/034ac3a6-92cf-444d-bcda-b1e65cc499b2/page/p_bjlfjs7sxd)[cite: 1]

---

## 💡 Etapa 4: Relatório Final de Insights e Soluções

### 1. Resumo dos Principais Achados
* **Validação da Correlação:** O gráfico de série temporal demonstrou o padrão cíclico de sazonalidade, onde os picos de consumo coincidem perfeitamente com os picos de temperatura[cite: 2].
* **Sazonalidade do Consumo:** Identificou-se que os meses de Verão (Dezembro, Janeiro e Fevereiro) são os períodos de maior risco de despesa[cite: 2].
* **Tendência de Custos:** A análise anual para 2025-2027 mostra custos estáveis sob a mesma condição tarifária, permitindo um provisionamento financeiro seguro[cite: 2].

### 2. Sugestão de Ação (Alerta de Orçamento Preditivo)
Implementação de um mecanismo de alerta no sistema que avisa o usuário quando o custo projetado exceder um limite de tolerância (ex: 10% acima da média anual), permitindo ações preventivas como ajuste no ar-condicionado[cite: 2].
