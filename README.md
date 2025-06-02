# Task-5-Decision-Trees-and-Random-Forests

Certainly! Here’s a clear and well-structured **README.md** file for your Decision Tree and Random Forest heart disease prediction project.

---

# Heart Disease Prediction with Decision Trees and Random Forests

This project demonstrates how to use tree-based machine learning models (Decision Tree and Random Forest) to predict heart disease from patient data. It covers model training, evaluation, visualization, feature importance analysis, and cross-validation using Python’s scikit-learn library.

---

## Table of Contents

- [Overview](#overview)
- [Requirements](#requirements)
- [Dataset](#dataset)
- [How to Run](#how-to-run)
- [Key Features](#key-features)
- [Project Structure](#project-structure)
- [Results](#results)
- [References](#references)

---

## Overview

This project:
- Loads and prepares a heart disease dataset
- Trains and evaluates Decision Tree and Random Forest classifiers
- Visualizes the decision tree
- Analyzes feature importances
- Uses cross-validation to assess model stability and prevent overfitting

---

## Requirements

- Python 3.7+
- pandas
- scikit-learn
- matplotlib


## Dataset

- **heart disease.csv**: Contains patient data and a `target` column indicating heart disease presence.
- Download a sample dataset from [Heart Disease Dataset]((https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset/data)) or use your own.

---

## How to Run

1. Place `heart.csv` in your working directory.
2. Run the Python script (e.g., `Task 5 Decision Trees and Random Forests.ipynb`).
3. Outputs will include:
   - Model accuracy scores
   - Classification reports
   - Decision tree visualization 
   - Feature importance plot

---

## Key Features

- **Decision Tree Training:**  
  Trains a tree with depth and leaf size controls to avoid overfitting.

- **Random Forest Training:**  
  Trains an ensemble of trees for improved accuracy and robustness.

- **Visualization:**  
  Plots the decision tree using Matplotlib.

- **Feature Importance:**  
  Shows which patient features are most predictive.

- **Cross-Validation:**  
  Evaluates model stability and helps select optimal tree depth.

---

## Results

- **Accuracy:**  
  Random Forests usually outperform single Decision Trees on test data.

- **Overfitting Control:**  
  Using `max_depth` and `min_samples_leaf` helps prevent overfitting.

- **Feature Insights:**  
  Feature importance plots reveal which health indicators matter most.

---

## References

- [GPT](https://chatgpt.com/c/683d39fc-04b8-8009-8e90-5a79b62fd921)
- [Perplexity]((https://www.perplexity.ai/search/what-is-decision-tree-PTjZKYhOTAqw6PShBXOGSw))


---

**Enjoy exploring tree-based machine learning for healthcare!**  
Feel free to fork, modify, and extend this project.
