# ⚙️ 02 — Power Query \| Automação e Processamento

## 📌 Objetivo

Este diretório concentra a etapa de **automação do processamento de dados** do Vila Viva. O Power Query reproduz regras do tratamento manual por meio de consultas na linguagem **M**, permitindo atualizar os resultados quando os arquivos de origem são alterados de maneira compatível.

## 📁 Arquivo principal

`Vila_Viva_02_PowerQuery.xlsx`

O arquivo contém consultas para **COVID-19**, **Dengue** e **Pneumonia**, parâmetros de caminho para as fontes e abas de apoio denominadas `Instruções`, `Mapeamento` e `Validação`.

## 🔄 Como funciona

1. **Conexão:** leitura das três planilhas de origem por parâmetros.  
2. **Preparação:** promoção de cabeçalhos, definição de tipos e filtragem de chaves ausentes.  
3. **Integração:** correspondência com cadastros e campos de referência por município e ano.  
4. **Transformação:** aplicação de cálculos, taxas e checagens específicos para cada doença.  
5. **Carga:** disponibilização dos resultados em tabelas separadas no Excel.  
6. **Validação:** comparação das saídas automatizadas com os resultados do tratamento manual.

## 📊 Resultados documentados

As três consultas produziram **2.580 linhas cada**, totalizando 7.740 registros. A comparação documentada com os valores salvos nas abas `Tratado` não identificou diferenças nas colunas verificadas, sob os critérios de comparação adotados.

## ▶️ Atualização

Abra o arquivo no Excel, confira os parâmetros `pArquivoCOVID19`, `pArquivoDengue` e `pArquivoPneumonia`, mantenha as fontes disponíveis e execute **Dados → Atualizar Tudo**. Depois, confira a aba `Validação` e as saídas das três doenças.

## ⚠️ Limitações

A automação não valida por si só a procedência epidemiológica das fontes. O tratamento de duplicatas, a reconciliação de rejeitados e a transformação de séries mensais ainda apresentam itens parciais ou pendentes na documentação.

📖 Detalhes: `Documentacao_02_Power_Query.pdf`, em `04-documentacao`.