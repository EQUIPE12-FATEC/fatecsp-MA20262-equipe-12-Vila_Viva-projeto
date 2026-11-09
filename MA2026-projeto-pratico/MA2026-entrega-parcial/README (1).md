# 📗 01 — Excel \| Tratamento Manual

## 📌 Objetivo

Este diretório reúne as **planilhas de origem e tratamento manual** utilizadas no projeto Vila Viva. Aqui são aplicadas fórmulas, verificações e procedimentos de auditoria que servem de referência para as etapas posteriores.

## 📁 Arquivos de trabalho

| Planilha | Dados e tratamento |
| :---- | :---- |
| `Vila_Viva_COVID19-1.xlsx` | Casos, óbitos, incidência, mortalidade, letalidade e checagens. |
| `Vila_Viva_Dengue-1.xlsx` | Notificações, casos confirmados, proporções e incidência. |
| `Vila_Viva_Pneumonia-1.xlsx` | Estrutura de internações, população, taxas e conferências. |

Cada arquivo possui quatro abas principais:

- **Bruto:** registros recebidos e campos originais.  
- **Tratado:** resultados organizados e calculados com fórmulas.  
- **Cadastros:** referências de códigos e nomes dos municípios.  
- **Auditoria:** ocorrências, validações e pendências identificadas.

## 🧮 Tratamentos realizados

São utilizadas operações de soma e contagem, cálculos de taxas por 100 mil habitantes, buscas em cadastros, limpeza e padronização de textos e verificações de consistência. A identificação dos registros considera município e ano.

## 🔗 Relação com as outras etapas

Os resultados da aba **Tratado** são usados como referência para verificar se a automação com Power Query reproduz as regras de cálculo do Excel.

## ⚠️ Atenção

Os arquivos contêm **dados brutos e dados tratados**, não apenas dados brutos. Há pendências registradas para COVID-19 e ausência de valores necessários para certos indicadores de pneumonia na versão de origem. Consulte o relatório `Documentacao_01_Manual.pdf` antes de interpretar resultados.