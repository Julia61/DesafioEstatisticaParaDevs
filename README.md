# 📊 Desafio: Análise de Faturamento com Pandas e Gráficos

Este repositório contém a resolução de um **exercício prático do módulo de Estatística**, proposto durante o curso. O desafio tem como objetivo aplicar na prática os conhecimentos adquiridos sobre análise de dados utilizando a biblioteca **Pandas**, além de explorar a visualização de dados com **Matplotlib**.

---

## 🧠 Objetivo do Desafio

A partir de um dicionário com dados de faturamento mensal, o desafio propõe:

1. **Calcular a média dos valores de vendas** contidos no dicionário.
2. **Criar um gráfico de barras vertical**, relacionando a data de referência (mês/ano) com o valor de faturamento.
3. **Criar um gráfico de linhas** com os mesmos dados, permitindo visualizar a variação ao longo do tempo.

---

## 🧾 Dados fornecidos

O dicionário fornecido no exercício tem duas colunas:

- `data_ref`: Datas de referência mensais.
- `valor`: Valor de faturamento correspondente àquela data.

Exemplo:

```python
dict_faturamento = {
    'data_ref': ['2023-01-01', '2020-02-01', ..., '2023-12-01'],
    'valor': [400000, 890000, ..., 995000]
}
