# Prevendo Preços De Apartamentos Com Machine Learning 🏙️💲
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
Após ter importado a base, realizamos certos tratamentos, trabalhamos no entendimento dos dados, identificação de tendências usando técnicas estatísticas e bibliotecas como **Pandas** e **Plotly**.

### ◾Dicionário Dos Dados:

`Avg_Area_Income`: Média da área construída. 

`Avg_Area_House_Age`: Média de idade do imóvel. 

`Avg_Area_Number_of_Rooms`: Média da quantidade de salas.

`Avg_Area_Number_of_Bedrooms`: Média da quantidade de quartos.

`Area_Population`: População do local.

`Price`: Preço do imóvel. **Variável target*

### ◾Correlação das variáveis com 'Price'(Pairplot):


<p align="center">
  <img src="https://github.com/Philippeizidorio/MLPredicaodepreco/assets/145637595/3c22fdb9-3d25-4c24-9358-6df2a9ca73e9" alt="Média de renda por canal de venda">
</p>

<p align="center">
   As colunas possuem uma maior correlação com 'Price' são as de número 1,2,3 e 5.
</p>


### ◾Correlação das variáveis com 'Price'(Heatmap):


<p align="center">
  <img src="https://github.com/Philippeizidorio/MLPredicaodepreco/assets/145637595/ea4c0322-83b3-442f-bbda-9d10d2a9a5e9" alt="Média de renda por canal de venda">
</p>


### ◾Treinando e Testando o modelo de ML:
Nessa etapa final, separamos as variáveis ___'x'___ e ___'y'___, definimos as bases ___train___ e ___test___. Por fim, importamos a Regressão Linear do Sklearn para treinamento dos dados, predição e mensuração do R² Score.
<p align="center">
  <img src="https://github.com/Philippeizidorio/MLPredicaodepreco/assets/145637595/79d2d6fb-94fe-4842-a048-79542bbb924c" alt="Média de renda por canal de venda">
</p>

<p align="center">
 Obtivemos um R²_Score de 91%(Alta linearidade)
</p>

### ◾Utilização:
Para usar este código, siga estas etapas:

1. Instale as bibliotecas(dependências) necessárias listadas logo no início;

2. Copie e cole o código em um ambiente Python, como Jupyter Notebook ou um script Python;

3. Execute o código para carregar o conjunto de dados, tratamentos, treinar os modelos e gerar métricas de desempenho e visualizações;

4. Insira os parâmetros desejados para realizar a previsão de preços dos imóveis.

### ◾ Tecnologias Utilizadas: 
<div <br> 
<img src="https://img.shields.io/badge/Python-4695dd?style=for-the-badge&logo=python&logoColor=FFD43B">
<img src="https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white">
<img src="https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white">
<img src="https://img.shields.io/badge/Matplotlib-%232A9D8F.svg?style=for-the-badge&logo=Matplotlib&logoColor=black">
<img src="https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white">
</div> 

## Autor:

<img  src="https://github.com/Philippeizidorio/AnaliseTRIM_AgenciaMKTDIGITAL/assets/145637595/9800ac43-2070-48d4-9002-dbf82f756f2c" width="80" alt="cognitiveclass.ai logo" align="left" /> 

### &nbsp;&nbsp;Philippe Izidório

<p>
&nbsp;&nbsp;Estudante De Ciência De Dados / Business Intelligence / Analista De Dados<br/>
&nbsp;&nbsp;LinkedIn: https://www.linkedin.com/in/philippeizidorio/<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;E-mail: euphilippeizidorio@gmail.com<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Portifólio de projetos em Data Science: https://github.com/Philippeizidorio
</p>

