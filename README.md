# 🌍 AI-Driven Natural Hazard Prediction

This project investigates the application of machine learning models for predicting natural hazards, focusing on major disasters in India such as floods and cyclones. It features a comparative performance analysis of **K-Nearest Neighbors (KNN)**, **Support Vector Machines (SVM)**, and **Decision Trees (DT)**.

## 📌 Overview

Natural hazard prediction is critical for disaster preparedness and mitigation. This project explores how classical machine learning techniques can be leveraged to build accurate and interpretable models for hazard prediction based on historical data.

## 🔍 Key Features

- 📊 Comparative model analysis (KNN, SVM, DT)
- 📁 Data preprocessing and feature engineering
- 📈 Performance metrics: Accuracy, Precision, Recall, F1-Score
- 📉 Visualization of model results
- 🧪 Built and tested in Google Colab

## 🧠 Methodology

1. **Data Collection**: Historical disaster data from Indian meteorological and disaster response sources.
2. **Data Preprocessing**: Handled missing values, normalization, and categorical encoding.
3. **Model Training**:
   - **KNN**: Distance-based classification
   - **SVM**: Margin-based optimization
   - **Decision Tree**: Rule-based splitting
4. **Evaluation**: Used stratified k-fold cross-validation to assess model generalizability.

## 📊 Results Summary

| Model         | Accuracy (%) | Precision (%) | Recall (%) | F1-Score (%) |
|---------------|--------------|----------------|-------------|---------------|
| KNN           | 79.47        | 74.15          | 79.47       | 75.88         |
| SVM           | 48.34        | 32.35          | 48.34       | 36.45         |
| Decision Tree | 87.41        | 80.50          | 87.41       | 83.66         |

## 🛠️ Tech Stack

- Python 3.x
- pandas, seaborn, matplotlib
- scikit-learn

## 📁 Repository Structure

```plaintext
.
├── Capstone.ipynb        # Main analysis notebook
├── README.md             # Project overview
└── requirements.txt      # Dependencies
```


## 📚 References

- [IMD - Indian Meteorological Department](https://mausam.imd.gov.in/)
- [NDMA - National Disaster Management Authority](https://ndma.gov.in/)
- Scikit-learn documentation

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repo, raise issues, or submit pull requests.

