# ConnectTel Customer-Churn-Prediction

<img src="https://www.ibm.com/content/dam/connectedassets-adobe-cms/worldwide-content/cdp/cf/ul/g/27/97/lifecycle_leadspace.component.xl.ts=1712852083772.jpg/content/adobe-cms/us/en/consulting/telecommunications/_jcr_content/root/leadspace" height="250" />

## Project Overview
Customer churn is a critical issue for businesses as acquiring new customers is often more expensive than retaining existing ones. By predicting which customers are likely to churn, ConnectTel can proactively address the issues leading to churn and implement targeted retention strategies.

## Project Features
### Data Preprocessing
- **Data Cleaning:** Cleaned and prepared the dataset for analysis by converting data types and handling missing values.
- **Feature Engineering:** Created new features, such as tenure_range for visualisation.
- **Encoding and Scaling:** Encoded categorical variables and scaled numerical features to ensure they are on a comparable scale.
    
### Data Analysis
- Conducted exploratory data analysis (EDA) to understand the distribution of data and relationships between variables.
- Identified key features that influence customer churn.

### Data Visualization
- Created informative visualizations using Matplotlib and Seaborn to present data in a clear and informative manner.
- Visualized key metrics and distributions to understand churn patterns.

### Modeling
- Employed various classification models to predict customer churn, including Logistic Regression, Random Forest, XGBoost, and Linear SVC.
- Addressed class imbalance issues using SMOTE (Synthetic Minority Over-sampling Technique).
- Conducted hyperparameter tuning to optimize model performance.
- Performed feature selection using Random Forest to identify the most important features.

### Evaluation
- Evaluated models using metrics such as AUC (Area Under the Curve), precision, recall, and F1-score.
- Used confusion matrix to analyze model performance in terms of true positives (TP), true negatives (TN), false positives (FP), and false negatives (FN).

## Conclusion
The project successfully identified key predictors of customer churn and evaluated various models for predicting churn. Among the models, Random Forest showed the best performance with high AUC and balanced precision and recall scores, especially after hyperparameter tuning. Key features such as tenure and total charges were significant predictors of churn, providing valuable insights into customer behavior. Overall, the findings provide actionable recommendations for improving customer retention strategies for ConnectTel, ensuring better customer satisfaction and reduced churn rates.

Note: This project is for illustrative purposes only. The data and content are publicly sourced, and I do not own them.
