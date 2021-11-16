# Regularization-Ridge-LASSO
## Orange Juice Sales

We will analyse the weekly sales data of refrigerated 64-ounce orange juice
containers from 83 stores in the Chicago area. There are many stores throughout
the city, many time periods, and three brands (Dominicks, MinuteMaid, and Tropicana).
The data are arranged in rows with each row giving the recorded sales (in
logarithms; `logmove`), as well as brand, price, presence/absence of feature advertisement,
and the demographic characteristics of the stores. In total, there are 28,947
rows in this data set. The data is taken from P. Rossi’s bayesm package for R, and it has been used earlier in Montgomery (1987).

### Data

---
STORE \  \ store number

BRAND \  \ brand indicator

WEEK \  \ week number

LOGMOVE \  \ log of the number of 64oz units sold

PRICE \  \ price of 64oz unit

FEATURE \  \ feature advertisement

AGE60 \ \  proportion of the population that is aged 60 or older

EDUC \  \ proportion of the population that has a college degree

ETHNIC \  \ proportion of the population that is black or Hispanic

INCOME \  \  log median income

HHLARGE \  \ proportion of households with 5 or more persons

WORKWOM \  \  proportion of women with full-time jobs

HVAL150 \  \ proportion of households worth more than $150,000

SSTRDIST \  \ distance to the nearest warehouse store

SSTRVOL \  \ ratio of sales of this store to the nearest warehouse store

CPDIST5 \  \ average distance in miles to the nearest 5 supermarkets

CPWVOL5 \  \ ratio of sales of this store to the average of the nearest
five stores

### Task

Build a model that predicts the sales (log of the number of units sold) using ridge and lasso regression models. Select the best one, i.e. the one with the lowest testing MSE.
