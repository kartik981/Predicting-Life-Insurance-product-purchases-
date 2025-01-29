# Predicting Life Insurance Purchase Using Supervised Machine Learning

## Introduction
With the rapid advancement of big data technologies, companies leverage machine learning algorithms to improve customer insights and decision-making. This project applies various supervised machine learning models to predict whether a customer will purchase a life insurance product based on demographic and behavioral data.

## Methodology
### Data Preparation
- **Data Cleaning:**
  - Identified and handled missing values.
  - Removed outliers and duplicate records.
  - Encoded categorical variables numerically.
  - Scaled numerical variables using Min-Max normalization.

- **Feature Selection:**
  - Identified significant predictors using correlation analysis.
  - Key variables: gender, education, mortgage, online presence, family income.

- **Data Splitting:**
  - Split data into training and testing sets.
  - Applied oversampling to balance class labels.

### Machine Learning Models
- **K-Nearest Neighbors (KNN)** - Measures similarity between customers.
- **Logistic Regression** - Predicts probabilities for binary classification.
- **Support Vector Machine (SVM)** - Finds optimal hyperplane for classification.
- **Decision Tree** - Builds tree-based decisions for interpretability.

## Results
### Model Performance
| Model                  | Accuracy  |
|------------------------|-----------|
| K-Nearest Neighbors    | 95.1%     |
| Logistic Regression    | 97.3%     |
| Support Vector Machine | 98.2%     |
| Decision Tree          | 96.5%     |

### Key Insights
- **Feature Importance:**
  - Education, gender, and mortgage were the most influential factors.
- **Prediction Trends:**
  - Higher-income individuals were more likely to purchase life insurance.
  - Online presence significantly impacted the decision.

## Conclusion
Machine learning can enhance customer targeting and underwriting in the life insurance industry. Addressing challenges like data privacy, dataset quality, and model interpretability will further improve results.

## References
- Bhatia, R. et al. (2021). *Life Insurance Purchase Behavior.*
- Descombes, J. (2021). *COVID-19 and Life Insurance Trends.*
- Sivarajah, U. (2017). *Big Data Challenges and Analytical Methods.*
