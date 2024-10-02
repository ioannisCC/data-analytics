# Data Analysis Project

## Overview

This repository provides code and documentation for a comprehensive data analysis project using a real-world dataset. The project involves data preprocessing, clustering, classification, and prediction techniques applied to the Bank Marketing Data Set.

### Dataset: Bank Marketing Data Set

	•	Description: Approximately 45,000 records with information about a Portuguese bank’s direct marketing campaigns (phone calls).

### Steps

1. ### Data Preprocessing

*Objective*: Prepare and clean the dataset for analysis.

	•	Initial Exploration: Load the dataset and familiarize yourself with its structure and content.
	•	Handling Missing Values: Identify and address any missing or erroneous values (e.g., filling gaps, removing outliers).
	•	Normalization and Encoding: Normalize and encode columns as needed.
	•	Statistical Analysis: Perform a simple statistical analysis, including histograms and box plots, to understand key features of the dataset.

2. ### Clustering

*Objective*: Discover hidden patterns and properties within the data.

	•	Feature Selection: Choose relevant features for clustering.
	•	Clustering Methods: Apply KMeans and DBSCAN using Scikit-Learn.
	•	Evaluation: Compare the clustering results and the impact of different parameters on clustering quality using scatter plots and clustering metrics.

3. ### Classification

*Objective*: Classify data into predefined categories.

	•	Data Transformation: Prepare the dataset in the form of <Feature(s)>, <Label(s)>.
	•	Initial Classifiers: Use Scikit-Learn to create and evaluate two classifiers (e.g., Bayesian, LS-SVM).
	•	Neural Networks: Build and train two neural networks using TensorFlow/Keras—one with standard training and one with transfer learning. Compare their performance with the initial classifiers using metrics like confusion matrix and ROC-AUC curve.

4. ### Summary

*Objective*: Summarize findings and present key insights.

	•	Observations: Record observations from the previous steps.
	•	Key Conclusions: Provide 2-3 key takeaways with appropriate visualizations to “tell a story” about the dataset.

## Usage

	•	Data Preprocessing: Run the preprocessing scripts to clean and prepare the data.
	•	Clustering: Execute the clustering scripts to apply and compare KMeans and DBSCAN.
	•	Classification: Train and evaluate classifiers and neural networks using the provided scripts.
	•	Summary: Analyze results and create visualizations to summarize the findings.
