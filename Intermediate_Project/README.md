# 🏠 House Price Prediction (Intermediate Project)

## 📌 Description
This project aims to predict house prices based on various features such as living area, number of bedrooms, bathrooms, location, and other housing attributes. Machine learning models are used to analyze patterns in the data and make accurate predictions.

---

## 📊 Dataset
- **Source:** Kaggle (House Price India Dataset)
- **Description:**
  The dataset contains 14,000+ records of houses with 23 features including:
  - Living area
  - Number of bedrooms & bathrooms
  - Lot area
  - Number of floors
  - Location (latitude & longitude)
  - Year built & renovation details
  - Distance from airport
  - Final price (target variable)

---

## ⚙️ Steps Performed

### 1. Data Cleaning
- Checked for missing values
- Filled missing values using mean
- Removed unnecessary columns (`id`, `Date`)

### 2. Feature Engineering
- Created new feature: **house_age**
- Created binary feature: **is_renovated**

### 3. Exploratory Data Analysis (EDA)
- Correlation heatmap
- Scatter plots (Living Area vs Price)
- Distribution analysis

### 4. Model Building
- Linear Regression
- Decision Tree Regressor

### 5. Model Evaluation
Used evaluation metrics:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

---

## 📈 Results
- Linear Regression gives baseline performance
- Decision Tree improves prediction accuracy
- Key influencing features:
  - Living area
  - Grade of the house
  - Location (latitude/longitude)

---

## 🛠️ Tools & Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Visualizations
- Correlation Heatmap
- Scatter Plot (Actual vs Predicted)
- Feature Importance Graph

---

## 🧠 Conclusion
The project successfully demonstrates how machine learning can be used to predict house prices. Advanced techniques like feature engineering and model comparison improved the overall performance. Decision Tree performed better due to its ability to capture non-linear relationships.

---

## 👩‍💻 Author
B. Siri Varshitha

---

## ✅ Final Note
This project is part of the Data Science Lab work. All steps including data preprocessing, visualization, and model building were implemented independently.

