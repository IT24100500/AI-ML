# IT2011 Group Assignment – Data Preprocessing & EDA

## 📊 Project Overview
This repository presents a collaborative data preprocessing and modeling pipeline built around a health and lifestyle dataset. The dataset includes biometric, behavioral, and demographic attributes such as age, BMI, glucose levels, sleep hours, physical activity, and family history—aimed at predicting a health risk classification (target_encoded).
Each group member contributed a distinct preprocessing technique, including encoding, scaling, outlier removal, and feature selection. These techniques were individually documented in separate notebooks and then integrated into a unified pipeline (group_pipeline.ipynb) for model training and evaluation.
The final workflow includes:
- Absolutely, Chamodith! Here's the revised version of your project workflow, aligned with the group member responsibilities:
### 🧩 Project Workflow 

- 🧼 **Missing Data Handling** – Managed by IT24100500  
  Addressing null values, imputing missing entries, and ensuring data consistency

- 🔄 **Categorical Encoding** – Managed by IT24100546  
  Converting categorical variables into numerical formats using label encoding, one-hot encoding, or target encoding

- 📦 **Outlier Removal** – Managed by IT24100488  
  Detecting and removing outliers using IQR, Z-score, and visual techniques like box plots

- 📐 **Feature Scaling** – Managed by IT24100418  
  Standardizing numeric features using techniques like StandardScaler or MinMaxScaler for model compatibility

- 🧠 **Feature Engineering** – Managed by IT24100390  
  Creating new features, transforming existing ones, and improving model signal through domain knowledge

- 🧮 **Dimensionality Reduction** – Managed by IT24100419  
  Reducing feature space using PCA or other techniques to improve performance and reduce noise

- 📊 **EDA & Visualization** – Collaborative  
  Exploring distributions, correlations, and trends using histograms, box plots, heatmaps, and pair plots

Let me know if you'd like this formatted for a report, presentation, or GitHub README. I can also help scaffold each member’s code module for clean integration.

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
