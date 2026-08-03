# GPA Predictor — Existential Factors vs. Academic Performance

Analyzes a dataset of 2,392 high school students to identify which factors most strongly predict GPA, using and comparing several regression models.

## Overview

- **Dataset:** [Students Performance Dataset](https://www.kaggle.com/datasets/rabieelkharoua/students-performance-dataset/data) (Rabie El Kharoua, CC BY 4.0) — 2,392 students, covering demographics, study habits, parental involvement, extracurriculars, and GPA.
- **Approach:** Explored correlations between candidate factors and GPA, narrowed to the five most predictive (study time, parental support, absences, tutoring, parental education), then trained and compared Linear, Ridge, and Lasso regression, Random Forest, Decision Tree, and SVR models.
- **Result:** Ridge Regression performed best (R² ≈ 0.93), showing that these five factors together explain the large majority of variance in student GPA. Absences had the strongest negative correlation; extracurriculars, sports, volunteering, and gender showed no meaningful relationship.

## Files

- `GPA_Predictor.ipynb` — cleaned analysis notebook: data exploration, feature selection, model training and comparison
- `FINAL_Research_Paper.pdf` — full write-up with methodology, related work, results, and discussion

## Running it

1. Download `Student_performance_data _.csv` from the [Kaggle dataset link](https://www.kaggle.com/datasets/rabieelkharoua/students-performance-dataset/data) and place it in this directory.
2. `pip install pandas numpy scikit-learn seaborn matplotlib`
3. Run `GPA_Predictor.ipynb`.

## Background

This project was completed during an ML apprenticeship at Inspirit AI, in collaboration with a Stanford mentor.
