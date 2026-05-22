# Analise-Exploratoria-e-Visualizacao-de-Dados
Análise exploratória em Python (USD/BRL) demonstrando engenharia de recursos e visualização de dados aplicada a três unidades distintas (Monetária, Frequência e Percentual).
# Análise Exploratória e Visualização de Dados Multi-Unidade: Histórico USD/BRL

Este repositório contém um projeto de análise exploratória de dados desenvolvido em Python (Jupyter Notebook/Google Colab) focado em engenharia de recursos (*feature engineering*) e na construção de visualizações de dados baseadas na natureza e distribuição das variáveis.

O objetivo principal foi transformar um único conjunto de dados reais em três perspectivas analíticas distintas, utilizando **três unidades de medida diferentes** (Monetária, Frequência Absoluta e Percentual).

## 📊 O Dataset
O conjunto de dados utilizado consiste no histórico diário de cotações de venda do Dólar Americano em relação ao Real Brasileiro (**USD/BRL**), cobrindo o horizonte temporal de **2010 a 2019**. 

## 📈 Estrutura das Visualizações

O projeto foi dividido em três abordagens gráficas para respeitar a natureza de cada dado:

1. **Gráfico 1: Evolução Temporal da Cotação**
   * **Tipo:** Gráfico de Linha (*Line Plot*).
   * **Unidade de Medida:** Monetária (Real - R$).
   * **Conceito:** Ideal para séries temporais, demonstrando a tendência estrutural de alta da moeda na década.

2. **Gráfico 2: Distribuição de Frequência e Densidade**
   * **Tipo:** Histograma com curva KDE.
   * **Unidade de Medida:** Frequência Absoluta (Quantidade de Dias).
   * **Conceito:** Estuda a recorrência estatística, mapeando quantos dias o mercado operou em cada faixa de preço.

3. **Gráfico 3: Volatilidade e Rendimento Anual**
   * **Tipo:** Gráfico de Barras (*Bar Plot*).
   * **Unidade de Medida:** Percentual (Variação %).
   * **Conceito:** Compara categorias discretas (anos), mostrando o delta percentual acumulado entre a abertura e o fechamento de cada ano civil.

## 🛠️ Tecnologias Utilizadas
* **Python 3**
* **Pandas:** Manipulação, limpeza e engenharia de atributos dos dados.
* **Matplotlib & Seaborn:** Construção, estilização e renderização dos gráficos.
* **Google Colab:** Ambiente de desenvolvimento integrado.

