# Crop Recommendation System

## Overview
This project is an AI-powered crop recommendation system that predicts the most suitable crop based on agricultural and environmental conditions such as soil nutrients, temperature, humidity, pH level, and rainfall.

## Features
- Machine learning crop prediction
- Data preprocessing and scaling
- Model training via Jupyter Notebook
- Streamlit web interface for user interaction
- Real-time crop recommendation
- Trained model deployment

## Project Structure
- `data/` - Agricultural dataset
- `notebook/` - Model training notebook
- `models/` - Trained machine learning models and preprocessing files
- `app/` - Streamlit deployment application

## Technologies Used
- Python
- Pandas
- Scikit-learn
- Streamlit
- Jupyter Notebook
- Pickle

## How to Run
```bash
pip install -r requirements.txt
streamlit run app/streamlit_croprecommendation.py
