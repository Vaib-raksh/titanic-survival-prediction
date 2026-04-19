# Titanic-survival-prediction


## Overview
Predicting survival of Titanic passengers using machine learning.
Built as part of my ML learning journey.

## Models Tried
| Model | Accuracy |
|---|---|
| Logistic Regression | 80.0% |
| Random Forest | 79.8% |
| Decision Tree (depth 5) | 80.4% |
| KNN unscaled | 73.2% |
| KNN scaled (k=7) | 80.4% |

## Final Model
KNN with feature scaling (k=7) — 80.4% accuracy

## What I Learned
- Feature scaling dramatically improves KNN performance
- Simpler models can outperform complex ones on small datasets
- Female passengers had 74% survival rate vs 19% for males

## Tech Stack
Python, Pandas, Scikit-learn, Matplotlib

## How to Run
Open the notebook in Google Colab and run the cell.
