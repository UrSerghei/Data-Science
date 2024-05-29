# 🎥 Movie Budget vs. Revenue Linear Regression Project

## Overview

The Movie Budget vs. Revenue Linear Regression Project aims to analyze the relationship between movie budgets and their corresponding revenues. Using a dataset of movies, this project builds and evaluates a linear regression model to predict movie revenues based on their budgets.

## Contents

- `MovieBudgetRevenue.ipynb`: Jupyter Notebook containing the complete workflow of the project, including data preprocessing, exploratory data analysis (EDA), model training, evaluation, and predictions.
- `data/`: Directory containing the movie budget and revenue dataset.

## Installation

To run the notebook, you need to have Python installed along with the necessary libraries. You can set up the environment using the following steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/UrSerghei/movie-budget-revenue.git
   cd movie-budget-revenue
   ```

2. Create a virtual environment:
   ```sh
   python -m venv venv
   ```

3. Activate the virtual environment:

   - On Windows:
     ```sh
     venv\Scripts\activate
     ```
   - On macOS and Linux:
     ```sh
     source venv/bin/activate
     ```

4. Install the required libraries:
   ```sh
   pip install -r requirements.txt
   ```

## Usage

1. Open the Jupyter Notebook:
   ```sh
   jupyter notebook MovieBudgetRevenue.ipynb
   ```

2. Follow the steps in the notebook to understand the data preprocessing, EDA, model training, and evaluation processes.

3. Modify and run the code cells to explore different models and parameters.

## Project Workflow

1. **Data Preprocessing**: Load the dataset, handle missing values, and normalize/standardize numerical features as necessary.
2. **Exploratory Data Analysis (EDA)**: Analyze the dataset to understand the distribution of movie budgets and revenues, and visualize the relationship between them.
3. **Feature Engineering**: Create new features or transform existing ones to improve model performance.
4. **Model Training**: Train a linear regression model to predict movie revenues based on budgets.
5. **Model Evaluation**: Evaluate the model's performance using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared.
6. **Prediction**: Use the trained model to make revenue predictions for new movie budget data.

## Dependencies

- Python 3.8+
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- jupyter


## Acknowledgments

- The dataset used in this project is sourced from Kaggle.
- Thanks to the open-source community for providing the tools and libraries used in this project.

## Contact

For any questions or feedback, please contact Serghei Ursachii at serghei.ursachii01@gmail.com
