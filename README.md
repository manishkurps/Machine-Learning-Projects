# Machine-Learning-Projects

In this project, Support Vector Machines (SVM) with a Radial Basis Function (RBF) kernel were used to predict stock prices for three different banks — **SBI, ICICI, and HDFC**, each analyzed in a separate Jupyter notebook. Historical stock price data from the NSE, covering the period from 14th May 2020 to 14th May 2024, were collected, preprocessed, and used to train the SVM models. The RBF kernel was chosen for its ability to handle non-linear relationships. The models' performance was evaluated using metrics such as Root Mean Squared Error (RMSE) and R-squared. Results showed varying levels of prediction accuracy across the three banks, highlighting the need for tailored approaches and potential further improvements in feature selection and model tuning.

## Datasets Description

## **Context** : 
The data is the price history and trading volumes of all three banks datsets from NSE (National Stock Exchange) India. The data in the dataset spans from **14th May, 2020** to **14th May, 2024**.

Dataset link : [SBI](https://finance.yahoo.com/quote/SBIN.NS/history/?period1=1652486400&period2=1715707972), [HDFC](https://finance.yahoo.com/quote/HDFCBANK.NS/history?period1=1589587200&period2=1715849843), [ICICI](https://finance.yahoo.com/quote/ICICIBANK.NS/history?period1=1589587200&period2=1715850148)

## **Columns Description :**

**Date -** Trade Data: Represents the date of the trading data, indicating when the stock market activity occurred.

**Open -** Opening Price for the Day: Represents the initial price at which a stock is traded on a given day.

**High -** Highest Price for the Day: Denotes the highest trading price reached by the stock during the trading day.

**Low -** Lowest Price for the Day: Represents the lowest trading price reached by the stock during the trading day.

**Close -** Closing Price: Indicates the final trading price of the stock at the end of the trading day.

**Adj Close -** The adjusted closing price takes dividends, stock splits, and new stock offerings into account. The adjusted closing price is a more accurate indicator of stock value since it starts where the closing price finishes.

**Volume -** Volume Traded for the Day: Represents the total number of shares or contracts traded during a specific time period, typically a trading day.

# SVM for predicting Closing Price for Three different Bank stock datasets
Comparing  SVR model with Kernel = Radial Basis Function Kernel, in their effectiveness when applied to predict Closing price of SBI, HDFC and ICICI Stock. A much detailed approach can be found on the accompanying [Medium article](https://medium.com/@rupesh1684/stock-market-prediction-using-machine-learning-model-svm-e4aaca529886), [Geeks For Geeks](https://www.geeksforgeeks.org/stock-price-prediction-using-machine-learning-in-python/)

## Results (Accuracy)
- SBI score : 97.28%
- HDFC score : 88.58%
- ICICi score : 97.33%

## RMSE and R-square
- SBI :
   - RMSE:6.22
   - R-square score:0.56
- HDFC :
   - RMSE:15.53
   - R-square score:0.60
- ICICI :
   - RMSE:7.04
   - R-square score:0.48

 **Best Configuration = Lower RMSE and higher R-square score**

## Interpretation

**With the above RMSE and an R² score using SVR with the RBF kernel, the model's predictive accuracy is relatively moderate.**

## Actual and Predicted Prices for all three banks

![Screenshot 2024-05-25 115638](https://github.com/manishkurps/Machine-Learning-Projects/assets/142977823/f4ec1927-010e-4e37-b20c-e6e3e86f7f08)

![Screenshot 2024-05-25 115712](https://github.com/manishkurps/Machine-Learning-Projects/assets/142977823/be3761a0-5083-432f-8818-b9b3428c3285)

![Screenshot 2024-05-25 115800](https://github.com/manishkurps/Machine-Learning-Projects/assets/142977823/288cc47d-4045-4cac-82d1-77b774dc1544)



Reference : [Medium article](https://medium.com/@rupesh1684/stock-market-prediction-using-machine-learning-model-svm-e4aaca529886)



