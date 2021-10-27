# Cryptocurrencies
# About
## Purpose
The purpose of the study is to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a 
classification system for the new investment. To make the report I used unsupervised machine learning module because there is no known output.
I used four technical analysis to complete the project:
- Preprocessed the Data for PCA
- Reduced the Data Dimensions Using PCA
- Clustered Cryptocurrencies Using K-means
- Visualized Cryptocurrencies Results

## Results:
After creating a new data frame from preprocessed dataframe, reducing data dimensions using PCA, and Clustered Cryptocurrencies Using K-means, I ploted the hvplot scatter plot with x="TotalCoinsMined", y="TotalCoinSupply", and by="Class" and CoinName as the hover datapoint as shown in figure below.

<img width="918" alt="Screen Shot 2021-10-27 at 3 19 25 PM" src="https://user-images.githubusercontent.com/85364095/139155538-42b2e6d0-b7b2-4c99-84be-84b26cf763a4.png">

