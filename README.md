# Projeto RevOps — Análise de Marketing e Vendas (B2B)

Este projeto simula uma análise completa de RevOps (Revenue Operations) para uma empresa B2B que vende treinamentos executivos para outras empresas.

O objetivo é identificar gargalos no funil de marketing e vendas, analisar eficiência comercial e gerar recomendações estratégicas orientadas a dados, com foco em crescimento previsível de receita.

---

## Objetivos do Projeto

- Analisar métricas de marketing e vendas dos últimos 6 meses
- Identificar gargalos no funil (Lead → Venda)
- Avaliar eficiência comercial e capacidade do time de vendas
- Analisar receita, mix de produtos e potencial de crescimento
- Gerar insights estratégicos e recomendações executivas

---

## Contexto da Empresa (Simulação)

- Segmento: Treinamentos Executivos B2B  
- Modelo comercial: Venda consultiva  
- Time:
  - 2 SDRs
  - 2 Closers
- Investimento mensal em tráfego: R$ 2.000 a R$ 2.500
- Canais: LinkedIn Ads, Google Ads e Instagram Ads
- Volume médio de vendas: 12 a 18 por mês
- Portfólio:
  - Produto de entrada
  - Produto intermediário
  - Produto premium

---

## Metodologia RevOps Utilizada

O projeto segue uma abordagem prática de RevOps, conectando Marketing, Vendas e Receita:

1. Exploração e validação dos dados
2. Análise do funil de conversão
3. Identificação de gargalos operacionais
4. Análise de receita, ticket médio e mix de produtos
5. Geração de recomendações estratégicas orientadas a dados

---

## Stack Tecnológica

- Python
- Pandas
- Matplotlib
- Jupyter Notebook
- Git / GitHub

---

## Estrutura do Projeto

```text
revops-executive-training-analysis/
│
├── data/
│   ├── raw/              # Dados brutos
│   └── processed/        # Dados tratados
│
├── notebooks/
│   ├── 01_data_exploration.ipynb
│   ├── 02_funnel_analysis.ipynb
│   ├── 03_revenue_analysis.ipynb
│   └── 04_recommendations.ipynb
│
├── reports/
│   ├── revops_diagnostic_report.md
│   └── revops_executive_summary.pdf
│
├── src/
│   ├── data_loader.py
│   ├── metrics.py
│   └── visualizations.py
│
├── README.md
├── requirements.txt
└── .gitignore
