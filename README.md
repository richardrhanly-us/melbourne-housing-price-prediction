# Melbourne Housing Price Prediction

End-to-end machine learning project that analyzes and predicts housing prices using the Melbourne Housing Market dataset.

---

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

The dataset contains housing transaction data from Melbourne, Australia and includes structural and geographic attributes of residential properties.

Key variables include:

- Rooms  
- Distance from the city center  
- Land size  
- Building area  
- Number of bathrooms  
- Year built  

Target variable:

```
Price
```

---

## Machine Learning Models

### Linear Regression

Linear Regression was used as a baseline model to estimate housing prices and provide a point of comparison for more flexible models.

### Random Forest Regressor

A tuned Random Forest model was implemented to capture nonlinear relationships between property features and housing prices.

Hyperparameter tuning was performed using **RandomizedSearchCV** to improve model performance.

---

## Model Evaluation

Models were evaluated using standard regression metrics:

- **MAE (Mean Absolute Error)**  
- **RMSE (Root Mean Squared Error)**  
- **R² (Coefficient of Determination)**  

The Random Forest model significantly outperformed the baseline Linear Regression model, explaining a larger portion of variance in housing prices and producing lower prediction error.

---

## Key Insights

Exploratory analysis revealed several important relationships:

- Larger homes with more rooms generally have higher prices  
- Properties located farther from the city center tend to have lower prices  
- Structural features such as land size and building area strongly influence property value  

Feature importance analysis confirmed that property size and location-related attributes are major contributors to price prediction.

---

## Project Structure

```
melbourne-housing-price-prediction
│
├── End_to_End_Machine_Learning.ipynb
├── requirements.txt
└── README.md
```

---

## Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## How to Run the Project

1. Clone the repository

```
git clone https://github.com/YOUR_USERNAME/melbourne-housing-price-prediction.git
```

2. Install dependencies

```
pip install -r requirements.txt
```

3. Open the notebook

```
End_to_End_Machine_Learning.ipynb
```

---

## Author

Richard Hanly  
Bachelor's in Software Development

---
