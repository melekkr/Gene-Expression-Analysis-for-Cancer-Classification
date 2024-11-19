# Gene-Expression-Analysis-for-Cancer-Classification

## Project Overview

This project aims to classify **invasive and non-invasive cancers** based on **gene expression data**. The goal is to predict whether a given cancer is invasive or non-invasive based on the gene expression profiles of tumor samples. Using **machine learning** techniques, we explore how gene expression can be used as a reliable predictor for cancer type classification.

### Objectives:
- **Predict cancer types**: Classify cancers as either invasive or non-invasive based on gene expression data.
- **Data preprocessing**: Clean and preprocess gene expression data to make it suitable for machine learning.
- **Feature selection**: Select the most important features (genes) that contribute to distinguishing invasive and non-invasive cancer types.
- **Model training**: Train machine learning models to classify the cancer types based on the gene expression data.
- **Model evaluation**: Evaluate the performance of various classification models.

## Data Set:

The dataset used in this project contains **gene expression data** from cancer samples that are categorized into **invasive** and **non-invasive** cancers.

### **Data Set Details:**
- **Number of Samples**: **X rows** (each representing a tumor sample)
- **Number of Features**: **Y columns** (representing the expression levels of different genes)
- **Description**: This dataset contains gene expression profiles, where each feature corresponds to the expression level of a gene. The target variable is the cancer type (invasive or non-invasive).
  
### **Features**:
- **Gene Expression Levels**: Each column represents the expression level of a specific gene.
- **Cancer Type Labels**: The target variable is the cancer type, labeled as **1 for invasive** and **0 for non-invasive**.

## Methods Used:

1. **Data Preprocessing**:
   - Handle **missing values** and **outliers** in the dataset.
   - Normalize the gene expression data to ensure consistency in the model training process.

2. **Machine Learning Models**:
   - The following machine learning algorithms were applied to predict cancer types:
     - **Logistic Regression**: A basic classification model to establish a baseline.
     - **Random Forest**: A more complex model that handles feature importance and non-linear relationships.
     - **Support Vector Machine (SVM)**: A powerful classification method for high-dimensional data like gene expression.
     - **K-Nearest Neighbors (KNN)**: A simple, intuitive algorithm for classification.

3. **Feature Selection**:
   - Methods such as **Principal Component Analysis (PCA)** and **LDA** were used to reduce dimensionality and select the most relevant genes for classification.

4. **Model Evaluation**:
   - **Accuracy**, **Precision**, **Recall**, and **F1-score** were used to evaluate the performance of each model.

## How to Use:

### Prerequisites:
Ensure that you have **Python** installed along with the required libraries. You can install the dependencies using the following:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Cancer-Type-Prediction.git
