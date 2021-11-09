# COS80023-Big-Data-Nikta-102870603-
This is the repository of Stock Market analysis and forecasting stock price

# Stock Market Analysis and Prediction

The goal is to predict the closing stock price of Apple, Google, and IBM after 5 days into the future from the historical data. Also, analyse and visualise the stock price variables for these companies.

This project analyses the stock market data of the technology companies individually and finds the correlation between stock price data of different technology companies. Also, the objective of this project is to develop and evaluate models LSTM, GRU, CNN and MLP that can effectively be used for stock price forecasting of the companies Apple, Google, and IBM

## Dataset
The dataset consists of the stock market data for 3 technology companies i.e., Apple, Google, and IBM from 5th Oct 2016 to 4th October 2021. It has been acquired from the link: https://finance.yahoo.com/lookup
The dataset consists of below variables:
* Date: The date for which stock price is recorded
* Open: The opening stock price of the company on a particular date
* High: The highest stock price of the company on a particular date
* Low: The lowest stock price of the company on a particular date
* Close: The closing stock price of the company on a particular date
* Adj Close: Adjusted close is the closing price after adjustments for all applicable splits and dividend distributions on a particular date. 
* Volume: It is the number of stock’s share that are traded on a particular day

## Data and Code files 

* There are 3 data files for stock market data of tech companies
  - Apple - AAPL.csv
  - Google - GOOG.csv
  - IBM - IBM.csv
* There is one code file Stock Price Forecasting.ipynb that contains the analysis and stock price prediction implementation of the 3 tech companies

## Softwares required
1) Anaconda3
2) Jupyter Notebook

## Cloning the repository and launching Jupyter notebook
1)	Copy the URL under the Code option from github repository
2)	Install Git in the local system
3)	Create a folder in the local system where all the github repository files would be downloaded
4)	Using cd command on the terminal navigate to the path of the folder created above
5)	Initialize the folder as git with the command: git init
6)	Clone the repository by using command: git clone URL of the repository
7)	Open Anaconda Navigator
8)	Select the option launch the Jupyter Notebook
9)	Once Jupyter notebook is opened, locations of different folders on local system can be displayed
10)	You can open the file from the folder where repository has been cloned, make sure the data files should be in the working directory
11)	Once the file is opened, under Kernel you can select Restart and Run all option to execute the file


