# OIB-SIP-task-4
Data science project
#  Car Price Prediction Model

This project aims to build a *Machine Learning regression model* to predict the *price of a car* based on various features such as brand, year, mileage, fuel type, transmission, and more. It's a practical use case in the automotive and e-commerce sectors for estimating car values.

---

##  Objective

Analyze the impact of different features on car price
Build a regression model to predict car prices accurately
Provide insights through data visualization

---

##  Dataset Overview

The dataset includes various attributes such as:
  - Car_Name
  - Year
  - Selling_Price
  - Present_Price
  - Kms_Driven
  - Fuel_Type
  - Seller_Type
  - Transmission
  - Owner

 Example:

| Car_Name | Year | Selling_Price | Present_Price | Kms_Driven | Fuel_Type | Transmission | Owner |
|----------|------|----------------|----------------|-------------|-----------|--------------|-------|
| Swift    | 2014 | 3.35          | 5.59          | 27000       | Petrol    | Manual       | 0     |

---

##  Tools & Libraries Used

Python
Pandas, NumPy
Matplotlib & Seaborn (EDA & visualization)
Scikit-learn (modeling)
Jupyter Notebook

---

##  Preprocessing Steps

Handled categorical variables using *One-Hot Encoding*
Removed unnecessary columns (e.g. car names)
Checked for missing values
Scaled features if necessary
Split the dataset into training and test sets

---

##  Model Building

Trained and compared several regression models:
*Linear Regression*
*Decision Tree Regressor*
*Random Forest Regressor*  (best performer)

---

##  Model Evaluation

Metrics used:
*R² Score*
*Mean Absolute Error (MAE)*
*Mean Squared Error (MSE)*
*Root Mean Squared Error (RMSE)*

 *Random Forest Regressor* achieved the best performance with high accuracy on test data.

---

##  Project Structure
car-price-prediction/
│
├── car_data.csv                   # Dataset
├── car_price_prediction.ipynb     # Jupyter notebook with code & analysis
├── model.pkl                      # Trained model saved using pickle
├── README.md                      # Project overview
