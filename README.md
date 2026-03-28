# Machine Learning Predictive Modeling on Artificial Data

## Overview
This repository contains an end-to-end machine learning project focused on building and optimizing predictive models using an artificial dataset. The project covers the entire data science lifecycle: from exploratory data analysis (EDA) and data preprocessing to model training, evaluation, and final reporting. 

## Repository Structure
The project files are organized as follows:

* **`code.ipynb`**: The main Jupyter Notebook containing all the Python code. This includes data exploration, feature engineering, model training, hyperparameter tuning, and evaluation.
* **`report.pdf`**: A comprehensive final report documenting the methodology, experiments conducted, model performance metrics, and final conclusions.
* **`project_requirements.pdf`**: The official project assignment, detailing the technical requirements and constraints.

### Datasets
* **`artifical_train_data.csv`**: The feature set used for training the machine learning models.
* **`artifical_train_labels.csv`**: The corresponding target variables (labels) for the training dataset.
* **`artifical_test_data.csv`**: The unseen test dataset used to evaluate the final model's generalization capabilities.

## Methodology
The pipeline implemented in this project follows standard industry practices for Machine Learning:
1.  **Exploratory Data Analysis (EDA):** Analyzing statistical distributions, identifying patterns, and understanding feature correlations.
2.  **Data Preprocessing:** Cleaning the data, handling potential outliers, scaling/normalizing features, and preparing the dataset for algorithms.
3.  **Model Selection & Training:** Implementing and fine-tuning various base machine learning algorithms (e.g., Decision Trees, Random Forests, Gradient Boosting), and combining them using advanced ensemble techniques — specifically Voting and Stacking classifiers—to maximize overall predictive accuracy and model robustness.
4.  **Evaluation & Optimization:** Assessing model performance using Balanced Accuracy metric and cross-validation techniques to prevent overfitting.

## Key Results
* **Final Model Performance:** After gaining access to the true test labels (`y_test`), the final ensemble model was evaluated on the unseen test set and achieved Balanced Accuracy score of 0.886.
* Detailed findings, visualizations, and the full rationale behind the model selection and hyperparameter tuning are thoroughly documented in the `report.pdf` file.


