# Intel-Workshop-Small-projects
Things we have learnt during intel workshop
# Intel Workshop: Data Science and Machine Learning

This repository contains four Jupyter notebooks covering foundational data analysis and machine-learning workflows using NumPy, pandas, Matplotlib, and scikit-learn.

## Learning Objectives

- Use Python libraries to inspect, clean, and prepare tabular data.
- Explore data with summary statistics, histograms, and visualizations.
- Handle missing values, duplicates, categorical variables, and feature scaling.
- Split data into training and test sets and evaluate model performance.
- Apply supervised learning to regression and classification problems.
- Apply unsupervised learning to discover clusters in data.

## Notebook Overview

### Day 1 — Python and Data Analysis Foundations
Introduces NumPy arrays and basic numerical operations, including sums, averages, medians, standard deviations, and matrix operations. The notebook then uses pandas to load and inspect a CSV dataset, review its structure and summary statistics, identify missing values, and demonstrate basic missing-data handling.

### Day 2 — Insurance Cost Prediction
Builds a regression workflow using insurance data. Topics include exploratory data analysis, duplicate and missing-value handling, one-hot encoding of categorical features, train/test splitting, and standardizing numerical features. A Lasso regression model is trained and evaluated using MAE, MSE, RMSE, and R². The notebook also demonstrates preparing a new customer record for prediction and saving the trained model with `joblib`.

### Day 3 — Diabetes Classification
Explores a diabetes dataset and introduces a Decision Tree classifier. The notebook demonstrates class distribution analysis, stratified train/test splitting, class weighting, and model evaluation with accuracy, a confusion matrix, and a classification report. It also visualizes the trained decision tree.

### Day 4 — Iris Clustering
Applies unsupervised learning to the Iris dataset. The notebook standardizes flower measurements, uses the elbow method to explore possible cluster counts, and applies K-Means clustering. Clusters are visualized and assessed with a silhouette score. A new flower is also scaled and assigned to a cluster.

## Tools and Libraries

- Python
- NumPy
- pandas
- Matplotlib
- scikit-learn
- joblib

## Data Requirements

The notebooks expect CSV datasets that are not included in this repository. Update the file paths in the notebooks to match where you store the datasets. Some notebooks use environment-specific paths, such as `/content/...` or `/train.csv`.

> In the Day 3 notebook, provide a complete sample patient row before running the prediction cell; an empty row cannot be used to generate a valid prediction.

## Running the Notebooks

Open the `.ipynb` files in Jupyter Notebook, JupyterLab, or Visual Studio Code. Install the required Python libraries and make sure each notebook's expected dataset is available at the path specified in its code.
