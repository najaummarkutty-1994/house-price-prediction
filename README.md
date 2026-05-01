# 🏠 House Price Prediction using Machine Learning

## 📌 Project Overview
This project predicts house prices using machine learning based on features like number of bedrooms, bathrooms, house size, and lot size.

## 📊 Dataset
Real estate dataset containing over 1 million records (sampled for training efficiency).

## ⚙️ Technologies Used
- Python
- Pandas
- Scikit-learn
- Matplotlib

## 🤖 Models Used
- Linear Regression
- Random Forest Regressor (Best Performing Model)

## 📈 Results
- Linear Regression Error: ~345,000
- Random Forest Error: ~12,000

## 🔍 Visualizations
- House size vs price
- Bedrooms vs price
- Price distribution
- Actual vs Predicted comparison

- ## 🔍 Model Interpretation

### 📌 Feature Importance (Random Forest)

| Feature     | Importance |
|-------------|------------|
| House Size  | 0.403      |
| Bathrooms   | 0.256      |
| Acre Lot    | 0.234      |
| Bedrooms    | 0.085      |

### 📊 Key Insights
- **House size** is the most important factor affecting house price  
- **Bathrooms** have strong influence on price  
- **Lot size (acre lot)** also contributes significantly  
- **Bedrooms** have the least impact compared to other features  

### 📌 Linear Regression Insights
- Bathrooms show strong positive impact on price  
- House size and lot size increase price  
- Bedrooms showed a negative coefficient due to correlation with other features (multicollinearity)

## 🚀 How to Run
1. Open notebook in Google Colab
2. Upload dataset
3. Run all cells
4. Test prediction function

## 🎯 Key Learning
- Data cleaning
- Feature selection
- Model comparison
- Evaluation metrics

## 👤 Author
Built as a learning project in Data Analyst journey


## 👤 Author
Built as a learning project in Data Science & AI journey
