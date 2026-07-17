<div align="center">

# RESUMO SOBRE OS PRINCIPAIS TIPOS DE ANÁLISE DE DADOS

### Análise de Dados 

Os tipos de análise de dados são categorias que definem a finalidade do estudo das informações.

<img src="https://img.shields.io/badge/STATUS-EM%20DESENVOLVIMENTO-success?style=for-the-badge" />
<img src="https://img.shields.io/badge/LICENSE-MIT-blue?style=for-the-badge" />

</div>

---

## 1. Análise Descritiva (Descriptive Analytics)

Pergunta que responde:

> O que aconteceu?

### Objetivo

> Resumir os dados utilizando estatísticas e indicadores.

> É o tipo mais comum em dashboards.

O que faz:

* Calcula KPIs
* Resume informações
* Mede desempenho
* Gera dashboards
  
### Ferramentas
* SQL
* Pandas
* Excel
* Power BI
* Tableau
* Apache Superset

### Técnicas
* Média
* Mediana
* Moda
* Percentuais
* Frequências
* KPIs
* Estatísticas descritivas

### Exemplo
Uma loja deseja saber:

* Receita total
* Ticket médio
* Quantidade de clientes
* Produto mais vendido
* Estado com maior faturamento

Resultado:

"O faturamento total foi de R$ 5 milhões."

## 2. Análise Diagnóstica (Diagnostic Analytics)

Pergunta que responde:

> Por que aconteceu?

O que faz:
* Compara grupos
* Investiga causas
* Procura fatores relacionados

### Objetivo

> Descobrir as causas dos resultados observados.

### Técnicas
* Drill-down
* Comparações
* Correlações
* Testes estatísticos
* Segmentações
* Análise por região
* Análise por cliente
* Root Cause Analysis

### Ferramentas
* SQL
* Pandas
* Scipy
* Statsmodels

### Exemplo

"O faturamento caiu porque as vendas da categoria Electronics diminuíram 25%."

## 3. Análise Preditiva (Predictive Analytics)

Pergunta que responde:

> O que provavelmente acontecerá?

### Objetivo

> Prever eventos futuros utilizando modelos estatísticos e Machine Learning.

### Exemplos
* Previsão de vendas
* Previsão de demanda
* Churn Prediction
* Forecast
* Séries temporais

### Ferramentas
* Scikit-learn
* XGBoost
* LightGBM
* Prophet
* TensorFlow

### Técnicas
* Regressão
* Árvores
* Random Forest
* Redes neurais

### Exemplo
Prever:

* Vendas do próximo mês
* Demanda
* Churn
* Inadimplência

Resultado:

"As vendas deverão crescer aproximadamente 12%."

## 4. Análise Prescritiva (Prescriptive Analytics)

Pergunta que responde:

> O que deve ser feito?

### Objetivo

> Sugerir ações para atingir determinado objetivo.

### Exemplos
* Melhor preço
* Melhor estoque
* Melhor rota
* Melhor campanha
* Melhor fornecedor

### Ferramentas
* OR-Tools
* PuLP
* Pyomo
* Gurobi

### Técnicas
* Otimização
* Programação Linear
* Simulação

### Exemplo
Uma empresa deseja minimizar custos de transporte.

O algoritmo recomenda:

* Mudar rotas
* Alterar fornecedores
* Redistribuir estoques

## 5. Análise Exploratória (Exploratory Data Analysis — EDA)

Pergunta que responde:

> O que existe nos dados?

### Objetivo

> Conhecer os dados antes de qualquer modelagem ou tomada de decisão.

> É a primeira etapa de praticamente qualquer projeto de análise de dados.

O que faz: 

* Entende a estrutura do dataset
* Verifica tipos de dados
* Identifica valores nulos
* Procura duplicidades
* Detecta outliers
* Analisa distribuições
* Busca padrões
* Identifica inconsistências

### Ferramentas
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly
* Altair

### Técnicas
* Histograma
* Boxplot
* Scatter Plot
* Heatmap
* Pair Plot
* Correlação

### Exemplo
Uma empresa recebe uma base com 1 milhão de vendas.

Primeiro deseja descobrir:

* Existem dados faltantes?
* Existem produtos duplicados?
* Existem preços negativos?
* Quais categorias existem?
* Existem valores extremos?

## 6. Análise Inferencial

Pergunta que responde:

> Os resultados observados representam a população?

> Baseia-se em probabilidade.

### Objetivo

> Generalizar conclusões obtidas em uma amostra.

O que faz:

* Testa hipóteses
* Mede significância
* Calcula intervalos de confiança

### Ferramentas
* Scipy
* Statsmodels
* R

### Técnicas
* Teste t
* ANOVA
* Qui-quadrado
* Valor-p
* Intervalo de confiança

### Exemplo

Uma empresa entrevista 1.000 clientes.

Pergunta:

A satisfação média dessa amostra representa todos os clientes?

## 7. Análise Causal

