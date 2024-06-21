# Development project
This is a final year development project that aims to solve stock prediction problem using artificial neural network especially long-short Term memory (LSTM) which is a type of RNN.
Blue Sticker

## --Overview-- 

This is a Django web application project used for stock market predictions and analysis using
Long-Short-Term Memory(LSTM) neural network. It collects historical stock data from yahoo finance 
and provides visualisation of the stock prices and volume using ApexCharts and Plotly. 

## --Features-- 

Step 1: Download historical data
Step 2: Preprocess and normalise the data 
Step 3: Split the data into training and testing
Step 4: Prepare stacked LSTM model to predict the data
Step 5: Visualise the stock data into candlestick charts and volume data
Step 6: Use Plotly tool to compare actual data to predicted data


## --Prerequisites--

. Python 
. Django  
. HTML
. CSS 
. Tensorflow 2.16.1
. Scikit-learn 1.1.50
. Keras 
. Datetime 
. Pandas
. yfinance 
. numpy 

use requirements.txt to download all the tools used 

## --Installation--

## --Clone-- 
git clone https://github.com/your-username/stockExchange.git
cd stockExchange

## --Install virtual environments--
python -m venv venv

Virtual environment may look slightly different on mac
activate script:
You can use either
.\activate.bat
activate.bat

## --Apply Migrations--
python manage.py migrate

## --Run development server--
python manage.py runserver 
This can be done at localhost 7000 or 8000
It should navigate to  http://127.0.0.1:8000/
Then type  http://127.0.0.1:8000/stockAI/ 
This will direct you to the webpage 


# Django documentation
Django documentation provides guidence to use django.
https://docs.djangoproject.com/en/5.0/
