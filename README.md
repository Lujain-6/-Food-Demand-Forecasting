# Real-World Food Demand Forecasting System 🍲📈
### Machine Learning Project | AI3201T
**Department of Computer Science and Artificial Intelligence — Umm Al-Qura University**

---

## 📌 Project Overview
Accurately predicting daily food demand is a critical challenge for the food industry, directly influencing production decisions, inventory management, and food waste reduction. 

**Our Solution:** An intelligent, data-driven system designed to predict daily food demand using advanced Machine Learning. By analyzing a multi-dimensional feature space—including historical sales, weather conditions, local events, and social media trends—the system optimizes food business operations, minimizes financial losses, and supports sustainability by systematically redirecting predicted surplus food to charitable organizations.

---

## 👥 Authors & Project Context
* **Course:** Machine Learning (AI3201T)
* **Academic Term:** 1st Term 2025
* **Supervisor:** Dr. Afaf Almehmadi

### Team Members & Contributions:
* **Lujain Omar (Leader):** Model Architecture Design, Core Implementation, Evaluation, and Verification.
* **Maha Ahmed:** Introduction, Problem Definition, and Domain Research.
* **Wareef Saad:** Data Description, Feature Exploration, and Preprocessing.
* **Mirana Mohammad:** Methodology and Engineering Pipeline.
* **Hebah Almatrafi:** Literature Review, Comparative Modeling, and Documentation.

---

## 🚀 System Architecture & Methodology

The forecasting pipeline is engineered to process sequential, time-dependent historical and environmental data streams:

```text
[Multi-Source Data Input] ➡️ [Feature Engineering & Scaling] ➡️ [Sequential Encoding]
     ➡️ [LSTM Neural Network Layers] ➡️ [Demand Prediction Output] ➡️ [Surplus Redistribution Logic]
```

* **Multi-Source Ingestion:** Collects temporal sales metrics aligned with external dynamic variables (Weather patterns, public holidays, and social trends).
* **Feature Engineering:** Normalizes high-variance features and encodes categorical contextual vectors to stabilize model weight convergence.
* **Deep Learning Core (LSTM):** Utilizes Long Short-Term Memory (LSTM) recurrent neural networks to effectively capture long-term temporal dependencies, seasonal trends, and non-linear patterns within the time-series dataset.
* **Actionable Insights:** Outputs exact daily quantity forecasts, driving precise inventory stocking and enabling an automated pipeline for logistics coordination with food banks.

---

## 🛠️ Tech Stack & Core Libraries
* **Development Environment:** Python 3.x (Executed via Google Colab / Jupyter Notebooks).
* **Deep Learning Framework:** `TensorFlow` / `Keras` (For building and training LSTM layers).
* **Data Engineering Stack:** `pandas`, `numpy`, `scikit-learn` (For scaling, encoding, and dataset splitting).
* **Data Visualization:** `matplotlib`, `seaborn` (For training loss tracking and prediction vs. actual visualization curves).
