# Project_4_Financial_Stock

# TEAM
* Abraham Ofolu
* Anderson Safo
* Charlotte Large
* Lionnel Tembu
* Siyuan Liang

# BACKGROUND

In this project, we will be collecting a dataset from the yahoo finance which is a financial stock data, and using a python script which has been initialised, trained and used to evaluate our model. 

Stock market data can be interesting to analyse and as a further incentive, strong predictive models can have a large financial payoff. The amount of financial data on the web is seemingly endless. A large and well-structured dataset on a wide array of companies can be hard to come by.

Our project aims to analyse and make use of historical stock prices, provide an analytical interpretation of the changes and trends, and forecast how those same stock prices will behave in the future.

We will load data using python script and sklearn. We have chosen to use a LSTM model for financial stock data. Our model predictions and overall performance will be printed and saved as a csv file.

# INSTRUCTIONS

This project has been broken down into four parts:

- Part 1: DATA EXTRACTION

We have extracted our Data from yahoo finance and can be accessed through this link - 
https://www.kaggle.com/datasets/jacksoncrow/stock-market-dataset


- Part 2 : INITIALISE, TRAIN AND EVALUATE A MODEL 

Our Data was loaded using a python script and sklearn, we have been able to initialise the dataset using the LSTM model as this was the best choice for a financial stock data. 
<img width="1105" alt="Screenshot 2023-02-22 at 02 04 47" src="https://user-images.githubusercontent.com/111929009/220502263-230c58e0-59d3-422c-8cf4-5df42fbe58fe.png">


- Part 3 : DATA MODEL OPTIMIZATION 

The Model optimisation and evaluation process shows iterative changes on our model selected which has also resulted in changes in performance These changes have been saved in a csv file and can be accessed in the output folder.

- Part 4 : PREDICTIONS AND OVERALL PERFORMANCE 

Model predictions and overall performance has been printed out and displayed at the end of our python script and also saved as a csv file.
<img width="917" alt="Screenshot 2023-02-23 at 10 28 41" src="https://user-images.githubusercontent.com/111929009/220882064-98a1404d-3137-4441-943e-c21f6c4d4bc4.png">



- Part 5 : TABLEAU VISUALIZATION 
We have been able to also create a visualizations of our data, predicted prices and also overall performance of various company stocks selected and here is a link to our tableau visualization.
 
# TECHNOLOGIES USED
- PYTHON
- SKLEARN
- KERAS
- TABLEAU
- GOOGLE COLAB

# LONG SHORT TERM MEMORY
An LSTM was chosen for analyzing stock price data because it excels at modeling sequential data. 

Its unique architecture allows it to store and utilize past information to make accurate predictions, making it well-suited for analyzing stock price patterns, which often exhibit trends and dependencies over time. 

By leveraging the memory cells in the LSTM, we can incorporate information about past stock prices and use this to better predict future trends.


# DATA VISUALISATION
## Closing Price
![image](https://user-images.githubusercontent.com/86980650/221029311-674bc81c-a249-4f67-9dee-48654d56163b.png)

## Volume of Sales 
![image](https://user-images.githubusercontent.com/86980650/221029426-76401860-bc3b-40bc-96e2-9029cea860fb.png)

## Moving Average of Stocks
![image](https://user-images.githubusercontent.com/86980650/221029506-16539670-e1d0-49ff-8c13-4a08b2b4b23b.png)

## Average Stock Returns
![image](https://user-images.githubusercontent.com/86980650/221029592-bd75c241-8d7b-4e18-924b-68760c6e9d0c.png)

## Correlation of Closing Prices Between Differnet Stocks
![image](https://user-images.githubusercontent.com/86980650/221032210-218c3bea-7cf0-4e1d-a8e5-99cb55ae27c7.png)

