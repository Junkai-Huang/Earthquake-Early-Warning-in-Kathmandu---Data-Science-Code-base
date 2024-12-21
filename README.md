# Early Earthquake Warning System — Nepal

This repository contains code and analysis for developing an early earthquake warning system tailored to Nepal. The project utilizes machine learning models, including Gaussian Processes and Convolutional Neural Networks, to analyze seismic data and predict earthquake events.

## Repository Structure

- **src/**
  - `CNN.ipynb`: Implementation of a Convolutional Neural Network for seismic data classification and prediction.
  - `Deep Gaussian Process – GPyTorch.ipynb`: Notebook demonstrating the application of deep Gaussian processes using GPyTorch.
  - `Deep Gaussian Process – Iterative Feature Elimination.ipynb`: Analysis and iterative feature selection process using deep Gaussian processes.
  - `Deep Gaussian Process EDA.ipynb`: Exploratory Data Analysis for understanding the dataset and its features before applying Gaussian processes.
  - `Single Layer Gaussian Process (using GPy).ipynb`: Implementation of a single-layer Gaussian process model using GPy library.
- **README.md**: Documentation for the repository.

## Project Overview

The aim of this project is to develop a robust and efficient system for early earthquake warnings in Nepal, leveraging machine learning techniques to analyze seismic signals. The primary goals include:

- **Prediction**: Utilize machine learning models to predict seismic activity.
- **Feature Selection**: Identify key features that influence earthquake prediction using iterative methods.
- **Exploration**: Perform detailed exploratory data analysis to understand the characteristics of seismic data.

## Key Models and Methods

1. **Convolutional Neural Networks (CNN)**:
   - Used for seismic signal classification.
   - Focuses on identifying patterns in time-series data.

2. **Deep Gaussian Processes**:
   - Provides uncertainty estimates for predictions.
   - Implements advanced models with GPyTorch and GPy.

3. **Feature Elimination**:
   - Iterative process to refine the dataset for optimal model performance.

## Dependencies

To run the notebooks, ensure the following Python libraries are installed:
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `GPy`
- `GPyTorch`
- `torch`

Install them using:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn GPy GPyTorch torch
