# heart_attack_prediction

# Heart Attack Prediction

This repository contains a comprehensive workflow for predicting heart attack risk using patient health data. The project demonstrates data exploration, preprocessing, outlier handling, statistical analysis, model building, and evaluation—all within a Jupyter Notebook.

---

## Table of Contents

- [Dataset Overview](#dataset-overview)
- [Project Workflow](#project-workflow)
- [Key Features](#key-features)
- [How to Run](#how-to-run)
- [Results](#results)
- [Visualization & Dashboard](#visualization--dashboard)
- [Requirements](#requirements)
- [Acknowledgements](#acknowledgements)

---

## Dataset Overview

The dataset includes 1,319 patient records with the following features:

- **Age**
- **Gender** (0 = Female, 1 = Male)
- **Heart rate**
- **Systolic blood pressure**
- **Diastolic blood pressure**
- **Blood sugar**
- **CK-MB** (Creatine Kinase-MB)
- **Troponin**
- **Result** (positive = heart attack, negative = no heart attack)

---

## Project Workflow

1. **Data Exploration**
   - Displayed data samples and summary statistics (mean, std, min, max, quartiles) for all features.
2. **Data Cleaning**
   - Checked for missing values and outliers.
   - Outlier handling strategies applied to clinical variables.
3. **Statistical Analysis**
   - Used t-tests to identify significant differences in features between positive and negative cases.
4. **Model Building**
   - Trained a logistic regression model to predict heart attack risk.
   - Achieved an accuracy of 89%.
5. **Model Evaluation**
   - Evaluated with accuracy, confusion matrix, classification report, and ROC-AUC score.
6. **Feature Importance**
   - Analyzed model coefficients to interpret feature impact.
7. **Visualization**
   - Created boxplots, scatter plots, and bar charts to visualize distributions and relationships.
   - Provided dashboard design guidance for Tableau.

---

## Key Features

- End-to-end machine learning pipeline for clinical prediction.
- Outlier detection and treatment tailored to healthcare data.
- Statistical testing for feature selection.
- Model interpretability through feature importance.
- Visual analytics for data-driven insights.

---

## How to Run

1. Clone this repository.
2. Install dependencies:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```
3. Open `prediction.ipynb` in Jupyter Notebook or JupyterLab.
4. Run all cells to reproduce the workflow and results.

---

## Results

- **Model:** Logistic Regression
- **Accuracy:** 89%
- **Key Predictors:** Age, heart rate, blood pressure, CK-MB, troponin, blood sugar
- **Insights:** Significant differences found in several features between heart attack and non-heart attack groups.

---

## Visualization & Dashboard

- The notebook includes code to generate key plots (boxplots, scatter plots, bar charts).
- Guidance is provided for building an interactive Tableau dashboard to further explore and present the results.

---

## Requirements

- Python 3.7+
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

---

**For questions or contributions, please open an issue or submit a pull request.**

[1] https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/31925554/c74ac98d-00e7-4846-8c5e-3f20521cd576/prediction.ipynb
