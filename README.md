🔬 AI-Powered Disease Prediction System 🚀

📌 Overview
This project is an AI-driven disease prediction system that analyzes user-reported symptoms and predicts possible diseases using machine learning models. The system intelligently processes symptoms, handles typos, maps synonyms, and provides explainable AI insights for better interpretability.

🎯 Features
✅ Multi-Model Prediction: Uses Random Forest and XGBoost for robust classification
✅ Real-Time Symptom Processing: Handles spelling errors, synonyms, and fuzzy matching
✅ Severity-Based Analysis: Weighs symptoms by severity for accurate predictions
✅ Explainability (XAI): Implements SHAP & LIME to explain model decisions
✅ Flask API Integration: Provides a REST API for real-time prediction
✅ Future-Proof Design: Ready for UI & cloud deployment

🏗️ Tech Stack
Python 🐍
Machine Learning: Random Forest, XGBoost
Data Processing: Pandas, NumPy, TextBlob, RapidFuzz
Model Optimization: Optuna, GridSearchCV, RandomizedSearchCV
Explainability: SHAP, LIME
Backend: Flask (REST API)

📊 How It Works
1️⃣ User Inputs Symptoms (e.g., "Fever, Headache, Fatigue")
2️⃣ System Preprocesses Data:
    Corrects spelling mistakes
    Maps synonyms (e.g., "cold" → "common cold")
    Uses fuzzy matching for close symptom matches
3️⃣ Machine Learning Models Predict the Disease
4️⃣ Explainability Tools (SHAP & LIME) Show How the Model Reached the Prediction
5️⃣ The Flask API Returns the Predicted Disease
