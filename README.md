# 🏡 House Rent Price Prediction using Linear Regression

This project predicts house rent prices using machine learning techniques. We perform Exploratory Data Analysis (EDA) and build a Linear Regression model on a dataset of 10,000 samples with 10 features.

---

## 📌 Objective

To build a predictive model that estimates monthly rent prices for houses based on features such as:
- Bedrooms, Bathrooms, Area (sqft)
- Furnishing status
- Location rating
- Age of house, Floor number
- Distance to city center
- Parking availability

---

## 📊 Dataset Overview

- 🔢 Rows: 10,000  
- 🧾 Columns: 10 features + 1 target (`rent_price`)  
- 📂 Type: Synthetic dataset (can be replaced with real-world housing data)

---

## 📈 Features Used

| Feature                  | Description                          |
|--------------------------|--------------------------------------|
| `bedrooms`              | Number of bedrooms                   |
| `bathrooms`             | Number of bathrooms                  |
| `area_sqft`             | Area in square feet                  |
| `balconies`             | Number of balconies                  |
| `floor`                 | Floor number                         |
| `location_rating`       | Location score (1–5)                 |
| `age_years`             | Age of the house                     |
| `furnishing`            | Furnished or not (1 = Yes, 0 = No)   |
| `parking_spaces`        | Number of parking slots              |
| `distance_to_city_center_km` | Distance from city center       |

---

## 🧪 Technologies Used

- Python 🐍
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 🔍 EDA Highlights

- Correlation heatmap
- Distribution plots
- Boxplots for categorical features
- Summary statistics

---

## 🧠 Machine Learning Model

- **Algorithm:** Linear Regression
- **Metric Used:** R² Score, Mean Squared Error (MSE)
- **Train/Test Split:** 80/20

---
```
## 📂 Project Structure
├── house_rent_price_dataset.csv
├── final_house_rent_predictions.csv
├── House_Rent_Price_Prediction.ipynb
├── README.md
└── requirements.txt
```

---

## 📌 How to Run

1. Clone the repository  
2. Install dependencies  
```bash
pip install -r requirements.txt

jupyter notebook House_Rent_Price_Prediction.ipynb

## 📊 Sample Output

Here is a preview of the dataset with predicted house prices:

| bedrooms | bathrooms | area_sqft | balconies | floor | location_rating | age_years | furnishing | parking_spaces | distance_to_city_center_km | rent_price | Predicted_house_price |
|----------|-----------|-----------|-----------|-------|-----------------|-----------|------------|----------------|----------------------------|------------|------------------------|
| 3        | 3         | 1844      | 0         | 18    | 2               | 0         | 1          | 1              | 9.848264                   | 73.265777  | 75.891932             |
| 1        | 3         | 2804      | 0         | 17    | 2               | 27        | 1          | 1              | 23.306474                  | 88.438904  | 84.897799             |
| 4        | 1         | 989       | 0         | 4     | 3               | 0         | 1          | 1              | 19.411022                  | 52.137590  | 58.331777             |
| 5        | 3         | 1565      | 1         | 6     | 1               | 14        | 0          | 1              | 6.514362                   | 71.847190  | 71.285016             |
| 1        | 1         | 2379      | 0         | 6     | 2               | 20        | 0          | 1              | 4.340231                   | 65.450705  | 62.139575             |

👉 **Note**: This is just a small preview. The full dataset contains **10,000+ rows** which can be downloaded from the repository.
```




✍️ Author
Suraj Kumar

- [LinkedIn](https://www.linkedin.com/in/suraj-kumar-2307skp/)

