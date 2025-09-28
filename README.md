# Dashboard Financeiro - Demonstração do Resultado do Exercício (DRE)

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black) ![Power Query](https://img.shields.io/badge/Power%20Query-107C41?style=for-the-badge&logo=microsoft-excel&logoColor=white) ![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)

## 🎯 Sobre o Projeto

Este projeto tem como objetivo acompanhar de forma interativa a Demonstração do Resultado do Exercício (DRE), fornecendo uma visão consolidada e detalhada sobre:

- Receita Bruta e Receita Líquida

- Custos e Despesas Operacionais

- Margem de Contribuição e Resultado Operacional

- Impostos sobre o Lucro e Resultado Líquido

- Evolução mês a mês do desempenho financeiro

O dashboard foi desenvolvido para apoiar gestores e analistas financeiros na tomada de decisão baseada em dados e permitir um acompanhamento transparente e estruturado da saúde financeira da empresa.

## 🖼️ Visualizações do Dashboard

### Resumo DRE

![Resumo](/reports/exports/images/slide1.png)

### Detalhamento DRE - Mês a Mês

![Detalhamento](/reports/exports/images/slide2.png)

## 🌐 Dashboard Online

[![Acessar Dashboard Power BI](https://img.shields.io/badge/🔗%20Acessar%20Dashboard%20Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://app.powerbi.com/view?r=eyJrIjoiYzA1NDBhN2UtZGRmMy00OWM3LTg0NGMtZTY1ZjhjN2M4YWMyIiwidCI6IjdlYmVmODBjLTEwMjctNDEyOS1iNDg0LWNjZjJiZDNmZDU4ZiJ9&pageName=ReportSection)
*Clique no botão acima para acessar o dashboard interativo online*

## 💡 Insights e Benefícios

- Identificação rápida de pontos críticos de custos e despesas

- Monitoramento da margem de contribuição e lucratividade

- Análise comparativa da evolução mês a mês

- Suporte a decisões estratégicas como redução de custos, precificação e alocação de recursos

- Transparência para investidores, gestores e stakeholders

## 📁 Estrutura do Projeto

```text
📁 acompanhamento_financeiro_dre_2_powerbi/
├── 📁 data/                              
│   └── raw/                                              # Dados brutos 
│      ├── db_categorias.xlsx                                                             
│      └── db_lancamentos.xlsx                            
│ 
├── 📁 reports/                                           # Relatórios e análises
│   ├── powerbi/                                         
│   │   └── link_acompanhamento_financeiro_dre_v1.txt         
│   └── exports/                                           # Arquivos exportados
│       └── images/
│           ├── slide1.png                                 # Capturas de Tela
│           └── slide2.png                      
│
└── 📄 README.md                                           # Documentação do projeto
```

## 🛠️ Tecnologias Utilizadas

- **Excel**: Fonte de dados estruturada (bd_estoque.xlsx)
- **Power Query**: ETL (Extract, Transform, Load) e transformação de dados
- **Power BI Desktop**: Desenvolvimento do dashboard e modelagem de dados
- **DAX (Data Analysis Expressions)**: Criação de medidas calculadas e KPIs
- **Power BI Service**: Publicação e compartilhamento online do dashboard
