# 🩺 Cancer Classification Project

## Table of Contents

1. [Project Overview](#project-overview)
2. [Data](#data)
3. [Methodology](#methodology)
4. [Results](#results)
5. [Conclusion](#conclusion)
6. [Future Work](#future-work)
7. [Usage](#usage)
8. [Contact](#contact)

## Project Overview

**Description:**
This project involves classifying cancer types using logistic regression. The goal is to accurately predict the presence of cancer based on various medical parameters. This classification task can help in early detection and treatment planning.

**Technologies Used:** Python, Pandas, Scikit-learn, Matplotlib, Seaborn

## Data

**Dataset:**
The dataset used in this project is obtained from UCI ML Breast Cancer Wisconsin (Diagnostic). It contains medical parameters that are used to predict whether a patient has cancer.

**Features:**

- radius (mean of distances from center to points on the perimeter)
- texture (standard deviation of gray-scale values)
- perimeter
- area
- smoothness (local variation in radius lengths)
- compactness (perimeter^2 / area - 1.0)
- concavity (severity of concave portions of the contour)
- concave points (number of concave portions of the contour)
- symmetry
- fractal dimension ("coastline approximation" - 1)

**Target:**
- 0: No Cancer
- 1: Cancer

## Methodology

1. **Data Preprocessing:**
   - Handling missing values
   - Feature scaling
   - Train-test split

2. **Exploratory Data Analysis (EDA):**
   - Visualizing the distribution of features
   - Correlation analysis

3. **Model Building:**
   - Logistic Regression
   - Model training and evaluation

4. **Model Evaluation:**
   - Accuracy
   - Precision, Recall, F1-Score
   - ROC-AUC Curve

## Results

- **Accuracy:** 96%

The logistic regression model shows high accuracy and good precision-recall balance, indicating that it is effective in classifying cancer presence based on the provided features.

## Conclusion

The logistic regression model developed in this project is able to accurately classify cancer presence, which could assist in early diagnosis and treatment planning. Further improvements can be made by exploring other classification algorithms and feature engineering techniques.

## Future Work

- **Explore Other Algorithms:** Test other classification algorithms like Random Forest, SVM, and Neural Networks.
- **Feature Engineering:** Create and test new features to improve model performance.
- **Hyperparameter Tuning:** Perform hyperparameter tuning to optimize model performance.

## Usage

To use this project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/cancer-classification.git
   cd cancer-classification

2. Run the Jupyter Notebook:
    jupyter notebook CancerClassification.ipynb

## Contact Me

- **LinkedIn:** [My LinkedIn Profile](https://www.linkedin.com/in/serghei-ursachii-254b39153/)
- **Email:** [serghei.ursachii01@gmail.com](mailto:serghei.ursachii01@gmail.com)
