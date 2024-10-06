# Medical Insurance Cost Prediction

This project focuses on predicting the medical insurance costs of individuals based on various features such as age, gender, BMI, number of children, smoking habits, and region. The project involves data analysis and the use of machine learning models to estimate the insurance costs.

## Table of Contents

- [Overview](#overview)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Models Used](#models-used)
- [Results](#results)

## Overview

The aim of this project is to create a predictive model that can estimate an individual's medical insurance cost based on their personal information. The project utilizes machine learning techniques to build a regression model that predicts the insurance cost as accurately as possible.

Key steps include:
- Data Preprocessing (Handling missing values, categorical encoding)
- Exploratory Data Analysis (Visualizing relationships between features and costs)
- Building Regression Models
- Evaluating Model Performance

## Project Structure
```plaintext
Medical-Insurance-Cost-Prediction/
├── insurance.csv                               # Contains dataset files
├── Medical Insurance Cost Prediction.ipynb     # Include Code
├── README.md                                   # Project documentation
```

## Installation

Clone the repository:

   ```bash
   git clone https://github.com/harshk6/Medical-Insurance-Cost-Prediction.git
   cd Medical-Insurance-Cost-Prediction
   ```
## Usage

To run the analysis and model training, follow these steps:

1. Open a terminal and navigate to the project directory:

   ```bash
   cd Medical-Insurance-Cost-Prediction
   ```
2. Start Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Open the notebook located in the notebooks folder:
   ```bash
   Medical Insurance Cost Prediction.ipynb
   ```
4. Follow the steps in the notebook to preprocess the data, train the model, and evaluate the results.


The notebook contains code for:

- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Building and training machine learning models
- Evaluating model performance


## Models Used

This project uses several machine learning models for predicting insurance costs, including:

- **Linear Regression**
- **AdaBoost Regressor**
- **Random Forest Regressor**
- **Gradient Boosting Regressor**
- **XgBoost Regressor**
- **KNeighbors Regressor**
- **Neural Network**

Each model's performance is evaluated using metrics such as **R2 Score**.

## Results

The final model chosen for predicting medical insurance costs is **Gradient Boosting Regressor**. 

### Performance Metric

- **R² Score**

### Model Comparison

| Model                     | R² Score      |
|---------------------------|---------------|
| Linear Regression         | 0.77856 |
| AdaBoost Regressor       | 0.88253 |
| Random Forest Regressor   | 0.87125 |
| Gradient Boosting Regressor| 0.88443 |
| XGBoost Regressor        | 0.88425 |
| KNeighbors Regressor      | 0.85024 |
| Neural Network            | 0.87418 |

### Visualizations

Below are visualizations that compare the predicted values with actual insurance costs:

- ![image](https://github.com/user-attachments/assets/35d25efb-f9d6-457c-b3f6-32d13ef97908)
- ![image](https://github.com/user-attachments/assets/9961f5a3-ffc6-4b82-91e8-c91381e4e4b2)
- ![image](https://github.com/user-attachments/assets/8b7d1ecd-2a25-48a5-b65f-aa2a3af858e6)




The results indicate that the **Gradient Boosting Regressor** performs the best among the models tested, achieving the highest R² score of 0.88443, suggesting a more accurate prediction of medical insurance costs.

