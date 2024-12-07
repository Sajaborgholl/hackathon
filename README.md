# Stress Level Prediction Using Machine Learning

## Overview
This project focuses on predicting stress levels based on lifestyle factors using machine learning. We utilized a dataset containing various lifestyle-related features, such as exercise frequency, smoking habits, social media usage, and more. By analyzing these factors, we aim to build a robust model capable of predicting stress levels effectively.

## Team Members
- **Saja Borghol**
- **Mohammad Ghorayeb**

## Objective
The primary goal of this project is to explore the relationship between lifestyle and stress levels, leveraging machine learning techniques to create a predictive model. This can provide insights into how lifestyle choices impact stress and help in recommending healthier habits.

## Methodology
We employed a range of machine learning concepts and techniques, including:

1. **Data Preprocessing:**
   - Cleaning and encoding categorical variables.
   - Handling missing values and outliers.
   - Standardizing numerical features.

2. **Dimensionality Reduction:**
   - Applied **Principal Component Analysis (PCA)** to reduce dimensionality while retaining key information.

3. **Machine Learning Models:**
   - **Logistic Regression:** For baseline classification and interpretability.
   - **Random Forest:** For feature importance analysis and improved accuracy.
   - **Support Vector Machine (SVM):** To handle non-linear relationships.
   - **XGBoost:** For advanced gradient boosting and high-performance predictions.

4. **Model Evaluation:**
   - Used metrics such as accuracy, precision, recall, and F1-score to evaluate the models.
   - Conducted cross-validation to ensure the models generalize well.

## Key Features
- **Stress Prediction:** Predict stress levels based on lifestyle data.
- **Machine Learning Pipeline:** A comprehensive pipeline for preprocessing, model training, and evaluation.
- **Feature Analysis:** Insights into which lifestyle factors have the greatest impact on stress levels.

## Results
- We achieved high predictive accuracy using **XGBoost** and **Random Forest** models.
- PCA helped reduce computational complexity while retaining model performance.

## Future Work
- Expand the dataset to include more diverse samples.
- Explore deep learning models for improved predictions.
- Integrate the predictive model into a user-friendly application to provide personalized stress management tips.

## Dependencies
- Python 3.8+
- Libraries: pandas, numpy, scikit-learn, XGBoost, matplotlib.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
