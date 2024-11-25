# Cali-House-Value-MLP
California Housing Price Prediction Using Neural Networks

This project implements a regression model using a Multi-Layer Perceptron (MLP) in PyTorch to predict California housing prices (median_house_value) based on various features such as median_income, longitude, and latitude.

Table of Contents

	•	Introduction
	•	Features
	•	Tech Stack
	•	Getting Started
	•	Steps in the Project
	•	Results
	•	Future Work
	•	License

Introduction

Housing prices in California vary based on features like income levels and geographic location. This project aims to predict housing prices using a regression model built with PyTorch. The dataset used is housing.csv, which contains features about areas in California.

Features

The dataset contains the following features:
	•	Median Income: Average income in the area.
	•	Longitude and Latitude: Geographic location.
	•	Additional features related to population and housing.

The target variable is:
	•	Median House Value: The median price of houses in the area.

Tech Stack

	•	Python
	•	PyTorch: For building and training the regression model.
	•	Pandas: For data manipulation and preprocessing.
	•	NumPy: For numerical computations.
	•	Matplotlib: For data visualization.
Steps in the Project

	1.	Data Loading and Exploration:
		Loaded and inspected the dataset.
		Checked for missing values and cleaned the data.
	2.	Data Preprocessing:
		Selected relevant features.
		Normalized features for better model performance.
	3.	Model Definition:
		Designed an MLP regressor using PyTorch.
	4.	Training:
		Trained the model using the Mean Squared Error (MSE) loss function.
		Optimized using the Adam optimizer.
	5.	Evaluation:
		Evaluated the model on test data using metrics like MSE.
	6.	Visualization:
		Visualized actual vs. predicted values to assess the model’s accuracy.

Results

	•	Training Loss: Observed during training to ensure convergence.
	•	Test Performance: Achieved an MSE of 0.013 on the test set.
	•	Visualizations: Predicted housing prices closely align with actual values.
