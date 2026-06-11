# Dashboard de Análise de Veículos Usados

Aplicativo web interativo para exploração visual de dados de anúncios de veículos usados nos Estados Unidos.

## 1. Objetivo do Projeto

Criar uma ferramenta acessível e intuitiva que permita a qualquer usuário — mesmo sem conhecimento técnico — explorar visualmente um conjunto de dados de anúncios de venda de carros usados. O projeto resolve o problema de como transformar dados brutos (CSV com milhares de anúncios) em visualizações interativas que revelam distribuições e correlações entre variáveis como quilometragem e preço.

## 2. Resultado Obtido

Um dashboard web funcional desenvolvido com Streamlit e implantado na nuvem (Render), contendo:
- **Histograma interativo** da coluna de quilometragem (`odometer`) para análise de distribuição
- **Gráfico de dispersão** relacionando quilometragem e preço (`odometer` vs `price`)
- Botões para acionar cada visualização sob demanda
- Notebook complementar de análise exploratória de dados (EDA) com as mesmas visualizações

**Acesse o dashboard online:** [https://projetosprint5-z2zj.onrender.com/](https://projetosprint5-z2zj.onrender.com/)

## 3. Ferramentas Utilizadas

- **Python** — linguagem principal
- **Streamlit** — framework para construção do dashboard web
- **Pandas** — leitura e manipulação dos dados
- **Plotly Express** — visualizações interativas (histograma e gráfico de dispersão)
- **Jupyter Notebook** — análise exploratória complementar
- **Render** — plataforma de deploy e hospedagem

## 4. O que Aprendi

- Construir aplicações web interativas com Streamlit a partir de um script Python
- Integrar gráficos Plotly dinâmicos em uma interface com controles (botões)
- Realizar deploy de aplicações Streamlit na nuvem utilizando Render
- Estruturar um projeto de análise de dados com separação entre notebook exploratório e aplicação final
- Praticar a lógica de leitura de datasets reais (CSV com ~50 mil registros) e criação de visualizações para comunicação de insights

## 5. Melhorias Futuras

- Adicionar filtros interativos (por marca, modelo, ano, condição do veículo)
- Incluir novas visualizações: boxplots por condição do veículo, gráficos de barras por fabricante, mapa de calor de correlações
- Implementar uma calculadora de preço estimado com base em quilometragem e ano (regressão simples)
- Melhorar o layout com colunas, abas e sidebar para organizar os controles
- Adicionar indicadores (cards) com estatísticas descritivas do dataset (média de preço, total de anúncios, etc.)
