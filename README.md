# Lung Cancer Prediction Using Decision Tree with GridSearchCV

This project demonstrates the use of a **Decision Tree Classifier** for predicting lung cancer based on age and smoking years. It also uses **GridSearchCV** to perform hyperparameter tuning and select the best set of parameters for the classifier.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Dependencies](#dependencies)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Running the Project](#running-the-project)
- [Results](#results)
- [Future Improvements](#future-improvements)

## Project Overview

This project uses a Decision Tree Classifier to predict whether a patient has lung cancer based on two features: `Age` and `Smoking_Years`. Hyperparameter tuning is performed using **GridSearchCV** to find the optimal parameters for the model.

## Dataset

The dataset contains the following columns:
- `Age`: The age of the person in years.
- `Smoking_Years`: The number of years the person has been smoking.
- `Lung_Cancer`: The target variable (0 for no lung cancer, 1 for lung cancer).

Example of the dataset:
| Age | Smoking_Years | Lung_Cancer |
|-----|---------------|-------------|
| 71  | 0             | 0           |
| 34  | 37            | 0           |
| 80  | 12            | 0           |
| 40  | 10            | 0           |

## Dependencies

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- mlxtend

You can install these dependencies using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn mlxtend
