#  AI-Powered Fake News Detection with Explainability

##  Overview

This project is an AI-based system that detects whether a news article is real or fake using machine learning techniques. It enhances trust and transparency by incorporating **Explainable AI (XAI)** tools such as **LIME** and **SHAP** to explain why a particular news item is classified as fake or real.

The goal is to build a model that is not only accurate but also interpretable — especially useful in sensitive domains where understanding decisions is just as important as making them.

---

##  Objectives

- Classify news articles as real or fake using machine learning.
- Provide visual and human-readable explanations for model predictions.
- Promote responsible AI by making model decisions interpretable.

---

##  Model & Dataset

- **Model Used**: Support Vector Machine (SVM)
- **Text Preprocessing**: TF-IDF Vectorization
- **Dataset**: Real vs Fake News articles (e.g., Kaggle dataset)
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-Score

---

## Explainability

- **LIME (Local Interpretable Model-Agnostic Explanations)**  
  Explains which words in a given news article influenced the model's prediction the most.

- **SHAP (SHapley Additive exPlanations)**  
  Provides a global and local understanding of feature contributions using Shapley values.

These visualizations help understand what features the model relies on and build user trust in its predictions.

---

##  Tech Stack

- **Language**: Python
- **Libraries**:  
  - `scikit-learn` – ML modeling  
  - `pandas`, `numpy` – data handling  
  - `LIME`, `SHAP` – explainability  
  - `matplotlib`, `seaborn` – visualization  
- **Development Environment**: Visual Studio Code / Jupyter Notebook

---
