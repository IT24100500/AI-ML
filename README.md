# IT2011 Group Assignment – Data Preprocessing & EDA

## 📊 Project Overview
This repository presents a collaborative data preprocessing and modeling pipeline built around a health and lifestyle dataset. The dataset includes biometric, behavioral, and demographic attributes such as age, BMI, glucose levels, sleep hours, physical activity, and family history—aimed at predicting a health risk classification (target_encoded).
Each group member contributed a distinct preprocessing technique, including encoding, scaling, outlier removal, and feature selection. These techniques were individually documented in separate notebooks and then integrated into a unified pipeline (group_pipeline.ipynb) for model training and evaluation.
The final workflow includes:
- 🧼 Data Cleaning: Handling missing values and inconsistent entries
- 🔄 Encoding: Transforming categorical variables into numeric formats
- 📐 Scaling: Standardizing numeric features for model compatibility
- 📊 EDA: Visualizing distributions, correlations, and outliers
- 🧠 Model Training: Using classifiers like Random Forest and Logistic Regression
- 📈 Evaluation: Confusion matrices, classification reports, and accuracy scores
This project demonstrates a reproducible and modular approach to health data preprocessing, suitable for downstream machine learning tasks and real-world deployment.

Let me know if you want to add a section on member roles, dataset source, or instructions for running the pipeline—I can scaffold that next.

## 👥 Group Members
- IT24100500 – Missing Data Handling
- IT24100546 – Encoding Categorical Variables
- IT24100488 – Outlier Removal
- IT24100418 – Scaling
- IT24100390 – Feature Engineering
- IT24100419 – Dimensionality Reduction

## 📁 Folder Guide
- `data/`: Raw and external datasets
- `notebooks/`: Individual preprocessing notebooks
- `group_pipeline.ipynb`: Combined pipeline
- `results/`: Visualizations, logs, and final outputs

## 🚀 How to Run
1. Clone the repo
2. Open `group_pipeline.ipynb` in Jupyter
3. Run all cells to reproduce the final results

## 📅 Viva Details
- Mode: In-class
- Duration: ~15 minutes
- Format: Individual walkthrough + Q&A
