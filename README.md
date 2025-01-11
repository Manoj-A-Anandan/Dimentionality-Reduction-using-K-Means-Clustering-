
# **Dimensionality Reduction with K-Means and Classification**

This repository demonstrates the implementation of dimensionality reduction techniques using K-Means clustering, combined with supervised learning models for classification. The dataset used is the **Human Activity Recognition (HAR) dataset**, which contains sensor readings from smartphones. 

---

## **Overview**
Dimensionality reduction is crucial for handling datasets with high feature counts, especially when many features may be redundant or irrelevant. This project showcases how K-Means clustering can be used for feature selection, reducing computational overhead while preserving classification performance. A Gaussian Naive Bayes classifier is used to evaluate the reduced dataset.

---

## **Key Features**
- **Data Preprocessing**: 
  - Normalization and Standardization of features for better model performance.
  - Label encoding to convert categorical target variables into numerical values.
- **Exploratory Data Analysis (EDA)**:
  - Initial insights into the dataset, including summary statistics and checks for missing data.
- **Dimensionality Reduction**:
  - Utilizes K-Means clustering to group and select important features, minimizing redundancy.
- **Model Training and Evaluation**:
  - Implements Gaussian Naive Bayes for predicting human activities.
  - Compares the accuracy and runtime performance of the model with full features vs reduced features.
- **Pipeline Implementation**:
  - Scalable pipeline integrating preprocessing, dimensionality reduction, and model training.

---

## **Technologies Used**
- **Programming Language**: Python
- **Libraries**:
  - **Data Processing**: NumPy, Pandas, Scikit-learn
  - **Visualization**: Matplotlib
  - **Clustering and Classification**: K-Means, Gaussian Naive Bayes
- **Dataset**: Human Activity Recognition (HAR) dataset from the UCI Machine Learning Repository.

---

## **Results**
- **Dimensionality Reduction**: Selected a subset of features using K-Means clustering.
- **Model Performance**:
  - Achieved similar accuracy with reduced features as compared to the full feature set.
  - Reduced computational time with the optimized dataset.

| Feature Set        | Accuracy | Runtime (s) |
|--------------------|----------|-------------|
| Full Feature Set   | 95.2%    | 0.120       |
| Reduced Feature Set| 94.8%    | 0.085       |

---

## **Installation**
1. **Clone the repository**:
   ```bash
   git clone https://github.com/Manoj-A-Anandan/Dimensionality-Reduction.git
   cd Dimensionality-Reduction
