## Flight Delay Predictor (15+ Minutes)

### The objective is to demonstrate the complete lifecycle of a practical machine learning solution.

This project implements an end-to-end machine learning workflow to predict whether a commercial flight will be delayed by more than 15 minutes (binary classification).

The objective is to demonstrate the complete lifecycle of a practical machine learning solution -  from raw data exploration to model deployment, with a focus on reproducibility and interpretability.

The application allows an end user to specify flight characteristics and receive a prediction indicating whether the flight is likely to be delayed.

## Project Overview

The project covers the full machine learning pipeline:

- Data exploration and preprocessing
- Feature engineering and selection
- Model training and evaluation
- Model interpretability using SHAP
- Model packaging and deployment

The final model is deployed in a lightweight Streamlit application that loads the trained model and preprocessing pipeline to generate predictions.

## Repository Structure
app/
Streamlit interface
Trained model
Preprocessing pipeline

notebooks/
Data exploration
Feature engineering
Model selection
Model evaluation
Model interpretability

requirements.txt
Project dependencies

## Machine Learning Approach

Multiple classification algorithms were evaluated to identify the best-performing model.
The selected model is a **Gradient Boosting classifier**, chosen based on evaluation metrics and robustness.
Model interpretability was analyzed using **SHAP (Shapley Additive Explanations)** to understand the main drivers of flight delays.

## Dataset

The original dataset used for training is not included in this repository.
The notebooks document the full workflow and can be reused with similar public flight delay datasets.

## Key Features

- End-to-end ML workflow
- Reproducible training process
- Model interpretability with SHAP
- Packaged preprocessing pipeline
- Deployable prediction interface

## Limitations

- The project uses historical flight data and does not incorporate real-time information such as weather or operational disruptions.
- The application is designed as a demonstration of the ML workflow and is not intended as a production system.

## Motivation

This project was developed as part of my transition into Data & AI, with the goal of building practical end-to-end solutions that combine data preparation, machine learning, and deployment.