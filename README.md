# Stock Price Prediction System

## Introduction

Predicting stock prices is a cumbersome task as it does not follow any specific pattern. Changes in the stock prices are purely based on supply and demand during a period of time. In order to learn the specific characteristics of a stock price, we can use an algorithm to identify these patterns through machine learning. One of the most well-known networks for series forecasting is LSTM (long short-term memory) which is a Recurrent Neural Network (RNN) that is able to remember information over a long period of time, thus making them extremely useful for predicting stock prices. RNNs are well-suited to time series data and they are able to process the data step-by-step, maintaining an internal state where they cache the information they have seen so far in a summarized version. The successful prediction of a stock's future price could yield a significant profit.

## Aim

To predict stock prices according to real-time data values fetched from API.

## Objective

The main objective of this project is to develop a web application that can predict stock price based on real-time data.

## Project Scope

The project has a wide scope, as it is not intended for a particular organization. This project is going to develop generic software, which can be applied by any business organization. Moreover, it provides a facility to its users. Also, the software is going to provide a huge amount of summary data.

## Technology Used

### Languages:
- HTML
- CSS
- JavaScript
- Python

### Frameworks:
- Bootstrap
- Django

### Deployment:
- Heroku

### Machine-Learning Algorithms:
- Multiple Linear Regression

### ML/DL Libraries:
- NumPy
- Pandas
- scikit-learn

### Database:
- SQLite

### APIs used for:
- Yahoo Finance API
- REST API

### IDEs:
- VS Code
- PyCharm
- Jupyter Notebook

### Operating Systems used for testing:
- MacOS
- Ubuntu
- Windows

### Designed using:
- AdobeXD
- Figma

## Prerequisites

- Django==3.2.6
- django-heroku==0.3.1
- gunicorn==20.1.0
- matplotlib==3.5.2
- matplotlib-inline==0.1.3
- numpy==1.23.0
- pandas==1.4.1
- pipenv==2022.6.7
- plotly==5.9.0
- requests==2.28.1
- scikit-learn==1.1.1
- scipy==1.8.1
- seaborn==0.11.2
- sklearn==0.0
- virtualenv==20.14.1
- virtualenv-clone==0.5.7
- yfinance==0.1.72

## Project Installation

### Step 1: Clone the repository from GitHub
git clone https://github.com/Kumar-laxmi/Stock-Prediction-System-Application.git

### Step 2: Change the directory to the repository
cd Stock-Prediction-System-Application

### Step 3: Create a virtual environment
python -m venv virtualenv

### Step 4: Activate the virtual environment
virtualenv\Scripts\activate

### Step 5: Install the dependencies
pip install -r requirements.txt

### Step 6: Migrate the Django project
python manage.py migrate

### Step 7: Run the application
python manage.py runserver

### Output Screen-shots
The Home page of the application that displays real-time data of stock prices. [image]
To Predict stock price we move on to prediction page where we need to enter a valid ticker value and number of days and click predict button. [image]
This page displays the predicted stock price along with searched ticker details and also generating a unique QR Code to view the predicted result. [image]
The Left Graph is the real-time stock price of the searched ticker for the past 1 day & the Right Graph is the predicted stock price for the number of days searched. [image]
The Ticker Info page displays the details of all the valid tickers accepted by the application. [image]


### Disclaimer
This software is for educational purposes only. USE THE SOFTWARE AT YOUR OWN RISK. THE AUTHORS AND ALL AFFILIATES ASSUME NO RESPONSIBILITY FOR YOUR TRADING RESULTS. Do not risk money which you are afraid to lose. There might be bugs in the code - this software DOES NOT come with ANY warranty!
