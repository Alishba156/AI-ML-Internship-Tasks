# AI-ML-Internship-Tasks
# AI/ML Internship Tasks

This repository contains all the completed tasks for the AI/ML Internship. Each task demonstrates data handling, machine learning, or prompt engineering principles.

---

## Task 1: Exploring and Visualizing a Simple Dataset
* **Objective:** Learn data loading, inspection, and visualization techniques.
* **Dataset Used:** Built-in Iris Dataset via Seaborn.
* **Key Findings:** 
  * Explored summary statistics and dataset shape using Pandas (`.info()`, `.describe()`).
  * Plotted Pairplots, Histograms, and Box plots using Matplotlib and Seaborn to identify data distributions and outliers.

## Task 2: Predict Future Stock Prices (Short-Term)
* **Objective:** Use historical stock data to forecast the next day's closing price.
* **Dataset Used:** Apple Inc. (`AAPL`) stock data fetched via `yfinance` API.
* **Models Applied:** Random Forest Regressor.
* **Key Results:** Successfully evaluated using RMSE and $R^2$ score, visualizing actual vs. predicted trend lines.

## Task 3: Heart Disease Prediction
* **Objective:** Build a classification pipeline to predict whether a patient is at risk of heart disease.
* **Dataset Used:** UCI Heart Disease Dataset.
* **Models Applied:** Decision Tree Classifier.
* **Key Results:** Achieved high accuracy, evaluated performance using Confusion Matrix and ROC-AUC curves, and extracted clinical feature importances (e.g., Chest Pain Type `cp`).

## Task 4: General Health Query Chatbot
* **Objective:** Build a safe, empathetic medical assistant chatbot using a Large Language Model.
* **API/Model Used:** Google Gemini API (`gemini-2.5-flash`) via the modern `google-genai` SDK.
* **Key Techniques:** Applied system prompt engineering to enforce safety guardrails, prohibit diagnosing/prescribing, and append medical disclaimers automatically.
