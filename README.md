# AI Food Waste Prediction System

A machine learning-based system that predicts total food waste in tons using food, economic, population, and household-related factors.

## SDG Alignment

This project supports:

**SDG 12 – Responsible Consumption and Production**

The project focuses on food waste reduction by using machine learning to estimate the amount of food waste based on available factors.

## Problem Statement

Food waste is a major sustainability problem that results in wasted resources and economic losses. There is a need for data-driven approaches that can help estimate and understand food waste levels.

## Project Objective

The objective of this project is to develop a machine learning model that predicts total food waste in tons and demonstrate the prediction through a simple interactive application.

## Dataset

The project uses the **Worldwide Food Waste Dataset** available on Kaggle.

The dataset contains information including:

- Country
- Year
- Food Type
- Total Waste in Tons
- Food Economic Loss
- Average Waste per Capita
- Country Population
- Household Waste Percentage

## Methodology

The project follows these steps:

1. Dataset collection
2. Data inspection
3. Missing-value and duplicate checks
4. Exploratory Data Analysis
5. Correlation analysis
6. Categorical feature encoding
7. Train-test split
8. Random Forest Regression
9. Model evaluation
10. Interactive prediction prototype

## Exploratory Data Analysis

The project includes:

- Average food waste by food type
- Correlation heatmap
- Actual vs predicted food waste visualization

## Machine Learning Model

**Algorithm:** Random Forest Regressor

**Training/Test Split:** 80% / 20%

### Model Performance

| Metric | Result |
|---|---:|
| MAE | 2319.77 tons |
| RMSE | 3085.51 tons |
| R² | 0.956 |

## Interactive Prototype

A Gradio-based web interface was developed to allow users to enter food-waste-related information and obtain a predicted total food waste value.

### Main Inputs

- Country
- Food Type
- Year
- Food Economic Loss
- Average Waste per Capita
- Country Population
- Household Waste

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Gradio
- Google Colab

## Project Files

```text
AI-Food-Waste-Prediction/
│
├── AI_Food_Waste_Prediction.ipynb
├── feature_names.pkl
└── README.md
````

## Limitation

The selected dataset contains a very strong relationship between Food Economic Loss and Total Waste in Tons. Therefore, the high model performance should be interpreted with caution. Future versions should use more independent real-world variables for prediction.

## Future Scope

Possible improvements include:

* Using larger and more reliable real-world datasets
* Adding additional environmental and supply-chain variables
* Developing a mobile application
* Adding food waste reduction recommendations
* Integrating real-time data
* Comparing multiple machine learning algorithms

## Author

Ritik Kumar Yadav
