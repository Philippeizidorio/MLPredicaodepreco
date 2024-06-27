# Prevendo Preços De Apartamentos Com Machine Learning 🏙️


### ◾Contexto:
O projeto consistiu em tratar uma base de dados de uma imobiliária dos Estados Unidos, construir análises gráficas para entendimento dessa base, desenvolver e avaliar um modelo de regressão linear capaz de prever o preço de imóveis do tipo apartamento.

### ◾Instalação das bibliotecas

Para desenvolvimento do projeto, foram utilizadas bibliotecas como **[pandas](https://pandas.pydata.org/)**, **[matplotlib](https://matplotlib.org/)**, **[scikit-learn](https://scikit-learn.org/)**, **[seaborn](https://seaborn.pydata.org/)** e **[plotly](https://plotly.com/python/)**

Para trazermos algumas bibliotecas necessárias na criação do projeto, foi necessário utilizar o comando **pip install** ou importá-las com o comando **import** em uma célula do Colab.

```
%pip install plotly
%pip install cufflinks
%pip install chart-studio
import pandas as pnd
import seaborn as sns
import numpy as np
import chart_studio.plotly as py
import cufflinks as cf
import plotly.graph_objects as go
import plotly.express as px
```

### ◾Análise Exploratória De Dados(AED):
Após ter importado a base, realizarmos certos tratamentos, trabalharmos no entendimento dos dados, identificação de tendências e extração de insights, a fim de realizamos uma análise exploratória dos dados.
