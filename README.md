# PriceWise AI
![TS.webp](attachment:TS.webp)

# 1. BUSINESS UNDERSTANDING

## 1.1 Business Problem

The main objective of this project is to develop accurate time series models that can forecast economic indicators and commodity prices. Economic indicators such as inflation, exchange rates, and GDP growth are critical factors for businesses, investors, and policymakers in making informed decisions about pricing, investment, and monetary policy. Accurate forecasting of these indicators can help businesses manage inventory, set prices, and adjust operations to meet changing economic conditions. Investors can use these forecasts to make strategic investment decisions and policymakers can use them to set monetary policy.

The project focuses on providing value to businesses, investors, and policymakers who require accurate and timely economic forecasts. The real-world problem that this project aims to solve is the challenge of accurately forecasting economic indicators and commodity prices. The stakeholders who could benefit from this project include businesses, investors, and policymakers who need to make informed decisions based on economic data.

The project aims to develop accurate and reliable model for predicting commodity prices and inflation trends, identify investment opportunities based on trends in commodity prices and inflation rates, and provide recommendations on how to capitalize on these opportunities. By doing so, this project can help businesses manage costs associated with fluctuations in commodity prices and inflation rates, as well as identify opportunities to reduce these costs

## 1.2 Objectives

### 1.2.1 Main Objective
The main objective of this project is to develop accurate time series models that can forecast economic indicators such as inflation rates and exchange rates and commodity prices

### 1.2.2 Specific Objectives
1. Explore and clean time series data on economic indicators and commodity prices to identify patterns, trends, and seasonality.
2. Conduct market analysis to identify trends and patterns in commodity prices and inflation rates, and provide investment recommendations to capitalize on the identified opportunities.
3. Develop and test time series models, evaluate their performance using statistical metrics, and use the best-performing models to forecast economic indicators and commodity prices for the next 12 months.
4. Develop a web-based application that provides traders and investors with reliable real-time commodity price predictions and continuously update the model for ongoing accuracy.

## 1.3 Success Metric
Model Accuracy: The accuracy of the developed time series models will be measured by the Root Mean Squared Error (RMSE) and the project will be considered success if the time series model has a Root Mean Squared Error for each of the commodities is utmost 5% when making predictions.

# 2. DATA UNDERSTANDING 
## Data Sources:

The data for Inflation Rates.csv, Annual GDP.csv, and Exchange Rates.csv are obtained from the Central Bank of Kenya (CBK)  [here](https://www.centralbank.go.ke/inflation-rates/) website. CBK is the central monetary authority of Kenya responsible for formulating and implementing monetary policy in the country. The data for commodity prices.xlsx is obtained from the Food Security Portal [here](https://fews.net/kenya-monthly-fews-net-staple-food-price-data-0) which is maintained by the International Food Policy Research Institute.

### Properties of the Data:

Inflation Rates.csv contains the monthly inflation rates from January 2000 to December 2022. The data is presented as percentages, and the inflation rates are calculated as year-on-year changes in the Consumer Price Index (CPI) for the Kenyan economy. The dataset contains 276 observations.

Annual GDP.csv contains the annual GDP of Kenya in current prices (Kenyan Shillings) from 1960 to 2021. The GDP is calculated as the value of goods and services produced within the country's borders, and it is presented in nominal terms. The dataset contains 62 observations.

Exchange Rates.csv contains the daily exchange rates of major currencies (USD, GBP, EUR, and JPY) against the Kenyan Shilling from January 2000 to December 2022. The exchange rates are presented as the number of units of foreign currency that can be exchanged for one Kenyan Shilling. The dataset contains 6,346 observations.

Commodity prices.xlsx contains monthly prices of selected food commodities (maize, beans, rice, and wheat) in Kenya from January 2005 to December 2022. The data is presented in Kenyan Shillings per kilogram, and the dataset contains 216 observations for each commodity.

### Suitability of the Data:

The data from CBK and the Food Security Portal is highly relevant to the Kenyan economy and is suitable for the project. Inflation Rates.csv provides insight into the inflation trends in Kenya, which is essential for forecasting commodity prices. Annual GDP.csv helps in understanding the overall performance of the Kenyan economy, and Exchange Rates.csv is crucial in forecasting the future prices of commodities denominated in foreign currencies. Commodity prices.xlsx is essential for understanding the trends and patterns of food commodity prices in Kenya, which is essential for predicting food security.

### Data Limitations:

The data from CBK and the Food Security Portal is comprehensive, but there are some limitations. Inflation Rates.csv only covers the period from January 2000 to December 2022, which may not capture long-term trends in inflation. Annual GDP.csv only presents the GDP in nominal terms, which does not account for changes in the prices of goods and services over time. Exchange Rates.csv only covers a limited number of major currencies, which may not reflect the exchange rates of other currencies that may affect commodity prices. Commodity prices.xlsx only covers a limited number of food commodities, which may not reflect the prices of other essential commodities affecting food security in Kenya.
## Data Preparation

## EDA 

## Modelling

## Deployment
