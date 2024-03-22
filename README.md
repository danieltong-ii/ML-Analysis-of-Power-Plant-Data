# ML Analysis of Combined Cycle Power Plant Data

## Introduction

This project focuses on analyzing the Combined Cycle Power Plant Data Set using Machine Learning (ML) techniques. The data set, collected over 6 years (2006-2011), includes hourly average ambient variables like Temperature (T), Ambient Pressure (AP), Relative Humidity (RH), and Exhaust Vacuum (V) to predict the net hourly electrical energy output (EP) of the plant. The project aims to model and predict energy output based on these ambient conditions, addressing the gap in efficiently predicting power output for better energy management and planning.

## Educational Context

As part of the DSCI 552 (Machine Learning for Data Science) course, this project provides a practical application of ML concepts, emphasizing the real-world utility of statistical learning in energy production sectors.

### Application of theory:

The analysis incorporates:
- **Linear Regression:** Both simple and multiple, to understand the relationship between each predictor and the energy output, and how predictors combined affect the output.
- **Polynomial Features and Interaction Terms:** To explore nonlinear associations and the effect of predictor interactions on the energy output.
- **K-Nearest Neighbor (KNN) Regression:** To apply a non-parametric method that considers the 'k' closest points to predict the output, comparing its performance against linear models.

## Technical Details

### Technologies used:
- **Python:** For programming with libraries like pandas, NumPy for data manipulation, matplotlib, and seaborn for visualization.
- **scikit-learn:** For implementing ML models, handling polynomial features, and evaluating model performance.

### Architecture overview:
The project adopts a structured ML workflow:
1. **Data Exploration:** Understanding the data through descriptive statistics and visualizations.
2. **Preprocessing:** Preparing data for modeling, including normalizing features for KNN.
3. **Modeling:** Applying simple linear regression, multiple regression with interaction terms, polynomial regression, and KNN regression.
4. **Evaluation:** Comparing models using metrics like Mean Squared Error (MSE) to determine the best approach.

### Main features:
- **Comprehensive Data Analysis:** Exploratory data analysis to uncover underlying patterns and relationships.
- **Multiple Regression Models:** Including simple linear, multiple linear with interactions, and polynomial regressions to capture linear and nonlinear relationships.
- **KNN Regression:** Using both normalized and raw features to predict energy output, identifying the optimal 'k'.
- **Model Comparison:** Evaluating different models to identify the most effective predictors and model structures.
