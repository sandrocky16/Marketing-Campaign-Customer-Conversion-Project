# Marketing-Campaign-Customer-Conversion-Project
🧩 Problem Statement
- Predict whether a customer will subscribe to a term deposit using demographic and campaign data
- Handle a highly imbalanced dataset with very few "Yes" (converted) cases
- Overcome bias of traditional models toward the majority class

🎯 Objectives
- Build a binary classification model for customer conversion prediction
- Improve detection of minority class (potential customers)
- Compare multiple models to identify the best performer
- Optimize model efficiently using RandomizedSearchCV

🛠️ Approach
- Data Preprocessing:
  - Handle missing and unknown values
  - Encode categorical variables
  - Perform feature transformations

- Imbalance Handling:
  - Apply ADASYN (Adaptive Synthetic Sampling)
  - Use class weight balancing

- Model Building:
  - Logistic Regression
  - Random Forest Classifier

- Model Optimization:
  - Use RandomizedSearchCV for efficient hyperparameter tuning

- Evaluation Metrics:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - ROC-AUC
 
📊 Results
- Imbalance handling significantly improved minority class prediction
- ADASYN-based models achieved higher recall and better F1-score
- Trade-off observed: improved recall with slight drop in precision

💡 Key Insights
- RandomizedSearchCV reduced tuning time while maintaining strong performance
- Handling class imbalance is critical for model effectiveness
- Recall is more important than accuracy in this use case
- ADASYN improves minority class learning better than class weighting

💼 Business Impact
- Enables targeting of high-potential customers
- Improves conversion rates in marketing campaigns
- Reduces unnecessary marketing costs
- Supports data-driven decision making
