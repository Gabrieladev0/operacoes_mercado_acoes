# 📈 Operações no Mercado de Ações

Dataset e análise de operações de compra e venda de ações na B3, cobrindo o ano de 2023 com registros de 100 clientes e 20 ativos diferentes.

---

## 📋 Sobre o Projeto

Este projeto contém um conjunto de dados com **2.000 operações** de mercado de capitais simuladas, ideal para prática de análise de dados, construção de dashboards financeiros e estudos de comportamento de investidores.

---

## 🗂️ Estrutura dos Dados

O arquivo `operacoes_mercado_acoes.xlsx` contém uma planilha (`mercado_acoes`) com as seguintes colunas:

| Coluna           | Tipo     | Descrição                                      |
|------------------|----------|------------------------------------------------|
| `Código Cliente` | Numérico | Identificador único do cliente (1–100)         |
| `Nome Cliente`   | Texto    | Nome completo do cliente                       |
| `Email Cliente`  | Texto    | E-mail do cliente                              |
| `Operação`       | Texto    | Tipo de operação: `Compra` ou `Venda`          |
| `Stiker`         | Texto    | Ticker do ativo negociado (ex: PETR4, VALE3)   |
| `Preco`          | Decimal  | Preço unitário do ativo na data da operação    |
| `Data`           | Data     | Data da operação (formato YYYY-MM-DD)          |

---

## 📊 Visão Geral do Dataset

- **Total de registros:** 2.000 operações
- **Período:** 01/01/2023 a 28/12/2023
- **Clientes únicos:** 100
- **Ativos negociados:** 20 tickers da B3

### Ativos disponíveis

```
ABEV3  · B3SA3  · BBAS3  · BBDC4  · BHIA3
CPFE3  · CSAN3  · HAPV3  · IGTA3  · ITUB4
JBSS3  · LREN3  · MGLU3  · PETR4  · RENT3
SANB11 · TAEE4  · VALE3  · VIVT3  · WEGE3
```

---

## 💡 Possíveis Análises

- Volume de operações por ativo e por período
- Comparação entre operações de compra e venda
- Perfil de comportamento dos clientes (frequência, ativos preferidos)
- Variação de preços dos ativos ao longo do ano
- Construção de dashboards financeiros com Power BI, Tableau ou Python

---

## 📁 Arquivos

```
📦 operacoes-mercado-acoes/
 ┣ 📊 operacoes_mercado_acoes.xlsx   # Dataset principal
 ┗ 📄 README.md                      # Este arquivo
```

## 📝 Licença

Projeto desenvolvido para fins de estudo e prática em análise de dados.
