Previsão de Vendas com Séries Temporais.

Análise de dados e previsão de vendas para uma loja global usando séries temporais e o modelo ARIMA.


📋 Sobre o Projeto

O objetivo deste projeto é realizar uma análise de dados exploratória e a previsão das vendas dos próximos 7 dias com base em dados históricos, utilizando técnicas de análise exploratória e modelagem preditiva.


🚀 Tecnologias Utilizadas

Python

Pandas

Matplotlib

Seaborn

Statsmodels (para o modelo ARIMA)

Sklearn



🔍 Etapas do Projeto

1 - Preparação dos Dados:

1.1 - Conversão de datas para índices.
      
2 - Tratamento de valores nulos e organização dos dados.

3 - Identificação de padrões e tendências nas vendas.

4 - Agregação dos dados em séries temporais diárias.

5 - Modelagem Preditiva com ARIMA:

6 - Treinamento do modelo com dados históricos.

7 - Previsão de vendas para os próximos 7 dias.



💻 Como Rodar o Projeto

Clone este repositório:

bash

Copiar código

git clone https://github.com/seuusuario/nomedoprojeto.git


Instale as dependências:

bash

Copiar código

pip install -r requirements.txt


Execute o notebook Jupyter:

bash

Copiar código

jupyter notebook



📈 Resultados

Previsão para os Próximos 7 Dias:


  index	      predicted_mean
  
0	2018-12-30	1806.327261

1	2018-12-31	1263.473265

2	2019-01-01	1533.008720

3	2019-01-02	1399.180173

4	2019-01-03	1465.628129

5	2019-01-04	1432.635685

6	2019-01-05	1449.016946




🛠️ Próximos Passos

Implementar métricas de avaliação como RMSE e MAE.

Testar outros modelos, como Prophet ou LSTM, para comparar os resultados.

