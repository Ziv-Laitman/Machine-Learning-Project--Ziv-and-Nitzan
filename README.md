# Machine Learning Project Overview

## Introduction
This project aims to classify whether a candidate will be hired for a job based on previous hiring data.
The project showcases various stages of a machine learning workflow, including data preprocessing, feature engineering, model training, and evaluation.

## Project Structure
- **`data/`**: Contains the training and test datasets, as well as additional files such as `countryContinent.csv` used for feature engineering.
- **`Finale_Project_Ziv_and_Nitzan.ipynb`**: The main Jupyter Notebook containing all code for data analysis, model training, and evaluation.
- **`results_Ziv_and_Nitzan.csv`**: The output file containing the predictions made by the final model.

## Key Features
- **Data Preprocessing**: Handling missing values, encoding categorical features, and scaling numerical data.
- **Feature Engineering**: Grouping countries into sub-continents to capture regional insights.
- **Model Training**: Training and fine-tuning various machine learning models to predict whether a candidate will be hired.
- **Evaluation**: Using appropriate metrics to evaluate the performance of the models and avoid overfitting.

## Methodologies
- **Target Encoding**: Applied to categorical features to capture the average effect of different categories.
- **Avoiding Overfitting**:
  - **Data Cleaning**: Outliers were identified and removed to ensure that the model trained on representative data.
  - **Validation Assessments**: Used validation datasets throughout the training process to ensure that the performance gap between the training error and validation error remained reasonable and under control.
  - **Grouping Countries**: Grouped countries into sub-continents to maintain the regional effect while reducing the risk of overfitting.
 
## Evaluation
The model's performance was assessed using the AUC (Area Under the Curve) metric to measure its ability to distinguish between classes. 
Validation datasets were used throughout the training process to monitor the performance and ensure that the gap between training and validation errors remained minimal, indicating a well-generalized model.

## Results
The final model's performance was evaluated using AUC. The predictions on the test set are stored in `results_Ziv_and_Nitzan.csv`, showing the probability of candidates being hired.

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/username/repository-name.git
   cd repository-name
