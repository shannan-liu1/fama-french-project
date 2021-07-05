# fama-french-project
Application of the Fama-French 3-factor model to analyse the daily returns of 4 technology companies--Apple, Microsoft, Intel, and IBM--over 35 years. 

The historical prices of the stocks were collected from Yahoo Finance and the data on the three Fama-French factors (colloquially known as Size Premium, Value Premium, and Market Risk Premium) were collected from Kenneth French's personal website. After converting historical prices to historical returns, a panel data frame was constructed, and the daily returns were regressed on the Fama-French factors. 

Three types of models were applied to the data: a pooled model, a fixed-effects model, and a random effects model. The model was then trained and tested using k-fold cross validation and finally used to forecast the stocks' prices.
