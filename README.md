# 🚗 Car Price Prediction using Machine Learning

## 📌 Project Overview

This project predicts the selling price of a used car using Machine Learning techniques. It involves data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and performance evaluation.

The model learns the relationship between various car features such as manufacturing year, present price, kilometers driven, fuel type, seller type, transmission type, and ownership to estimate the car's selling price.

---

## 📂 Dataset

The dataset contains information about used cars and their selling prices.

### Features

- Car Name
- Year
- Present Price
- Kms Driven
- Fuel Type
- Seller Type
- Transmission
- Owner

### Target Variable

- Selling Price

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📊 Project Workflow

### 1. Data Collection
- Loaded the car dataset.
- Explored the dataset structure.

### 2. Data Preprocessing
- Checked for missing values.
- Converted categorical variables into numerical values.
- Removed unnecessary columns (if applicable).
- Created new features such as car age.

### 3. Exploratory Data Analysis (EDA)
- Correlation Analysis
- Distribution of Selling Price
- Fuel Type Analysis
- Transmission Analysis
- Owner Analysis
- Heatmap Visualization
- Pair Plot Visualization

### 4. Feature Engineering
- Selected important features.
- Split dataset into training and testing sets.

### 5. Model Training
Machine Learning model used:

- Linear Regression

*(You can add more models later such as Random Forest Regressor or XGBoost.)*

### 6. Model Evaluation

The model performance is evaluated using:

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

---

## 📁 Project Structure

```
Car-Price-Prediction/
│
├── Car_price_prediction.ipynb
├── README.md
├── requirements.txt
└── dataset/
    └── car_data.csv
```

---

## 🚀 How to Run the Project

### Clone the Repository

```bash
git clone https://github.com/yourusername/Car-Price-Prediction.git
```

### Navigate to Project

```bash
cd Car-Price-Prediction
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open

```
Car_price_prediction.ipynb
```

---

## 📈 Results

The trained Machine Learning model predicts the selling price of used cars based on their specifications.

Model performance is evaluated using regression metrics such as:

- R² Score
- MAE
- MSE
- RMSE

---

## 📚 Skills Demonstrated

- Data Cleaning
- Data Preprocessing
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Data Visualization
- Machine Learning
- Regression Analysis
- Model Evaluation
- Python Programming

---

## 🔮 Future Improvements

- Hyperparameter Tuning
- Random Forest Regression
- XGBoost Regression
- Model Deployment using Flask or Streamlit
- Web Application for Price Prediction

---

## 📦 Requirements

```
numpy
pandas
matplotlib
seaborn
scikit-learn
jupyter
```

Install using:

```bash
pip install -r requirements.txt
```


## ⭐ If you found this project useful, don't forget to give it a Star!