Pergunta que responde:

> O que causou esse resultado?

### Objetivo

> Identificar relações de causa e efeito.

Importante:

Correlação não implica causalidade.

### Ferramentas
* DoWhy
* EconML
* CausalML
* Python

### Técnicas
* Teste A/B
* Randomização
* Experimentos

### Exemplo

Uma empresa oferece:

desconto de 10%
desconto de 20%

Pergunta:

O desconto realmente aumentou as vendas?

## 8. Análise Estatística

É um termo bastante amplo.

Inclui:

* Média
* Mediana
* Moda
* Desvio padrão
* Variância
* Distribuição
* Curtose
* Assimetria
* Regressão

A Estatística Descritiva faz parte dela.

## 9. Análise Multivariada

Pergunta que responde:

> Como várias variáveis se relacionam simultaneamente?

### Objetivo

> Estudar relações entre múltiplas variáveis.

### Ferramentas
* Scikit-learn
* Statsmodels

### Técnicas
* PCA
* Regressão múltipla
* Clusterização
* Fatoração

### Exemplo

Relacionar:

* Idade
* Salário
* Escolaridade
* Consumo

## 10. Análise de Séries Temporais

Pergunta que responde:

> Como os dados evoluem ao longo do tempo?

### Objetivo

> Encontrar padrões temporais.

### Técnicas

* Tendência
* Sazonalidade
* Ciclos
* Forecast

### Ferramentas
* Prophet
* ARIMA
* SARIMA

### Exemplo

Prever vendas dos próximos 12 meses.

## 11. Análise Espacial (Geoespacial)

Pergunta que responde:

> Onde os eventos acontecem?

### Objetivo

> Analisar a distribuição geográfica.

### Ferramentas
* GeoPandas
* Folium
* Plotly
* ArcGIS

### Técnicas
* Mapas
* Choropleth
* Heatmaps geográficos
* Distribuição por região

### Exemplo
Quais estados possuem maior faturamento?

Como os dados variam no espaço?

## 12. Análise de Segmentação

Pergunta que responde:

> Quais grupos semelhantes existem?

### Objetivo

> Dividir clientes, produtos ou regiões em grupos.

> Agrupar clientes, produtos ou regiões com características parecidas.

### Ferramentas
* Scikit-learn

### Técnicas
* K-Means
* DBSCAN
* Hierárquico
* RFM
* Clusterização
* RFM
* Personas
* Segmentação de mercado

### Exemplo
Separar clientes em:

* Premium
* Frequentes
* Ocasionais
* Inativos

## 13. Análise de Sobrevivência

Muito usada em Medicina e Marketing.

Pergunta que responde:

Quanto tempo até um evento ocorrer?

### Exemplos

* Tempo até cancelamento
* Tempo até churn
* Tempo até falha

## 14. Análise de Anomalias

### Objetivo

Encontrar comportamentos incomuns.

### Exemplos

* Fraudes
* Erros
* Compras suspeitas
* Ataques

## 15. Análise de Redes (Network Analysis)

Usada para estudar relações.

### Exemplos

* Redes sociais
* Cadeias de suprimentos
* Relacionamentos entre clientes

## 16. Análise de Texto (Text Analytics)

### Exemplos

* NLP
* Sentimentos
* Classificação
* Resumos
* Extração de palavras-chave

## 17. Análise em Tempo Real (Streaming Analytics)

### Exemplos

* Sensores
* IoT
* Monitoramento
* Fraudes bancárias
* Mercado financeiro

---

## Resumo
| Tipo de análise |	Pergunta principal | Exemplos |
| --------------- | ------------------ | -------- |
| Exploratória (EDA) | O que existe nos dados? | Qualidade, padrões, gráficos, outliers |
| Descritiva | O que aconteceu? | KPIs, dashboards, estatísticas |
| Diagnóstica | Por que aconteceu? | Correlação, comparações, causa provável |
| Inferencial | Isso vale para toda a população? | Testes de hipótese, intervalos de confiança |
| Causal | O que causou isso? | Testes A/B, experimentos |
| Preditiva | O que vai acontecer? | Machine Learning, previsão |
| Prescritiva | O que devemos fazer? | Otimização, recomendações |
| Multivariada | Como as variáveis se relacionam? | PCA, regressão múltipla, clusters |
| Séries Temporais | Como os dados evoluem no tempo? | Tendências, sazonalidade, forecast |
| Geoespacial | Onde isso acontece? | Mapas, análise regional |
| Segmentação | Quais grupos existem? | RFM, clusterização |
| Anomalias | O que foge do padrão? | Fraudes, outliers |
| Sobrevivência | Quando um evento ocorrerá? | Churn, falhas |
| Redes | Como os elementos se conectam? | Grafos, redes sociais |
| Texto (NLP) | O que os textos dizem? | Sentimento, classificação, tópicos |
| Tempo Real | O que está acontecendo agora? | Streaming, monitoramento |
