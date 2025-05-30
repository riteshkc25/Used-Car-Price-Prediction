# 🚗 Comparative Analysis of Machine Learning Models for Used Car Price Estimation


## 📌 Objective  
This project aims to build a robust machine learning model to predict **price of used cars** using a number of features such as horsepower, mileage, make, model, year, engine type, transmission, fuel type, and location. The goal is to evaluate different models using multiple performance metrics to select the model with the best performance for deployment or further optimization.

---

## 📚 Background  
The used vehicle market is large and fairly dynamic, primarily caused by various factors that contribute to value determination, such as - but are not limited to - specifications of the vehicle (that is, particulars like horsepower, engine mileage, and fuel type), and external factors (such as geographical location and dealership). This can make it more complicated to establish a fair market value of a vehicle for both buyer or seller.

By building an intelligent price model, this project seeks to support consumers in making informed decisions and help dealerships to price or discount their inventory more strategically and competitively. 

---

## ❓ Problem Statement  
Manually determining the fair price of the vehicle is often both subjective and labor-intensive. Existing valuation techniques, as well as pricing calculators and pricing databases, may struggle with flexibility in adjusting for variability due to changes in market trends or variability across places.

---

## 🎯 Project Goals  
- Build, tune, and evaluate machine learning models that can predict the **price of used cars** based on historical data.  
- Handle both **numerical features** (e.g., mileage, year) and **categorical features** (e.g., make, fuel type, transmission).  
- Select the best-performing model using objective performance metrics.  

---

## ✅ Success Criteria  
- **High Accuracy:** Achieve a strong coefficient of determination (R²) and low Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).  
- **Generalization:** Minimize overfitting through cross-validation and train-test comparisons.  
- **Interpretability:** Provide clear insights into **feature importance** and model behavior.  
- **Scalability:** Ensure that the approach can scale to large datasets without performance bottlenecks.

---

## 🛠️ Tools & Technologies  
- **Language:** Python  
- **Core Libraries:**  
  - `pandas`  
  - `numpy`  
  - `seaborn`  
  - `matplotlib`  

---

## 📂 Repository Structure  
```
├── archive.zip                         # Raw imported datasets
├── selected_car_dataframe.parquet      # dataframe with selected attributes
├── car_price.pdf                       # Python scripts for data preprocessing and training
├── randomForest_model.joblib           # Saved model file for deployment
├── README.md                           # Project overview
```

---

## 📈 Future Work  
- Integrate real-time pricing APIs for dynamic model updates  
- Deploy the best-performing model as a web app  
- Explore deep learning techniques for improved performance  
- Localize predictions by incorporating region-based economic indicators

---

## 📊 Datasets Used in This Analysis
https://www.kaggle.com/datasets/ananaymital/us-used-cars-dataset
