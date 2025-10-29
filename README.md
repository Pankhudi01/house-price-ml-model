# Real Estate Price Prediction using Machine Learning
This project predicts house/real estate prices using machine learning models in Python.  
It covers data cleaning, exploratory data analysis (EDA), feature engineering, and model training through hyperparameter tuning with Scikit-learn.

## Features
- End-to-end ML pipeline (data preprocessing → model training → evaluation)
- Implemented **Linear Regression, Lasso and Decision Tree Regressor**
- Hyperparameter tuning with `GridSearchCV`
- Achieved **R² = 0.81** on test set
- Visualizations with Matplotlib & Seaborn

## Project Structure
- `data/` → sample dataset or link to dataset source  
- `notebooks/` → EDA and experiments  
- `src/` → modular Python scripts  
- `requirements.txt` → dependencies  

## How to Run
```bash
git clone https://github.com/your-username/real-estate-price-prediction.git
cd real-estate-price-prediction
pip install -r requirements.txt
python src/model_training.py.
