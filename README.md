# Melbourne Housing Price Prediction

End-to-end machine learning project that analyzes and predicts housing prices using the Melbourne Housing Market dataset.

## Project Overview

This project demonstrates a complete machine learning workflow including:

- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- Feature engineering
- Baseline modeling using Linear Regression
- Hyperparameter tuning of a Random Forest model
- Model evaluation and comparison
- Feature importance analysis
- Prediction performance visualization

The objective is to understand the factors influencing housing prices and build a predictive model capable of estimating property values.

---

## Dataset

The dataset contains housing transaction data from Melbourne, Australia.

Key variables include:

- Rooms
- Distance from city center
- Land size
- Building area
- Number of bathrooms
- Year built

Target variable:

Price

---

## Models Used

### Linear Regression

Used as a baseline model to estimate housing prices.

### Random Forest Regressor

A tuned Random Forest model was used to capture nonlinear relationships between housing features and price.

Hyperparameter tuning was performed using **RandomizedSearchCV**.

---

## Results

The Random Forest model significantly outperformed the Linear Regression baseline.

Key insights:

- Property size and number of rooms strongly influence price
- Distance from the city center negatively correlates with housing value
- Structural property characteristics play a major role in price prediction

---

## Project Structure
melbourne-housing-price-prediction
│
├── End_to_End_Machine_Learning.ipynb
├── requirements.txt
└── README.md

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Author

Richard Hanly  
Bachelor's in Software Development
