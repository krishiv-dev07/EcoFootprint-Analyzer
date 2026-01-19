# EcoFootprint-Analyzer
Machine Learning and GenAI based Carbon Footprint Estimation System

# 🌍 EcoFootprint Analyzer

A Machine Learning and Generative AI–based system for estimating and explaining individual carbon footprints based on lifestyle choices.

## 🚀 Features
- Random Forest regression model for carbon footprint prediction
- Classification into Low / Moderate / High impact
- Streamlit web interface
- Generative AI used for explanation and sustainability suggestions (with fallback support)
- Trained on a dataset with 65 lifestyle-related features

## 🗂 Project Structure
EcoFootprint-Analyzer/
├── app.py
├── rf_model.pkl
├── X_columns.pkl
├── target_series.pkl
├── EcoFootprint_Analyzer_Training.ipynb


## 🧠 How It Works
1. User enters lifestyle details in the Streamlit UI.
2. The ML model predicts a numeric carbon footprint score.
3. The system classifies it into Low / Moderate / High.
4. A GenAI module explains the result in natural language.

## ▶ How to Run

```bash
pip install -r requirements.txt
streamlit run app.py

