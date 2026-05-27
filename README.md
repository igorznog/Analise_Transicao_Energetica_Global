# 🚚 Análise de Cancelamentos e Tempo de Entrega em Delivery

## 📌 Sobre o Projeto

Este projeto foi desenvolvido com o objetivo de analisar os principais fatores que impactam cancelamentos de pedidos e desempenho operacional em plataformas de delivery.

Utilizando um dataset com mais de 100 mil registros operacionais, o projeto explora padrões logísticos, eficiência operacional, impacto do trânsito, performance das entregas e comportamento dos cancelamentos através de técnicas de Data Analytics, Business Intelligence e Machine Learning.

Além da análise exploratória, também foi desenvolvido um dashboard interativo no Power BI para fornecer insights executivos e monitoramento operacional dinâmico.

O projeto inclui ainda uma etapa de Machine Learning voltada para previsão de cancelamentos, simulando um cenário real de negócio onde os dados são utilizados não apenas para entender problemas, mas também para antecipar riscos operacionais.

---

# 📂 Informações do Dataset

O dataset utilizado contém informações operacionais e logísticas de uma plataforma de delivery.

## 📌 Principais Colunas do Dataset

- Order_ID
- User_ID
- Restaurant_ID
- Driver_ID
- Item_Name
- Quantity
- Total_Price
- Order_Time
- Delivery_Time
- Delivery_Duration_Minutes
- City
- Payment_Method
- Order_Status
- Driver_Vehicle
- Restaurant_Lat
- Restaurant_Lon
- Customer_Lat
- Customer_Lon
- Driver_Lat
- Driver_Lon
- Delivery_Distance_km
- Traffic_Level
- Driver_Availability

---

## 📌 Informações Gerais

- Mais de 100 mil registros de entregas
- Dados operacionais e logísticos
- Variáveis numéricas e categóricas
- Dados relacionados a clientes, entregadores, restaurantes e pedidos

---

# 🎯 Objetivos do Projeto

- Analisar fatores relacionados aos cancelamentos de pedidos
- Identificar fatores operacionais que impactam o tempo de entrega
- Entender o impacto do trânsito na performance logística
- Criar KPIs executivos para monitoramento operacional
- Desenvolver dashboards interativos no Power BI
- Aplicar técnicas de Machine Learning para análise preditiva
- Simular um cenário real de negócio no setor logístico

---

# 📊 Principais KPIs

- Total de Pedidos
- Taxa de Cancelamento
- Taxa de Entregas
- Tempo Médio de Entrega

---

# 📈 Análise Exploratória de Dados

## 🔹 Taxa de Cancelamento por Cidade
Identificação das cidades com maior percentual de cancelamentos.

## 🔹 Tempo Médio de Entrega por Nível de Trânsito
Análise do impacto operacional causado pelo tráfego.

## 🔹 Tempo Médio de Entrega por Tipo de Veículo
Comparação entre motos, bicicletas e carros.

## 🔹 Relação entre Distância e Tempo de Entrega
Avaliação da eficiência logística e padrões operacionais.

## 🔹 Distribuição dos Status dos Pedidos
Visualização da proporção entre pedidos entregues e cancelados.

---

# 🤖 Machine Learning

O projeto também inclui uma etapa de Machine Learning voltada para previsão de cancelamentos de pedidos.

O objetivo foi simular um cenário real de negócio, onde modelos preditivos ajudam empresas de delivery a antecipar problemas operacionais e reduzir perdas.

---

## 📌 Variável Target

Foi criada uma variável target chamada:

```python
Target_Cancelled
```

Onde:

- `1` → Pedido Cancelado
- `0` → Pedido Entregue

---

## 📌 Variáveis Utilizadas no Modelo

Principais variáveis utilizadas para predição:

- Delivery_Distance_km
- Traffic_Level
- Driver_Vehicle
- Quantity
- Total_Price
- Delivery_Duration_Minutes

---

## 📌 Etapas do Machine Learning

- Limpeza de Dados
- Engenharia de Features
- Encoding de Variáveis Categóricas
- Separação Treino/Teste
- Treinamento do Modelo
- Avaliação de Performance

---

## 📌 Objetivo do Modelo

Prever a probabilidade de cancelamento de pedidos com base em fatores operacionais e logísticos.

---

## 📌 Resultado

O modelo preditivo permitiu identificar padrões operacionais relacionados aos cancelamentos e demonstrou como técnicas de Machine Learning podem auxiliar na tomada de decisão em operações logísticas.

---

# 📊 Dashboard Power BI

O dashboard foi desenvolvido com foco executivo e operacional, permitindo análises dinâmicas e interativas através de filtros e KPIs.

---

## 🔹 Funcionalidades do Dashboard

- Filtros por cidade
- Filtros por veículo
- Filtros por trânsito
- Filtros por método de pagamento
- KPIs executivos
- Gráficos interativos
- Insights operacionais

---

# 📸 Preview do Dashboard

Imagem do dashboard disponível no repositório:

- dashboard_preview.jpeg

---

# 🎥 Demonstração do Dashboard

Um vídeo demonstrando a navegação e interação com o dashboard está disponível neste repositório.

---

# 📌 Principais Insights

- A taxa de cancelamento permaneceu próxima de 10%
- O nível de trânsito apresentou impacto operacional significativo
- O tempo de entrega variou conforme trânsito e tipo de veículo
- Algumas cidades apresentaram taxas de cancelamento acima da média geral
- Distância e duração da entrega demonstraram padrões logísticos consistentes

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
 ├── 📄 Análise_Operacional_de_Delivery.ipynb
 ├── 📄 Dashboard.pbix
 ├── 📄 dashboard_preview.jpeg
 ├── 📄 Dashboard-video.mp4
 ├── 📄 base_operacional_delivery_talabat.csv
 ├── 📄 dashboard-link.md
 └── 📄 README.md
```

---

# 🧠 Conclusão

Este projeto transformou dados operacionais de delivery em insights estratégicos para tomada de decisão.

Através de análise exploratória, dashboards interativos e modelos preditivos, foi possível identificar padrões operacionais relacionados aos cancelamentos e desempenho logístico.

Além da análise técnica, o projeto simula um cenário real de logística, aplicando conceitos de Business Intelligence, Data Analytics, Machine Learning e monitoramento operacional.

---

# 🔗 Acesso ao Dashboard

O link do dashboard online está disponível em:

```bash
dashboard-link.md
```

---

# ⭐ Considerações Finais

Projeto desenvolvido para estudo, portfólio e aplicação prática em:

- Data Analytics
- Business Intelligence
- Machine Learning
- Análise Logística

---
