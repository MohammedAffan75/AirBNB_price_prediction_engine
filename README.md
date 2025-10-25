📊 Airbnb Dynamic Pricing Recommendation Engine  
*Predict smarter. Price better. Boost host revenue with data-driven insights.*

---

## 🚀 Project Overview

The **Airbnb Dynamic Pricing Recommendation Engine** is a machine learning-driven solution designed to help Airbnb hosts **predict optimal listing prices** based on key features such as location, reviews, property type, and host credibility.  
Using **Linear Regression** and a **Power BI dashboard**, this project delivers both predictive intelligence and visual insights to support better pricing decisions.

---

## ✅ Key Features

✅ Airbnb price prediction using machine learning  
✅ Linear Regression as core model (lightweight + interpretable)  
✅ Data cleaning & feature engineering pipeline in Python  
✅ Power BI dashboard with insights and interactive filters  
✅ Predictions stored in output CSV for easy usage  
✅ Insights on market trends (e.g., NYC has highest price levels)  

---

## 📂 Project Structure

airbnb-pricing-engine/
│
├─ data/ # Raw & cleaned datasets
├─ src/
│ ├─ preprocess.py # Data cleaning & feature engineering
│ ├─ model.py # Model training & evaluation
│ ├─ predict.py # Predict price for new listings
│
├─ outputs/
│ ├─ model.joblib # Saved trained model
│ ├─ predictions.csv # Final predicted prices
│
├─ powerbi/
│ ├─ dashboard.pbix # Power BI visual dashboard
│
└─ report.pdf # Final project report (summary)

---

## 📘 Dataset

📍 Source: Kaggle – *Airbnb Price Prediction Dataset*  
🗂 Contains features such as:
- `property_type`, `room_type`, `city`, `neighbourhood`
- `accommodates`, `bathrooms`, `bedrooms`, `beds`
- `review_scores_rating`, `number_of_reviews`
- `host_response_rate`, `host_since`
- `latitude`, `longitude`
- `price` (target variable)

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| 🐍 Python | Data processing & ML model |
| 📦 Pandas, Numpy | Data wrangling |
| 📈 Matplotlib, Seaborn | EDA & visualization |
| 🤖 Scikit-Learn | Model training |
| 💾 Joblib | Model serialization |
| 📊 Power BI | Dashboard & insights |
| 📁 CSV | Result storage |

---

## 📈 Model Performance

The **Linear Regression** model was trained on engineered features and evaluated based on **R² Score** and **MAE**.  
✅ The model performed well for predicting continuous price values.  
✅ Ideal for baseline model and easy explainability.

🚀 *Future improvement*: Try XGBoost, Random Forest, or LightGBM for performance boosts.

---

## 📊 Power BI Dashboard – Insights Delivered

✅ NYC listings had highest predicted prices  
✅ Entire apartments/homes are priced higher than private rooms  
✅ Review scores averaged above 4+  
✅ Beds, bathrooms, and property type significantly influence price  

---

## 🧮 How to Run the Project

###  1️⃣ Clone the repository
```
git clone https://github.com/your-username/airbnb-pricing-engine.git

 2️⃣ Install dependencies
pip install -r requirements.txt

 3️⃣ Clean & preprocess data
python src/preprocess.py

 4️⃣ Train the model
python src/model.py

 5️⃣ Predict price for new listing(s)
python src/predict.py

💡 Future Enhancements
✅ Advanced ML Models (RandomForest, XGBoost, LightGBM)
✅ Time-based dynamic pricing (seasonality trends)
✅ SHAP-based interpretability
✅ Deployment as web app (Flask/FastAPI + Streamlit UI)
✅ Real-time API-based suggestion engine
