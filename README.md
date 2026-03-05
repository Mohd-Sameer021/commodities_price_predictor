# Commodities Price Predictor

This project is a Machine Learning based web application that predicts the price of cars and laptops.

Users can enter product specifications and the system predicts the estimated price using trained ML models.

## Technologies Used

Python  
Pandas  
Scikit-learn  
Flask  
HTML  
CSS  

## Dataset

The datasets used in this project are:

quikr_car.csv  
laptop_data.csv  

These datasets were cleaned and preprocessed before training the models. After preprocessing i downloaded it :

Cleaned_Car_data.csv
Cleaned_laptop_data.csv

## Models

car_model.pkl – trained car price prediction model  
laptop_model.pkl – trained laptop price prediction model  

## Project Structure

app.py – Flask application  
templates/ – HTML files for frontend  
static/ – CSS and styling files  
car_cleaned.csv – car dataset  
laptop_cleaned.csv – laptop dataset  

## How to Run

Install dependencies:

pip install pandas numpy scikit-learn flask

Run the project:

python app.py

Open browser and go to:

http://127.0.0.1:5000/