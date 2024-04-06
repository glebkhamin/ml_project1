# ml_project1

Using ML in Predicting Car Insurance Sales

- Data Overview: Analyzed data for 304,887 customers, identifying a target variable imbalance with only 12.2% showing interest in car insurance.
- Key Findings from EDA:
  - Variables like gender and driving license had minimal impact.
  - Past accidents and loyalty status (switch) were significant predictors.
- Data Preparation:
  - Used KNN imputer for numerical and mode imputation for categorical variables.
  - Applied undersampling to address data imbalance.
- Modeling Insights:
  - Established baseline with SVM, showing poor performance on minority class.
  - Explored various sampling methods; undersampling chosen for efficiency.
  - Feature selection refined to focus on impactful variables.
- Model Selection and Tuning:
  - Compared multiple classifiers; logistic regression, decision tree, and AdaBoost showed promise.
  - AdaBoost outperformed others in test set evaluation.
- Special Approach: Evaluated AdaBoost on a dataset without imputed values, significantly improving model performance.
- Conclusion:
  - Dropping missing values and focusing on key features improved baseline performance.
  - Highlighted the importance of obtaining accurate data on past accidents and loyalty for future predictions.
