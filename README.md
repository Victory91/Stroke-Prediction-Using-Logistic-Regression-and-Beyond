# Stroke-Prediction-Model

# Project Overview
Develop a model to predict stroke events using a diverse range of demographic, lifestyle, and clinical attributes, ensuring a holistic representation of potential disease determinants.

# Table of Contents
- Introduction
- Dataset
- Project Structure
- Results
- Contibuting
- License
- Acnowledgements

# Introduction
This project aims to create a predictive model for stroke occurrences by leveraging a comprehensive dataset encompassing various factors influencing health. Beginning with multiple linear regression, we progressed to more advanced models to improve prediction accuracy and address challenges like class imbalance.

# Dataset
The dataset includes:

- Numerical Features:

1. Age
2. Average Glucose Level (avg_glucose_level)
3. Body Mass Index (bmi)

- Categorical Features:

1. Gender
2. Hypertension
3. Heart Disease
4. Ever Married
5. Work Type
6. Residence Type
7. Smoking Status

- Target Variable:

Stroke (0: No Stroke, 1: Stroke)

# Results and Analysis:

Review the results and visualizations in the notebook

# Project Structure
```markdown
stroke-prediction-model/
├── data/
│   └── stroke_data.csv
├── notebooks/
│   ├── 1_data_preprocessing_and_eda.ipynb
│   ├── 2_multiple_linear_regression.ipynb
│   └── 3_logistic_regression_and_advancements.ipynb
├── results/
│   ├── figures/
│   └── model_performance_metrics.txt
├── src/
│   ├── data_preprocessing.py
│   ├── modeling.py
│   └── evaluation.py
├── requirements.txt
├── README.md
└── LICENSE
```

# Results

Baseline Model (Multiple Linear Regression):

MAE: Value

R²: Value

# Observations: [Brief summary]

# Enhanced Model (Logistic Regression):

ROC AUC Score: Value

Improved recall and precision for stroke prediction.

# Key Findings:

Age, average glucose level, and hypertension were significant predictors.

Lifestyle factors like smoking status also influenced stroke risk.

# Contributing

Contributions are welcome! Please follow these steps:

Fork the repository.

Create a new branch: git checkout -b feature/your_feature

Commit your changes: git commit -am 'Add your feature'

Push to the branch: git push origin feature/your_feature

Create a pull request.

# License

This project is licensed under the MIT License - see the LICENSE file for details.

# Acknowledgments

Thanks to AbdulQudus for support.

Appreciation to the data providers.
