# 🏠 Delhi House Price Prediction



## 📌 Overview

The **Delhi House Price Prediction** project is a machine learning-based solution designed to estimate house prices in Delhi using historical housing data. This project can benefit **home buyers**, **property sellers**, **real estate agents**, and **investors** by providing data-driven insights into property pricing.

With the rapid growth of the real estate market in Delhi, having an intelligent prediction system can help stakeholders make informed decisions. This project uses regression algorithms and exploratory data analysis to build an accurate and interpretable house price prediction model.

---

## 📊 Dataset Description

- **Source**: Kaggle
- **Total Rows**: 1,259
- **Total Columns**: 11

| Column Name   | Description                                           |
|---------------|-------------------------------------------------------|
| Area          | Built-up area of the property in square feet          |
| BHK           | Number of bedrooms                                    |
| Bathroom      | Number of bathrooms                                   |
| Furnishing    | Furnishing status (e.g., Furnished, Semi-Furnished)  |
| Locality      | Area/location of the house within Delhi               |
| Parking       | Number of parking spaces available                    |
| Price         | Total price of the property in Indian Rupees (INR)    |
| Status        | Construction status (Ready to Move/Under Construction)|
| Transaction   | Nature of transaction (New Booking/Resale)            |
| Type          | Property type (e.g., Builder Floor, Apartment, etc.)  |
| Per_Sqft      | Price per square foot                                 |

---

## 🔍 Exploratory Data Analysis (EDA)

Key insights uncovered during EDA include:

- **Localities like Punjabi Bagh, Lajpat Nagar, and Vasant Kunj** have consistently higher property prices.
- Property prices **positively correlate** with area, number of bedrooms (BHK), and bathrooms.
- **Builder floor properties** are highly preferred, indicating a trend toward independent and customizable living.
- **New bookings** are more expensive than resale properties, likely due to modern amenities and better construction quality.

Charts and visualizations were created using **Matplotlib** and **Seaborn** to support these findings.

---

## 🧠 Machine Learning Models Used

Two popular regression models were trained and evaluated:

1. **Decision Tree Regressor**  
   - Quick and interpretable but tends to overfit on small datasets.

2. **Random Forest Regressor**  
   - An ensemble model that combines multiple decision trees.
   - Achieved the best performance with an accuracy of **84.98%**.
   - Robust to outliers and handles high-dimensional data well.

### 📈 Model Performance Metrics
- **Train/Test Split**: 80/20
- **Evaluation Metrics**: R² Score, Mean Absolute Error (MAE), Mean Squared Error (MSE)
- **Best Model**: `RandomForestRegressor`

---

## 🛠 Tools & Technologies

- **Programming Language**: Python
- **Libraries**:
  - Data Analysis: `Pandas`, `NumPy`
  - Visualization: `Matplotlib`, `Seaborn`
  - Machine Learning: `scikit-learn`
- **Environment**: Jupyter Notebook

---

## 🎯 Use Cases

- 🧍 **Buyers**: Estimate fair price for a property before making a purchase.
- 🏢 **Sellers/Builders**: Determine optimal selling prices based on location and features.
- 💼 **Agents**: Use the tool as part of real estate consulting services.
- 📊 **Analysts/Researchers**: Understand Delhi’s property market trends and pricing dynamics.

---

## 🧩 Future Improvements

- Deploy the model using **Streamlit** or **Flask** for a user-friendly web interface.
- Integrate with **Google Maps API** for location-based insights.
- Include **time-based features** like construction year to improve predictions.
- Add **user input validation** and error handling in deployed versions.

---

## 📌 Conclusion

This project demonstrates how machine learning can be leveraged to understand and predict house prices in a real-world urban setting like Delhi. The insights gained from EDA combined with high-performing regression models offer a practical solution for anyone involved in the housing market.

---


