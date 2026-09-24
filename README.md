# Car Price Prediction using Machine Learning

A machine learning project that predicts the selling price of used cars based on vehicle specifications and other attributes.

## Project Overview

This project follows a complete machine learning workflow, including:

- Data loading and exploration
- Exploratory Data Analysis (EDA)
- Feature selection
- Outlier analysis
- Train-test splitting
- Feature transformation
- Categorical feature encoding
- Machine learning pipeline
- Linear Regression model training
- Model evaluation

## Dataset

The dataset contains used-car information such as:

- Car brand and model
- Vehicle age
- Kilometers driven
- Seller type
- Fuel type
- Transmission type
- Mileage
- Engine capacity
- Maximum power
- Number of seats
- Selling price

**Target Variable:** `selling_price`

## Data Preprocessing

The project applies the following preprocessing techniques:

- Numerical feature analysis
- Log transformation for skewed numerical features
- One-Hot Encoding for categorical features
- `ColumnTransformer` for combining preprocessing steps
- `Pipeline` for integrating preprocessing with the model

## Machine Learning Model

### Linear Regression

Linear Regression is used to predict the selling price of a used car.

The preprocessing steps and regression model are combined into a Scikit-learn Pipeline, making the complete workflow reusable and consistent.

## Model Evaluation

The model is evaluated using:

- **MAE** — Mean Absolute Error
- **MSE** — Mean Squared Error
- **RMSE** — Root Mean Squared Error
- **R² Score** — Coefficient of Determination

These metrics are used to measure prediction error and overall model performance.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Scikit-learn
- Google Colab / Jupyter Notebook

## Project Structure

```text
car-price-prediction-ml/
│
├── car_price_predict_pynb.ipynb
├── cardekho_dataset2.csv
└── README.md
```

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/yourusername/car-price-prediction-ml.git
cd car-price-prediction-ml
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scipy scikit-learn
```

### Run the Project

Open `car_price_predict_pynb.ipynb` using Jupyter Notebook, VS Code, or Google Colab and run the cells sequentially.


## Author

**Khushal Kumar**

