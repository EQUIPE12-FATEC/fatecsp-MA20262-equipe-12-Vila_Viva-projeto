# 📦 Vila Viva \| Entrega Parcial

Esta pasta reúne os materiais da **entrega parcial do projeto Vila Viva**, organizados conforme a evolução do tratamento e da análise de dados epidemiológicos de COVID-19, dengue e pneumonia.

## 🗂️ Estrutura dos diretórios

| Diretório | Conteúdo | Objetivo |
| :---- | :---- | :---- |
| [`01-excel`](./01-excel/) | Planilhas originais e fórmulas manuais | Preparar, conferir e auditar os dados de origem. |
| [`02-powerquery`](./02-powerquery/) | Consultas e resultados automatizados | Executar transformações reproduzíveis e validar resultados. |
| [`03-powerpivot`](./03-powerpivot/) | Arquivo de análises e visões | Explorar indicadores e comparações territoriais. |
| [`04-documentacao`](./04-documentacao/) | Relatórios técnicos em PDF | Explicar métodos, regras, testes e limitações. |

## 🔁 Fluxo do projeto

```
Bases de origem (COVID-19, Dengue, Pneumonia)
                 ↓
       01 · Excel manual
                 ↓
      02 · Power Query
                 ↓
     03 · Análises / Power Pivot
                 ↓
    04 · Documentação e evidências
```

A documentação acompanha todas as etapas, não apenas o resultado final.

## 📊 Recorte dos dados

As bases de origem abrangem **645 municípios**, com registros anuais de **2022 a 2025** (2.580 linhas por base). A chave de referência é composta por `Ano` e `Codigo_Municipio_CVE`.

## 🔍 Como avaliar a entrega

1. Consulte os arquivos e fórmulas de `01-excel`.  
2. Compare as regras manuais com as consultas de `02-powerquery`.  
3. Examine as quatro visões analíticas em `03-powerpivot`.  
4. Leia os relatórios de `04-documentacao` para entender as verificações e pendências.

> **Nota de qualidade:** resultados técnicos e indicadores epidemiológicos exigem validação de suas fontes. A presença de gráficos não comprova, isoladamente, relacionamentos ou medidas DAX implementados.