<sub>**Datas:** pasta 23/12/2022 · código 18/11/2022 (`lancamentos.xlsx`)</sub>

# Trabalho da matéria da Nancy — moedas e proporções

Experimento de **cara/coroa** com quatro pessoas; teste **Z** para proporção 2/3 vs observado.

## O que o código faz

| Arquivo | Função |
|---------|--------|
| `Trabalho_Nancy.Rmd` | Lê lançamentos da planilha por blocos Excel; contagem caras/coroas; teste de hipótese |
| `moedas.Rmd` | Gera dataset sintético e grava `moedas.csv` |

## Dados

`lancamentos.xlsx` — abas/ranges fixos com resultados de João, Lucas, Ana e Daniel.

`moedas.csv` — saída do segundo Rmd.

## Como rodar

WD na pasta → knit `Trabalho_Nancy.Rmd` (`readxl`).
