# Automobile Price Prediction using Linear and Lasso Regression

## Overview
This project performs regression analysis to predict the prices of automobiles based on various features such as engine size, horsepower, fuel type, and more. The goal is to build a predictive model that can accurately estimate the price of a car using linear and lasso regression techniques. The project demonstrates both multiple regression approaches. 

![Alt text](images/photo_2024-10-09_20-48-42.jpg)


## Table of Contents
1. [Installation](#installation)
2. [Dataset](#dataset)
3. [Technologies Used](#technologies-used)
4. [Project Structure](#project-structure)
5. [Modeling](#modeling)
6. [Results](#results)
7. [Usage](#usage)
8. [Conclusion](#conclusion)
9. [Contact](#contact)

## Installation
To replicate this project, clone the repository and install the necessary dependencies.

```bash
git clone https://github.com/your-username/automobile-price-regression.git
cd automobile-price-regression
```

Create a virtual environment and activate it:
```bash
python -m venv env
source env/bin/activate  # On Windows use: env\Scripts\activate
```

Install the required dependencies:
```bash
pip install -r requirements.txt
```


## Technologies Used
- **Programming Language**: Python
- **Data Analysis**: Pandas, NumPy
- **Data Visualization**: Matplotlib, Seaborn
- **Machine Learning**: Scikit-learn
- **Development Environment**: Google Colab
- **Version Control**: Git


## Dataset
The dataset used in this project contains various features related to automobiles, including:
- **Make**: The brand of the car
- **Fuel Type**: The type of fuel used (e.g., gas, diesel)
- **Engine Size**: The size of the car's engine
- **Horsepower**: The power of the engine
- **Price**: The price of the car (target variable)

- **Source**: [https://www.kaggle.com/datasets/toramky/automobile-dataset?resource=download]
- **Preprocessing**: Handling missing values, encoding categorical variables, and scaling numerical features.

## Project Structure
```
├── data/               # Contains the dataset
├── notebooks/          # Jupyter notebooks for analysis
├── models/             # Saved machine learning models
├── README.md           # Project documentation
└── requirements.txt    # Dependencies
```

## Modeling
The following steps were performed for the regression analysis:

1. **Exploratory Data Analysis (EDA)**: 
    - Visualization of data distributions and relationships between features.
    - Handling of missing data and outliers.

2. **Linear Regression**:
    - A model predicting the car price based on multiple features like engine size, horsepower, fuel type, and more.

3. **Lasso Regression**:
    - A model incorporating regularization techniques using multiple features like engine size, horsepower, fuel type, and more.

4. **Model Evaluation**:
    - Evaluation metrics include Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared value.

## Results
- Best model: **Multiple Linear Regression**
- Key findings:
    - Features such as engine size, horsepower, and fuel type have a significant impact on car prices.
    - The model achieved an R-squared score of [0.85].

- Performance metrics:
    - **MAE**: 2366.64
    - **MSE**: 12326591.13
    - **R-squared**: 0.82
    - **RMSE**: 3510.92


## Usage

Example of predictions:
```
| Engine Size | Horsepower | Fuel Type | Predicted Price |
|-------------|------------|-----------|-----------------|
| 2.0L        | 130        | Gas       | $15,000         |
| 3.5L        | 200        | Diesel    | $25,000         |
```

## Conclusion
This project demonstrates the use of linear and lasso regression to predict automobile prices. The linear regression model provided better results than the lasso regression model, emphasizing the importance of incorporating multiple features. Future work could include polynomial regression, or incorporating another regularization techniques like Ridge regression.

## Contact
For further information, feel free to reach out:
- **Name**: Ojo Timilehin
- **Portfolio**: https://ojotimilehin01.wixsite.com/ojotimi
- **Email**: Ojotimilehin01@gmail.com

---

