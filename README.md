# Credit Risk Modeling Project

## Project Overview
This repository contains a project on credit risk modeling using data from two sources:
1. **CIBIL Dataset**: Provides credit-related information such as credit scores and repayment history.
2. **Bank Internal Dataset**: Includes proprietary data such as account details, transaction history, and internal risk assessments.

The project focuses on assessing credit risk by analyzing these datasets and building predictive models to identify high-risk customers.

## Objectives
The key objectives of this project are:
1. **Data Integration**: Combine CIBIL and bank internal datasets for a comprehensive view of customer credit risk.
2. **Exploratory Data Analysis (EDA)**: Uncover patterns and trends in credit behavior.
3. **Credit Risk Prediction**: Develop machine learning models to predict the likelihood of loan default.
4. **Business Insights**: Provide actionable insights to improve credit decision-making processes.

## Dataset Description
A separate excel file has been given which contain detailed description of each feature.

## Project Structure
The repository is organized as follows:
- `data/`: Contains sample datasets (anonymized for confidentiality).
- `notebooks/`: Jupyter notebooks for EDA, feature engineering, and model development.
- `scripts/`: Python scripts for data preprocessing and model training.

## Tools and Technologies
The following tools and libraries are used:
- **Python**: Core programming language.
- **Pandas & NumPy**: Data manipulation and numerical computation.
- **Matplotlib & Seaborn**: Data visualization.
- **Scikit-learn**: Machine learning.
- **XGBoost**: Advanced gradient boosting models for prediction.
- **SQL**: Querying the bank's internal database.

## Methodology
1. **Data Preparation**:
   - Load and clean the datasets.
   - Merge the CIBIL and internal datasets using unique identifiers.
   - Handle missing values and outliers.
2. **Exploratory Data Analysis (EDA)**:
   - Analyze credit scores, repayment patterns, and loan defaults.
   - Visualize correlations between features and default rates.
3. **Feature Engineering**:
   - Derive new features such as debt-to-income ratio and transaction frequency.
   - Encode categorical variables.
4. **Model Development**:
   - Train-test split to create separate datasets for training and evaluation.
   - Train models (Logistic Regression, Random Forest, XGBoost) to predict loan default.
   - Optimize model parameters using Grid Search.
5. **Evaluation**:
   - Use metrics like AUC-ROC, precision, recall, and F1-score to evaluate model performance.
6. **Reporting**:
   - Summarize insights and results.
   - Create visual dashboards for stakeholders.

## How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/princedoobay/credit_modeling.git
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Navigate to the `notebooks/` directory and explore the analysis steps.
4. Run `scripts/train_model.py` to train the predictive models.

## Results
- Detailed analysis of factors contributing to credit risk.
- Predictive models with high accuracy in identifying high-risk customers.
- Recommendations for improving credit risk policies.

## Future Scope
- Include additional data sources for better prediction.
- Implement real-time credit risk scoring using APIs.
- Deploy the model as a web-based application.

## Acknowledgments
- **CIBIL**: For providing credit data.
- **Bank**: For sharing anonymized internal data.

## License
This project is licensed under the [MIT License](LICENSE).

# credit_modeling
