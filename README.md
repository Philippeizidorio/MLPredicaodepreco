# Prevendo Preços De Apartamentos Com Machine Learning 🏙️
![Alt ou título da imagem](https://github.com/Philippeizidorio/MLPredicaodepreco/assets/145637595/46c32dee-10f5-43ad-b6e4-598495f87fba)

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
Após ter importado a base, realizamos certos tratamentos, trabalhamos no entendimento dos dados e identificação de tendências, a fim de realizarmos uma análise exploratória desses dados usando bibliotecas como **Pandas** e **Plotly**.

### ◾Dicionário Dos Dados:

`Avg_Area_Income`: Média da área construída. 

`Avg_Area_House_Age`: Média de idade do imóvel. 

`Avg_Area_Number_of_Rooms`: Média da quantidade de salas.

`Avg_Area_Number_of_Bedrooms`: Média da quantidade de quartos.

`Area_Population`: População do local.

`Price`: Preço do imóvel. **Variável target*

### ◾Correlação entre as variáveis com 'Price'(Pairplot):

<p align="center">
  <img src="https://github.com/Philippeizidorio/MLPredicaodepreco/assets/145637595/3c22fdb9-3d25-4c24-9358-6df2a9ca73e9" alt="Média de renda por canal de venda">
</p>

<p align="center">
   As colunas possuem uma maior correlação com 'Price' são as de número 1,2,3 e 5.
</p>

### ◾Correlação entre as variáveis com 'Price'(Heatmap):

<p align="center">
  <img src="https://github.com/Philippeizidorio/MLPredicaodepreco/assets/145637595/ea4c0322-83b3-442f-bbda-9d10d2a9a5e9" alt="Média de renda por canal de venda">
</p>

### ◾Treinando e Testando o modelo de ML:
Nessa etapa final, separamos as variáveis ___'x'___ e ___'y'___, definimos as bases ___train___ e ___test___. Por fim, importamos a Regressão Linear do Sklearn para treinar os dados, predizer e tirarmos o R² Score.
<p align="center">
  <img src="https://github.com/Philippeizidorio/MLPredicaodepreco/assets/145637595/79d2d6fb-94fe-4842-a048-79542bbb924c" alt="Média de renda por canal de venda">
</p>

<p align="center">
 Obtivemos um R²_Score de 91%(Alta linearidade)
</p>
