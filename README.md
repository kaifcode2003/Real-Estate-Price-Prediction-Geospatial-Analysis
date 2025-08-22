# 🏡 Pune House Price Prediction (Geospatial + ML)

This project builds an **end-to-end machine learning pipeline** to predict **house prices in Pune**.  
It combines **synthetic housing data** with **geospatial features** like distance to metro, schools, and downtown, along with socio-economic indicators such as crime rate.  

---

## 🚀 Features

- 📊 **Synthetic Housing Dataset** (500 records) with location, sqft, bedrooms, year built, and price  
- 🌍 **Geospatial Features**:
  - Distance to Pune Downtown  
  - Distance to nearest metro station  
  - Number of schools within 2 km  
  - Crime rate (simulated per location)  
- 🔎 **Exploratory Data Analysis (EDA)**:
  - Price distribution plots  
  - Correlation heatmap  
  - Location-wise price boxplots  
- 🤖 **Machine Learning Pipeline**:
  - Preprocessing with scaling & encoding  
  - Model training with **Ridge Regression**  
  - Evaluation with R² & MSE  
  - Feature importance visualization  

---

## 📂 Project Structure

```
📦 pune-house-price-prediction
 ┣ 📜 house_price_prediction.py   # Main script
 ┣ 📜 README.md                   # Documentation
 ┣ 📜 requirements.txt            # Dependencies
 ┗ 📂 data                        # (Optional: store CSVs for real data)
```

---

## ⚙️ Tech Stack

- **Python 3.9+**  
- `pandas`, `numpy` – data handling  
- `matplotlib`, `seaborn` – visualization & EDA  
- `scikit-learn` – preprocessing, modeling (Ridge Regression)  
- `geopy` – distance calculations  

---

## 📊 Model Performance

- **R² (R-squared):** ~0.85  
- **MSE:** varies depending on random noise in data  

✅ Model explains most of the variation in housing prices using both structural & location-based features.  

---

## 📈 Sample Visualizations

- Price distribution histogram  
- Correlation heatmap of numeric features  
- Boxplot of house prices by location  
- Feature importance (coefficients from Ridge regression)  
- Actual vs Predicted price scatterplot  

---

## 🔑 Key Learnings

- Feature engineering (distances, schools, crime) adds **strong predictive power**.  
- `scikit-learn Pipelines` ensure clean preprocessing + modeling.  
- Synthetic datasets can effectively demonstrate **real-world ML workflows**.  

---

## 📌 Next Steps

- Replace synthetic data with **real housing datasets**.  
- Try advanced models (Random Forest, XGBoost).  
- Deploy as a **Streamlit/Dash web app** for interactive predictions.  

---

👨‍💻 **Author:** *Mohd Kaif*  
🎓 B.Tech ECE (AI & ML Specialization) | 💻 ML • DSA • MERN Stack | 🔗 [[LinkedIn](http://www.linkedin.com/in/mohdkaif14)](#)

---

⚡ *“In real estate, location is everything — and data proves it!”*  
