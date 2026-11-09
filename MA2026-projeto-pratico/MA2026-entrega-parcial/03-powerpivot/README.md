# 📊 03 — Power Pivot | Análises e Refinamento

## 📌 Objetivo

Este diretório reúne a **etapa analítica** do Vila Viva, que utiliza dados preparados para apresentar indicadores epidemiológicos de forma organizada, permitindo observar padrões anuais e diferenças entre municípios.

## 📁 Arquivo principal

`VilaViva_03_PowerPivot.xlsx`

O arquivo disponibilizado contém quatro abas de análise:

| Aba | Conteúdo |
|---|---|
| `01_Executivo` | Visão geral das bases, período e indicadores comparativos. |
| `02_COVID19` | Registros de casos, óbitos e análises anuais. |
| `03_Dengue` | Casos, notificações, incidência e análises territoriais. |
| `04_Pneumonia` | Internações, taxas e comparações municipais. |

## 🔎 Refinamento e interpretação

A análise trabalha com **totais anuais**, **taxas por 100 mil habitantes** e **rankings municipais**, sempre respeitando o significado de cada indicador. Casos de dengue, registros de COVID-19 e internações por pneumonia não devem ser somados como se representassem a mesma medida.

## 🔗 Relação com o Power Query

A etapa sucede o processamento do Power Query no fluxo do projeto. Os dados tratados fornecem a base para as análises e visualizações.

## ⚠️ Situação técnica

O arquivo examinado apresenta **relatórios e gráficos em Excel**. A documentação não comprova que todas as consultas, tabelas do Modelo de Dados, relações e medidas DAX estejam efetivamente configuradas e testadas como um modelo Power Pivot completo. Esses elementos devem ser verificados antes de declarar a implementação concluída.

📖 Detalhes: `Documentacao_03_PowerPivot.pdf`, em `04-documentacao`.
