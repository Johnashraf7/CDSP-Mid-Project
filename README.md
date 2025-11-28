# Medical Insurance Data Analysis

A comprehensive exploratory data analysis (EDA) and machine learning project analyzing medical insurance data with interactive visualizations.

## Project Overview

This project analyzes medical insurance data to identify key patterns and relationships between patient demographics, health conditions, and medical costs. It includes:

- **EDA Analysis**: Comprehensive data exploration and feature engineering
- **ML Preprocessing**: Data cleaning and preparation for machine learning models
- **Interactive Dashboard**: Streamlit-based web application for data visualization

## Dataset Features

The dataset includes 50+ features covering:
- **Demographics**: Age, sex, region, income, education, marital status
- **Health Metrics**: BMI, blood pressure, cholesterol (LDL), HbA1c
- **Medical History**: Chronic conditions, medications, procedures
- **Insurance Info**: Plan type, deductible, copay, network tier, premium
- **Utilization**: Visits, hospitalizations, procedure counts
- **Target Variable**: Annual medical costs

## Files

- `EDA.ipynb` - Exploratory data analysis with visualizations
- `ML_preprocessing.ipynb` - Data cleaning and preprocessing pipeline
- `med_insurance_app.py` - Streamlit interactive dashboard
- `medical_insurance.csv` - Original dataset
- `medical_insurance_cleaned.csv` - Cleaned dataset
- `requirements.txt` - Python dependencies

## Installation & Usage

### Setup

```bash
pip install -r requirements.txt
```

### Run the Dashboard

```bash
streamlit run med_insurance_app.py
```

### View Analysis

Open `EDA.ipynb` and `ML_preprocessing.ipynb` in Jupyter Notebook or JupyterLab.

## Key Insights

- **Age Impact**: Senior patients have significantly higher average annual medical costs
- **Chronic Conditions**: Each additional chronic condition correlates with higher costs
- **Hospitalization**: Number of hospitalizations in last 3 years strongly predicts medical costs
- **BMI & Lifestyle**: Obesity category associated with elevated costs
- **Plan Type**: Network tier and plan type affect insurance premiums and cost distribution

## Technologies Used

- **Python 3.x**
- **Pandas**: Data manipulation and analysis
- **Plotly**: Interactive visualizations
- **Scikit-learn**: Data preprocessing and machine learning
- **Streamlit**: Web dashboard framework

## Author

John Iskros

## License

This project is open source and available under the MIT License.
