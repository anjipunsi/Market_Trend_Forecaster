# stock-price-prediction-system
Introduction
Predicting stock prices is a cumbersome task as it does not follow any specific pattern. Changes in the stock prices are purely based on supply and demand during a period of time. In order to learn the specific characteristics of a stock price, we can use algorithm to identify these patterns through machine learning. One of the most well-known networks for series forecasting is LSTM (long short-term memory) which is a Recurrent Neural Network (RNN) that is able to remember information over a long period of time, thus making them extremely useful for predicting stock prices. RNNs are well-suited to time series data and they are able to process the data step-by-step, maintaining an internal state where they cache the information they have seen so far in a summarised version. The successful prediction of a stock's future price could yield a significant profit.

Aim
To predict stock prices according to real-time data values fetched from API.

Objective
The main objective of this project is to develop a web application that can predict stock price based on real-time data.

Project Scope
The project has a wide scope, as it is not intended to a particular organization. This project is going to develop generic software, which can be applied by any businesses organization. Moreover it provides facility to its users. Also the software is going to provide a huge amount of summary data.

Technology Used:
Languages:
HTML
CSS
JAVASCRIPT
PYTHON
FrameWork:
BOOTSTRAP
DJANGO
Deployment:
Click to see deployement (NOTE: Deployement not working): Heroku
Machine-Learning Algorithms:
MULTIPLE LINEAR REGRESSION
ML/DL:
NumPy
Pandas
scikit-learn
Database:
SQLite
API used for:
Yahoo Finance API
REST API
IDE:
VS Code
pyCharm
Jupyter Notebook
OS used for testing:
MacOS
Ubuntu
Windows
Designed using:
AdobeXD
Figma
Prerequisites:
  Django==3.2.6
  django-heroku==0.3.1
  gunicorn==20.1.0
  matplotlib==3.5.2
  matplotlib-inline==0.1.3
  numpy==1.23.0
  pandas==1.4.1
  pipenv==2022.6.7
  plotly==5.9.0
  requests==2.28.1
  scikit-learn==1.1.1
  scipy==1.8.1
  seaborn==0.11.2
  sklearn==0.0
  virtualenv==20.14.1
  virtualenv-clone==0.5.7
  yfinance==0.1.72
Project Installation:
STEP 1: Clone the repository from GitHub.

  git clone https://github.com/Kumar-laxmi/Stock-Prediction-System-Application.git
STEP 2: Change the directory to the repository.

  cd Stock-Prediction-System-Application
STEP 3: Create a virtual environment (For Windows)

  python -m venv virtualenv
(For MacOS and Linux)

  python3 -m venv virtualenv
STEP 4: Activate the virtual environment. (For Windows)

  virtualenv\Scripts\activate
(For MacOS and Linux)

  source virtualenv/bin/activate
STEP 5: Install the dependencies.

  pip install -r requirements.txt
STEP 6: Migrate the Django project. (For Windows)

  python manage.py migrate
(For MacOS and Linux)

  python3 manage.py migrate
STEP 7: Run the application. (For Windows)

  python manage.py runserver
(For MacOS and Linux)

  python3 manage.py runserver
Output Screen-shots:
The Home page of the application that displays real time data of stock prices. image

To Predict stock price we move on to predicition page where we need to enter valid ticker value and number of days and click predict button. image

This page displays the predicted stock price alsong with searched ticker details and also generating unique QR Code to view the predicted result. image

The Left Graph is the real time stock price of the searched ticker for past 1day & the Right Graph is the predicted stock price for the number of days searched. image

The Ticker Info page displays the details of all the valid tickers accepted by the application. image

Disclaimer
This software is for educational purposes only. USE THE SOFTWARE AT YOUR OWN RISK. THE AUTHORS AND ALL AFFILIATES ASSUME NO RESPONSIBILITY FOR YOUR TRADING RESULTS. Do not risk money which you are afraid to lose. There might be bugs in the code - this software DOES NOT come with ANY warranty!
