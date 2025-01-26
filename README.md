# Titanic Survival Prediction

This repository contains the code and dataset used for the Titanic survival prediction challenge hosted on Kaggle. The goal of this project is to predict whether a passenger survived the Titanic shipwreck based on features like age, sex, ticket class, and family size.

## Project Overview

The Titanic dataset includes demographics and passenger information from 891 of the 2,224 passengers and crew on board the Titanic. You can view the dataset and competition details on the [Kaggle competition page](https://www.kaggle.com/c/titanic).

### Objectives

- Perform exploratory data analysis (EDA) to understand the data.
- Engineer relevant features to improve predictive models.
- Train a machine learning model to predict survival based on given features.
- Evaluate the model using appropriate metrics.
- Improve predictions through various algorithms and tuning techniques.

## Repository Structure
.
├── data <br>
│   ├── train.csv                    # Training data containing features and target <br>
│   ├── test.csv                     # Test data <br>
│   └── gender_submission.csv        # Example of a submission file in the correct format <br>
├── notebooks <br>
│   ├── EDA.ipynb                    # Notebook for exploratory data analysis <br>
│   ├── Feature_Engineering.ipynb    # Notebook for feature engineering <br>
│   └── Modeling.ipynb               # Notebook for training and evaluating models <br>
├── src <br>
│   ├── data_preprocessing.py        # Script for data cleaning and preprocessing <br>
│   └── train_model.py               # Script for training the machine learning model <br>
├── README.md <br>
└── requirements.txt                 # The required libraries for the project <br>

## Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/titanic-survival.git
   cd titanic-survival

2. **Install Dependencies** <br>
    Make sure you have Python installed on your system. It's recommended to use a virtual environment:
   ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    pip install -r requirements.txt

3. **Run the Notebooks** <br>
   Navigate to the notebooks directory and open the Jupyter notebooks:
   ```bash
   cd notebooks
   jupyter notebook

  This will start the Jupyter Notebook server and open a tab in your default web browser where you can open and run the notebooks.

  ## Usage 
  You can start by running the 'EDA.ipynb' to explore the dataset, followed by 'Feature_Engineering.ipynb' and 'Modeling.ipynb' for building and evaluating the prediction model.
  
  ## Licence 
  This project is open-sourced under the MIT License. See the LICENSE file for more details.

