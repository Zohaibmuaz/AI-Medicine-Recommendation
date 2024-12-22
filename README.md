# AI Medicine Recommendation System

A web application for recommending medicines based on symptoms, using machine learning.

---

## Project Description

This project predicts medicines based on user-provided symptoms. It leverages a Support Vector Classifier (SVC) model trained on a dataset of symptoms and their associated severities. The web interface provides a user-friendly experience for inputting symptoms and viewing recommendations.

---

## Features

- **Symptom Input:** Users can enter symptoms to get recommendations.
- **ML Integration:** SVC model for predicting outcomes.
- **Comprehensive Datasets:** Includes descriptions, diets, medications, precautions, and training data.
- **Interactive Frontend:** Built with HTML templates for a responsive design.

---

## Directory Structure

```plaintext
datasets/
    Contains all CSV files related to symptoms, medications, and other training data.

models/
    Contains the trained model file (SVC).

templates/
    HTML files for the web interface.

1.py
    Python script for utility or model processing.

main.py
    The main Python script for running the application.

Medicine_Recommendation.ipynb, Medicine_recommendation_final.ipynb
    Jupyter notebooks for model training and analysis.

README.md
    Documentation for the project.

img.png
    A project-related image or logo.
