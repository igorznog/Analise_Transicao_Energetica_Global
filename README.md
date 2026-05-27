# 🚚 Delivery Cancellation Analysis & Logistics Dashboard

## 📌 Sobre o Projeto

Este projeto foi desenvolvido com o objetivo de analisar os principais fatores que impactam cancelamentos e desempenho operacional em plataformas de delivery.

A análise foi realizada utilizando mais de 100 mil registros de pedidos, explorando métricas operacionais, padrões de comportamento e variáveis logísticas.

Além da análise exploratória, o projeto também conta com um dashboard executivo desenvolvido no Power BI, permitindo visualização interativa dos principais KPIs e insights do negócio.

O projeto também inclui uma etapa de Machine Learning para previsão de cancelamentos, simulando um cenário real de aplicação de Data Science no setor logístico.

---

# 🎯 Objetivos do Projeto

- Identificar fatores relacionados aos cancelamentos de pedidos
- Entender impactos de trânsito, distância e tipo de veículo
- Criar KPIs executivos para monitoramento operacional
- Desenvolver visualizações interativas no Power BI
- Aplicar técnicas de Machine Learning
- Simular um cenário real de análise de dados aplicada a logística

---

# 📊 Principais KPIs

- Total de Pedidos
- Taxa de Cancelamento
- Taxa de Entregas
- Tempo Médio de Entrega

---

# 📈 Principais Análises Realizadas

## 🔹 Taxa de cancelamento por cidade
Identificação das cidades com maior percentual de pedidos cancelados.

## 🔹 Cancelamento por nível de trânsito
Análise do impacto operacional causado pelo tráfego.

## 🔹 Tempo médio de entrega por veículo
Comparação entre bicicletas, carros e motos.

## 🔹 Relação entre distância e tempo de entrega
Avaliação da influência logística nas entregas.

## 🔹 Distribuição dos status dos pedidos
Visualização da proporção entre pedidos entregues e cancelados.

---

# 🤖 Machine Learning

Além da análise exploratória e do dashboard executivo, o projeto também contou com uma etapa de Machine Learning voltada para previsão de cancelamentos de pedidos.

O objetivo foi simular um cenário real de negócio, onde modelos preditivos podem auxiliar empresas de delivery a antecipar problemas operacionais e reduzir perdas.

---

## 📌 Variável Target

Foi criada a variável:

```python
Target_Cancelled
```

Onde:

- `1` → Pedido cancelado
- `0` → Pedido entregue

---

## 📌 Variáveis Utilizadas no Modelo

As principais variáveis utilizadas foram:

- Delivery_Distance_km
- Traffic_Level
- Driver_Vehicle
- Quantity
- Total_Price
- Delivery_Duration_Minutes

---

## 📌 Etapas Realizadas

- Tratamento de dados
- Engenharia de atributos
- Encoding de variáveis categóricas
- Separação treino/teste
- Treinamento do modelo
- Avaliação de métricas

---

## 📌 Objetivo do Modelo

Prever a probabilidade de cancelamento de pedidos com base em fatores operacionais e logísticos.

---

## 📌 Resultado

O modelo permitiu identificar padrões relacionados aos cancelamentos, contribuindo para análises mais estratégicas e simulação de aplicações reais de Data Science no setor logístico.

---

# 🛠️ Tecnologias Utilizadas

## 📌 Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

## 📌 Business Intelligence
- Power BI

## 📌 Ambiente
- Google Colab

---

# 📂 Estrutura do Projeto

```bash
📁 delivery-cancellation-analysis
 ├── 📄 delivery_analysis.ipynb
 ├── 📄 delivery_dashboard.pbix
 ├── 📄 dataset.csv
 ├── 📁 images
 ├── 📄 README.md
```

---

# 📊 Dashboard Power BI

O dashboard foi desenvolvido com foco executivo e operacional, permitindo análise dinâmica através de filtros interativos.

## 🔹 Funcionalidades

- Segmentação por cidade
- Segmentação por veículo
- Segmentação por trânsito
- Segmentação por método de pagamento
- Visualização de KPIs executivos
- Gráficos interativos

---

# 📌 Principais Insights

- A taxa de cancelamento ficou próxima de 10%
- O trânsito apresentou impacto operacional relevante
- O tempo médio de entrega permaneceu relativamente estável entre veículos
- Algumas cidades apresentaram taxas de cancelamento superiores à média geral
- A relação entre distância e tempo demonstrou comportamento operacional consistente

---

# 🧠 Conclusão

O projeto permitiu transformar dados operacionais em insights relevantes para tomada de decisão.

A utilização de análise exploratória, dashboards interativos e modelos preditivos possibilitou identificar padrões importantes relacionados aos cancelamentos e desempenho logístico.

Além do aspecto analítico, o projeto também simulou um cenário real de negócio, aplicando conceitos de Business Intelligence, visualização de dados, Machine Learning e análise operacional.

---

# 📸 Dashboard Preview

## 🔹 Adicione aqui prints do dashboard

Exemplo:

- KPIs principais
- Análise por cidade
- Análise operacional
- Filtros interativos

---

# 🔗 Contato

## 📌 LinkedIn
Adicione aqui seu LinkedIn

## 📌 GitHub
Adicione aqui seu GitHub

---

# ⭐ Projeto desenvolvido para fins de estudo e portfólio em Data Analytics, Business Intelligence e Machine Learning.
