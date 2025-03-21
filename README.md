# Insurance Fraud Detection

## Overview
This project focuses on detecting fraudulent insurance claims using machine learning models. Various classification algorithms are trained and evaluated to identify fraudulent claims based on historical data.

## Dataset
The dataset used contains insurance claim details, including categorical and numerical features. Some columns contain missing values, which are handled during preprocessing.

## Project Workflow
### 1. Data Preprocessing
- Loaded the dataset and replaced missing values (`?` → `np.nan`).
- Handled missing values in `collision_type`, `property_damage`, and `police_report_available`.
- Converted categorical variables into numerical representations using Label Encoding.
- Standardized numerical features for better model performance.

### 2. Model Training & Evaluation
The following machine learning models were trained and evaluated:
- **Random Forest**
- **Gradient Boosting**
- **AdaBoost**
- **Logistic Regression**
- **K-Nearest Neighbors**
- **Decision Tree**
- **XGBoost**
- **Stochastic Gradient Boosting**

**Evaluation Metrics:**
- **Accuracy Score**
- **Confusion Matrix**
- **ROC AUC Score**
- **Precision-Recall Curve**

### 3. Results
- The best-performing model achieved a **high ROC AUC score**, indicating strong fraud detection capability.
- Confusion matrices and classification reports provide insights into false positives and false negatives.
- Feature importance was analyzed for tree-based models to understand key factors contributing to fraud detection.

## Key Takeaways for Data Science Roles
This project showcases essential skills for data science roles, including:
- **Data Cleaning & Preprocessing:** Handling missing values and encoding categorical variables.
- **Feature Engineering:** Standardization and label encoding for better model performance.
- **Model Selection & Training:** Comparison of multiple classifiers to identify the best model.
- **Performance Evaluation:** Using classification metrics (accuracy, ROC AUC, confusion matrix) for model assessment.
- **Visualization & Interpretability:** Generating confusion matrices and feature importance plots for insights.

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/insurance-fraud-detection.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook InsuranceFraudDetection.ipynb
   ```

## Future Improvements
- Hyperparameter tuning for improved model accuracy.
- Deployment as a web service for real-time fraud detection.
- Integration of deep learning models for better fraud detection.

## Contributors
- **Your Name** - Data Science & Machine Learning Enthusiast

Feel free to contribute to this project and improve its performance!

---
**License:** MIT License

