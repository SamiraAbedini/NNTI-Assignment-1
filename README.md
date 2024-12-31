# NNTI Assignment 1

## Overview
This repository contains the implementation for **Assignment 1** of the Neural Networks and Theoretical Insights (NNTI) course. The assignment covers key concepts of data generation, visualization, and classification using Python libraries such as `NumPy`, `Matplotlib`, and `scikit-learn`.

## Assignment Details
**Released:** 23.10.2024  
**Deadline:** 30.10.2024 23:59  

### Topics Covered
1. **Data Generation**:
   - Creating linearly separable 2D clusters.
   - Generating an XOR dataset with logical XOR operation.

2. **Visualization**:
   - Visualizing clusters and XOR datasets.
   - Plotting decision boundaries for classification models.

3. **Classification**:
   - Using `sklearn.svm.LinearSVC` to classify datasets.
   - Exploring the impact of hyperparameters and noise on decision boundaries.

4. **Analysis**:
   - Observing decision boundary differences between linearly separable and XOR datasets.
   - Evaluating the influence of outliers on model performance.

## Files and Structure
- `assignment1_1_1.py`: Functions for generating 2D clusters and shuffling data.
- `assignment1_1_2.py`: Functions for creating an XOR dataset.
- `assignment1_1_3.py`: Functions to visualize datasets using scatter plots.
- `assignment1_2_1.py`: Implementation of a linear SVM model using `LinearSVC`.
- `assignment1_2_2.py`: Functions to plot decision boundaries for classification models.
- `assignment1_2_3.py`: Functions for hyperparameter tuning using `GridSearchCV` and `RandomizedSearchCV`.
- `main.py`: The main script that combines and executes the above functionalities.

## Dependencies
The following Python libraries are required:
- `NumPy`
- `Matplotlib`
- `scikit-learn`

You can install them using:
```bash
pip install numpy matplotlib scikit-learn
