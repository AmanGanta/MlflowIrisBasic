Project Overview
This repository demonstrates key concepts for building ML and DL projects using MLflow for experiment tracking, model management, and versioning.

ML Project Highlights
Experiment Tracking: Tracks all hyperparameters, metrics, and models during experimentation to ensure no information is lost, especially in large projects with multiple hyperparameters.
Model Registration: Demonstrates how to register models, why it's important, and how to access registered models using URIs in MLflow artifacts.
Model Versioning & Comparison: Stores multiple models with versioning, enabling easy comparison through the MLflow UI.
Key Feature: Utilizes GridSearch to find the best model based on predefined metrics (e.g., accuracy) and logs the final model.
DL Project Highlights
Nested Runs: Introduces nested runs to log multiple experiments under a single parent run for better organization.
Hyperparameter Optimization: Uses HyperOpt for experimenting with different parameters, logging every model created during the process.
Model Selection: Filters and logs the best model based on a chosen metric (e.g., accuracy or loss) instead of registering all models.
Key Difference: Unlike the ML project, every model in the process is logged, enabling comprehensive analysis of experiments.
Key Takeaways
MLflow Usage:
Local setup for tracking experiments.
Logging parameters, metrics, and models.
Model registration and versioning for efficient management.
Experiment Tracking:
Use of GridSearch for ML models.
Use of HyperOpt and nested runs for DL models.
Model Management:
Comparing models and selecting the best one via the MLflow UI.
Organizing experiments for scalability and reproducibility.