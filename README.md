# University Rankings QDA Model

This project implements a Quadratic Discriminant Analysis (QDA) model for predicting university tiers based on various academic and institutional metrics.
========================
Proyek ini mengimplementasikan model Quadratic Discriminant Analysis (QDA) untuk memprediksi tingkat universitas berdasarkan berbagai metrik akademik dan institusional.


## Features Used
- Citations per Paper
- Papers per Faculty
- Academic Reputation
- Faculty Student Ratio
- Staff with PhD
- International Research Center
- International Students
- International Faculty
- Employer Reputation

## Installation
1. Clone the repository
2. Install requirements: `pip install -r requirements.txt`
3. Run the model: `python src/22_11_4678_zidandhiyaulhaq_uasbddm.py`

## Model Performance
- Average Cross-validation Score: [Your score]
- Detailed performance metrics available in the model output

## Usage
Use the `predict_university_tier()` function to make predictions for new universities.

## Files
- `22_11_4678_zidandhiyaulhaq_uasbddm.py`: Main model training script
- `university_qda_model.joblib`: Saved model
- `university_scaler.joblib`: Saved scaler
- `model_info.json`: Model metadata and configuration