# 🚗 Car Dekho: Used Car Price Prediction Using Regression Analysis  

## 📌 Project Overview  
This project leverages **machine learning regression techniques** to predict the prices of used cars, enabling better decision-making for buyers, sellers, and dealerships.  
Through **EDA, feature engineering, and model evaluation**, the project identifies key drivers of car value such as **vehicle age, mileage, engine capacity, and brand influence**.  

By analyzing patterns in pricing and using advanced regression models, the solution provides **transparent, data-driven insights** into what makes a car retain or lose its value.  

---

## 📊 Dataset Description  

- **car_name** → Car's full name, including brand and model  
- **brand** → Brand name of the car  
- **model** → Specific model name  
- **seller_type** → Type of seller (Dealer / Individual / Trustmark Dealer)  
- **fuel_type** → Fuel used (Petrol / Diesel / LPG / CNG / Electric)  
- **transmission_type** → Transmission (Manual / Automatic)  
- **vehicle_age** → Years since the car was bought  
- **mileage** → Kilometers run per litre  
- **engine** → Engine capacity (in cc)  
- **max_power** → Maximum power (BHP)  
- **seats** → Seating capacity  
- **selling_price** → Actual listed selling price  

---

## 🛠️ Skills & Tools Used  
- **Programming & Data Handling**: Python (Pandas, NumPy), Data Visualization (Matplotlib, Seaborn)  
- **Machine Learning Algorithms**: Linear Regression, Decision Tree, Random Forest, XGBoost, LightGBM  
- **Feature Engineering**: Categorical Encoding, Interaction Features (Engine-to-Power Ratio), Log Transformation, Scaling  
- **Model Evaluation**: R² Score, MAE, MAPE, RMSE, Median Absolute Error (MedAE)  
- **Model Explainability**: SHAP Values, Feature Importance Analysis
  
---

## 🔎 Key Insights  
- **XGBoost proved the most reliable model**, achieving the **lowest MAPE of 13.3%** with a MedAE of ~54k, making it the best choice for consistent pricing predictions.  
- **Random Forest and LightGBM also delivered strong performance** (MAPE ~13.5%), but LightGBM placed a heavier penalty on vehicle age, while Random Forest leaned more on power ratio and fuel type effects.  
- **Vehicle Age and Engine Power Ratio emerged as the strongest pricing drivers**: older cars consistently lose value, while a higher engine-to-power ratio significantly boosts prices.  
- **SHAP analysis provided richer interpretability**: for example, high mileage improves perceived value in budget cars (fuel efficiency), but reduces it in premium cars (wear and tear).  
- **Fuel type matters**: Diesel vehicles typically carried a negative price impact across models, while petrol and hybrid configurations sustained better value.  
- Together, these insights highlight how **advanced ensemble methods** not only improve accuracy but also **capture nuanced trade-offs**—balancing performance, depreciation, and efficiency in predicting used car prices.  

By combining predictive accuracy with explainability (SHAP), the model ensures **fair, transparent, and trustworthy car pricing recommendations**.  

---


---
