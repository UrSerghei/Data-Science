# Titanic Exploratory Data Analysis (EDA) Project

Welcome to the Titanic Exploratory Data Analysis (EDA) project repository! This project aims to conduct an in-depth analysis of the Titanic dataset, exploring various aspects of the passengers onboard and their survival outcomes. Through exploratory data analysis techniques, we seek to gain insights into the factors that influenced survival rates and uncover interesting patterns within the data.


## Introduction

The sinking of the RMS Titanic in 1912 remains one of the most infamous maritime disasters in history. This project utilizes the Titanic dataset, which contains information about passengers aboard the Titanic, including demographics, ticket class, cabin, fare, and survival status. By analyzing this dataset, we aim to understand the characteristics of passengers who were more likely to survive and uncover any underlying patterns or correlations.

## Dataset

The dataset used in this project is commonly referred to as the "Titanic dataset" and is widely available for educational and analytical purposes. It contains the following features:

- PassengerId: Unique identifier for each passenger
- Survived: Whether the passenger survived (0 = No, 1 = Yes)
- Pclass: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- Name: Passenger's name
- Sex: Passenger's sex
- Age: Passenger's age
- SibSp: Number of siblings/spouses aboard
- Parch: Number of parents/children aboard
- Ticket: Ticket number
- Fare: Fare paid for the ticket
- Cabin: Cabin number
- Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## Installation

To run this project, you need to have Python installed along with several data science libraries. You can install the required libraries using the following command:

```bash
pip install -r requirements.txt
```

## Usage

Once you have the necessary libraries installed, you can start exploring the dataset and running the analysis scripts. The main script for analysis is `titanic_eda.py`, which can be run as follows:

```bash
python titanic_eda.py
```

This script performs various analyses and generates visualizations that help in understanding the factors influencing survival rates among Titanic passengers.

## Project Structure


- `notebooks/`: Jupyter notebook for interactive data exploration and analysis.
- `README.md`: The readme file you are currently reading.


## Analysis

The analysis covers various aspects of the Titanic dataset, including:

- Demographic analysis: Distribution of passengers by age, sex, and ticket class.
- Survival analysis: Factors influencing survival rates, such as ticket class, age, and sex.
- Family analysis: Impact of having family members aboard on survival chances.
- Fare analysis: Relationship between fare paid and survival rates.
- Port of embarkation analysis: Survival rates based on the port of embarkation.

The results of the analysis are presented through various visualizations, which can be found in the `images/visualizations` directory.

---

Thank you for visiting the Titanic Exploratory Data Analysis (EDA) project repository! We hope you find this project informative and insightful. If you have any questions or feedback, please don't hesitate to reach out.
