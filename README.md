# 🚗 Car Price Prediction (mashina.kg)

This project demonstrates the full pipeline of collecting, cleaning, and modeling real-world car data from [mashina.kg](https://www.mashina.kg/). The goal is to predict the price of **Toyota** cars listed in Kyrgyzstan.

## 📌 Workflow

- Web scraping with BeautifulSoup
- Data preprocessing and feature engineering
- Training Linear Regression and Random Forest Regressor models
- Feature importance visualization

## 🧠 Features Used

- Year of production
- Engine volume
- Mileage
- Fuel type
- Gearbox mechanism
- Steering wheel location

## 📈 Model Performance

| Model                 | Score |
|----------------------|----------|
| Linear Regression     | ~0.54    |
| Random Forest Regressor | ~0.82 |

## 📊 Most Important Features
1. Engine volume
2. Year of production
3. Mileage

## 🛠️ Libraries
`pandas`, `scikit-learn`, `matplotlib`, `seaborn`, `BeautifulSoup`

Made by Ruslan Sadyrbekov
