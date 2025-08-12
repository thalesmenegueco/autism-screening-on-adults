# Autism Screening on Adults

## Goals
1. Explore ASD's* idiosyncrasies and patterns in it's diagnosis
2. Create a Machine Learning model for finding one's chance to be autistic (based on the same variables) 

> *ASD: Autism Spectrum Disorder

## Project info

### Struture

📁 autism-screening/
├── 📄 README.md
├── 📁 data/ (raw and processed data)
├── 📁 notebooks/ (Jupyter analysis)
├── 📁 visualizations/ (charts and dashboards)
└── 📁 reports/ (final reports)

## Data

### Variables

### Data Source
[Autism Screening on Adults](https://www.kaggle.com/datasets/andrewmvd/autism-screening-on-adults)

## Methodology

## Outcomes

---

## To-do's:

### Basics
- [ ] Create README.md
- [ ] Define workflow/to-do's

### 1. Data Cleaning
- [ ] Data processing
- [ ] Remove duplicates
- [ ] Correct inconsistency
- [ ] Standarize types
> Tools: pandas (Python)

### 2. Exploratory Data Analysis (EDA)
- [ ] Descriptive Statistics: mean, median, standard deviation
- [ ] Identificatoin of patterns and anomalies 
- [ ] Correlations between variables
- [ ] Initial visualizations: histograms, box plots, scatter plots
> Matplotlib and Seaborn (Python)

### 3. Modeling and Statistical Analysis
- [ ] Descriptive Analysis
- [ ] Predictive Analysis
- [ ] Regression Models
> Tools: Scikit-learn (Python)

### 4. Visualization and Sharing of Outcomes
> Tools: Plotly (Python)

---

## 🎯 **Reminder - Framework for a Efficient Data Analysis (pt-BR)**

### **1. O Método das "5 Camadas de Perguntas"**

#### **Camada 1: Contexto e Objetivo**
- **O que estamos tentando resolver?**
- **Qual decisão precisa ser tomada?**
- **Quem vai usar essas informações?**
- **Qual o impacto esperado da análise?**

#### **Camada 2: Exploração Inicial**
- **O que os dados estão me mostrando à primeira vista?**
- **Existem padrões óbvios ou anomalias?**
- **Quais variáveis têm maior variabilidade?**
- **Há dados faltantes ou inconsistências?**

#### **Camada 3: Relacionamentos**
- **Quais variáveis podem estar relacionadas?**
- **Existem correlações interessantes?**
- **Há variáveis que podem ser causais?**
- **Que fatores externos podem influenciar os dados?**

#### **Camada 4: Segmentação**
- **Os padrões são consistentes em todos os grupos?**
- **Existem subgrupos com comportamentos distintos?**
- **Há variações temporais ou geográficas?**
- **Quais são os outliers e por que existem?**

#### **Camada 5: Ação e Validação**
- **O que essas descobertas significam na prática?**
- **Quais ações podem ser tomadas?**
- **Como validar essas conclusões?**
- **Que perguntas ainda precisam ser respondidas?**

---

## 🔍 **Techniques for Choosing Relevant Variables (pt-BR)**

### **Matriz de Priorização de Variáveis**

<table class="data-table">
  <thead>
    <tr>
      <th scope="col">Critério</th>
      <th scope="col">Alto (3)</th>
      <th scope="col">Médio (2)</th>
      <th scope="col">Baixo (1)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Relevância para o Objetivo</strong></td>
      <td>Diretamente relacionada</td>
      <td>Indiretamente relacionada</td>
      <td>Pouco relacionada</td>
    </tr>
    <tr>
      <td><strong>Qualidade dos Dados</strong></td>
      <td>Completos e confiáveis</td>
      <td>Algumas lacunas</td>
      <td>Muitos problemas</td>
    </tr>
    <tr>
      <td><strong>Variabilidade</strong></td>
      <td>Alta variação</td>
      <td>Variação moderada</td>
      <td>Pouca variação</td>
    </tr>
    <tr>
      <td><strong>Acionabilidade</strong></td>
      <td>Pode influenciar decisões</td>
      <td>Influência limitada</td>
      <td>Apenas informativa</td>
    </tr>
  </tbody>
</table>

**Pontuação total de 9-12**: Variável prioritária
**Pontuação de 6-8**: Variável secundária
**Pontuação abaixo de 6**: Considerar exclusão

---

## 🧠 **Analytical Thinking Strategies (pt-BR)**

### **1. Técnica do "Funil Invertido"**
```
Pergunta Ampla → Hipóteses → Variáveis Específicas → Análise Focada
```

**Exemplo prático:**
- **Pergunta ampla**: "Por que as vendas caíram?"
- **Hipóteses**: Sazonalidade, concorrência, qualidade, preço
- **Variáveis**: Período, região, produto, canal, preço
- **Análise focada**: Comparação mês a mês por categoria

### **2. Método CRISP-DM Adaptado**

#### **Business Understanding** 🎯
- Defina o problema em termos de negócio
- Identifique stakeholders e suas necessidades
- Estabeleça critérios de sucesso

#### **Data Understanding** 📊
- Explore a estrutura dos dados
- Identifique relacionamentos preliminares
- Avalie qualidade e completude

#### **Data Preparation** 🔧
- Selecione variáveis relevantes
- Trate valores ausentes e outliers
- Crie variáveis derivadas se necessário

#### **Modeling** 🧮
- Aplique técnicas analíticas apropriadas
- Teste diferentes abordagens
- Valide resultados

#### **Evaluation** ✅
- Interprete resultados no contexto do negócio
- Verifique se objetivos foram atendidos
- Identifique limitações

---

## 🎮 **Exercício Prático: Vamos Aplicar!**

Te proponho um exercício usando um cenário fictício para praticarmos:

### **Cenário:**
|---|


### Uma loja online de eletrônicos notou queda nas vendas nos últimos 3 meses. Você tem acesso a dados de:

| - Vendas por produto/categoria |
|---|


- Dados de tráfego do site
- Informações de clientes
- Dados de marketing
- Avaliações de produtos
- Dados de concorrência

### **Practice (pt-BR)**:

| Usando o framework que apresentei, me diga: |
|---|



1. **Quais seriam suas 3 primeiras perguntas?**
2. **Que variáveis você priorizaria para análise inicial?**
3. **Que relacionamentos você investigaria primeiro?**

---

## 📚 **Recursos para Desenvolver Essa Habilidade**

### **Livros Recomendados**:

| - "Storytelling with Data" - Cole Nussbaumer Knaflic |
|---|


- "The Art of Statistics" - David Spiegelhalter
- "Thinking, Fast and Slow" - Daniel Kahneman

### **Práticas Diárias**:

| - **Questione dados do cotidiano**: Por que esse gráfico de notícia mostra isso? |
|---|


- **Pratique com datasets públicos**: Kaggle, dados.gov.br
- **Documente seu processo de pensamento**: Anote suas hipóteses antes de analisar
