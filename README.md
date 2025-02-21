# IRTM Churn Prediction

## Overview
The **IRTM Churn Prediction** project aims to analyze customer data and predict churn using machine learning techniques. Churn prediction helps businesses identify customers who are likely to leave and take proactive measures to retain them.

## Dataset
The dataset used in this project contains customer-related features such as:
- **Demographics:** Age, gender, location, etc.
- **Account Information:** Subscription plan, tenure, contract type.
- **Usage Behavior:** Monthly charges, total spend, service usage.
- **Customer Support Interactions:** Complaints, resolution time, feedback.

## Project Workflow
1. **Data Preprocessing**: Handling missing values, encoding categorical variables, and feature scaling.
2. **Exploratory Data Analysis (EDA)**: Understanding data distributions, correlations, and visualizing key insights.
3. **Feature Engineering**: Creating new features, removing redundant features, and optimizing input variables.
4. **Model Selection & Training**: Implementing multiple machine learning models such as:
   - Logistic Regression
   - Random Forest
   - XGBoost
   - Neural Networks
5. **Model Evaluation**: Comparing performance using accuracy, precision, recall, F1-score, and AUC-ROC.
6. **Hyperparameter Tuning**: Optimizing models for better performance.
7. **Deployment & Interpretation**: Using SHAP values for explainability and deploying the model (if applicable).

## Requirements
To run this project, you need the following dependencies:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost shap
```

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/IRTM_Churn_Prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd IRTM_Churn_Prediction
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook IRTM_Churn_Prediction.ipynb
   ```
4. Run the notebook cells sequentially.

## Results
- The best performing model achieved an accuracy of **XX%** and an AUC-ROC score of **YY%**.
- Key customer churn indicators identified: [Feature A, Feature B, Feature C].
- Recommendations for reducing churn based on analysis.

## Future Improvements
- Experiment with deep learning models (e.g., LSTMs for sequential data).
- Implement real-time churn prediction using APIs.
- Deploy the model as a web application using Flask/Django.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
