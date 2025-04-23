# Diabetes Classification Model

This repository contains a machine learning project aimed at predicting whether a patient has diabetes based on certain diagnostic measurements. This project was developed as part of a university data science course and emphasizes data preprocessing and pipeline creation.

## Project Overview

The goal of the project is to build a high-performing machine learning model to classify diabetes presence. The project includes the following steps:

1. **Data Cleaning**:
   - Validating data types.
   - Removing duplicates and inconsistencies.
   - Handling extreme values.

2. **Data Preparation**:
   - Implementing a robust preprocessing pipeline to avoid data leakage.
   - Handling missing values using appropriate imputation strategies.
   - Scaling and encoding variables.

3. **Model Training and Evaluation**:
   - Building machine learning models and using pipelines for preprocessing and modeling.
   - Evaluating models using appropriate metrics.
   - Hyperparameter tuning to optimize the final model.

4. **Code Quality**:
   - Writing clean, organized, and well-documented code.

## Dataset

The dataset includes various features such as:
- **Pregnancies**
- **Glucose levels**
- **Blood Pressure**
- **Skin Thickness**
- **Insulin levels**
- **Diabetes Pedigree Function**
- **Weight Group**
- **Age Group**
- **Gender**
- **Outcome** (Target variable)

## Key Features of the Project

- **Preprocessing Pipeline**: The project implements a pipeline to preprocess data, handle missing values, and encode features.
- **Data Validation**: Checks for duplicates, missing values, and inconsistencies are performed.
- **Outlier Handling**: Extreme values are identified using Z-scores and handled appropriately.
- **Model Evaluation**: The model is validated using an 80-20 train-test split, and evaluation metrics are used to assess performance.
- **Hyperparameter Tuning**: The final model is optimized to achieve the best results.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Rasheed-Al-Qobbaj/Diabetes_classifier.git
   ```

2. Open and execute the Jupyter Notebook:
   ```bash
   jupyter notebook Report.ipynb
   ```

## Results

The final model and preprocessing pipeline are integrated into a single workflow to ensure reproducibility and robustness. The project demonstrates effective handling of data preprocessing challenges and model optimization.

## Author
**Rasheed Alqobbaj**  
