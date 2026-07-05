# Ethical-AI-Analysis
# Income Prediction: ML Fairness & Explainability

A beginner-friendly machine learning project built in Google Colab. This project trains a model to predict whether an individual's income exceeds $50K/year using the UCI Adult dataset, while evaluating the model for demographic bias and explaining its predictions.

##  Assignment Overview
The goal of this assignment is to look beyond basic model accuracy. We explore:
1. **Model Training:** Implemented a simple Logistic Regression model using `scikit-learn`.
2. **Fairness Audit:** Used `Fairlearn` to analyze systemic bias across gender groups.
3. **Model Explainability:** Used `SHAP` and `LIME` to understand both global feature importance and individual (local) predictions.

---

##  Tech Stack & Libraries
* **Language:** Python 3
* **Platform:** Google Colab / Jupyter Notebooks
* **Machine Learning:** `scikit-learn`
* **Fairness:** `fairlearn`
* **Explainability:** `shap`, `lime`
* **Data & Plots:** `pandas`, `numpy`, `matplotlib`

---

##  Setup and Installation

Since this project is designed for **Google Colab**, no local installation is required. Follow these steps to run the code:

1. Open [Google Colab](https://colab.research.research.google.com/).
2. Upload the `.ipynb` notebook file from this repository.
3. Run the very first cell to install the required external libraries:
   ```bash
   !pip install fairlearn shap lime
