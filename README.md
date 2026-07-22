# 📊 Tech Challenge - Fase 1: Análise Executiva de Vendas e Logística Olist

## 🎯 Objetivo do Projeto
Este projeto analisa o desempenho comercial, a eficiência logística e os fatores de satisfação do cliente da plataforma **Olist** (dataset público de e-commerce brasileiro com ~100 mil pedidos entre 2016 e 2018). 

O foco da análise é responder à seguinte **Pergunta Norteadora**:
> *"Como a eficiência logística regional impacta a receita e a satisfação do cliente no e-commerce brasileiro, e quais ações estratégicas devem ser tomadas?"*

---

## 🖥️ Dashboard Executivo Interativo
Clique no link abaixo para navegar pelo painel completo e interativo desenvolvido no Tableau Public:
👉 **[Acessar Dashboard Executivo no Tableau Public](https://public.tableau.com/views/DashboardExecutivoOlist-TechChallenge/DashboardExecutivo-Olist?:language=pt-BR&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)**

---

## 💡 Principais Insights e Descobertas de Negócio

### 1. Desempenho Comercial & Volume (GMV)
* **Receita Total (GMV):** R$ 20,47 Milhões gerados no período analisado.
* **Volume de Vendas:** 99.441 pedidos únicos processados, com ticket médio de **R$ 180,50**.
* **Sazonalidade:** Crescimento constante ao longo de 2017 e 2018, com pico histórico expressivo na **Black Friday de Novembro/2017**.

### 2. Gargalo Logístico Regional (SLA de Entrega)
* **Discrepância Geográfica:** O tempo médio de entrega varia de forma crítica entre os estados brasileiros.
* Enquanto no Sudeste/Sul (ex: SP) a entrega média leva **~8 a 11 dias**, em estados do Norte e Nordeste (ex: RR, AP, AM) o tempo médio ultrapassa **28 dias**.

### 3. Impacto Severo na Satisfação (Review Score)
* A pontualidade é o principal *driver* de avaliação do cliente.
* Pedidos entregues **No Prazo** sustentam uma nota média excelente de **4,2 / 5,0**.
* Pedidos com **Atraso** sofrem uma queda drástica na percepção de valor, caindo para **2,3 / 5,0** (uma redução de ~45% na satisfação).

---

## 📌 Recomendações Estratégicas para Acionistas/Investidores

1. **Hubs de Distribuição Avançados (Foco Norte/Nordeste):** Estabelecer parcerias com operadores logísticos regionais em RR, AP e AM para reduzir o tempo médio de trânsito em até 40%.
2. **Gestão Preventiva de Capacidade (Picos de Demanda):** Aumentar a reserva operacional de transporte antes do quarto trimestre (Q4) para absorver o gargalo da Black Friday sem gerar ondas de atrasos subsequentes.
3. **Plano de Retenção de Clientes:** Implementar alertas de atraso preditivo e compensação proativa para pedidos fora do prazo, minimizando a queda de nota e evitando a perda de clientes (*churn*).

---

## 🛠️ Tecnologias Utilizadas
* **Python (Pandas, NumPy):** Limpeza, tratamento de nulos, junção de bases relacionais e engenharia de variáveis (`Dias Entrega Real`, `No Prazo`).
* **Tableau Public:** Construção do Dashboard Executivo interativo, gráficos e storytelling visual.
* **Git & GitHub:** Versionamento e documentação da solução.

---

## 📂 Estrutura do Repositório
```text
├── Notebook Tech_Challenge_fase_1.ipynb   # Script Python com ETL dos dados
└── README.md                             # Relatório executivo e documentação

Projeto desenvolvido para o Tech Challenge - PosTech FIAP por Matheus Gonçalves.
