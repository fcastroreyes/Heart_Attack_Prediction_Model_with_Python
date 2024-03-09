# Heart_Attack_Prediction_Model_with_Python
This Jupyter Notebook demonstrates the use of machine learning techniques to predict heart attack risks, highlighting the importance of accurate medical diagnostics. It navigates through data preprocessing, model training, and rigorous evaluation to select the most effective model based on recall.

# Notebook Overview
## Objective: The primary goal is to develop predictive models that can accurately determine the risk of heart attacks in patients based on multiple health indicators and demographics.

# Key Insights
The notebook underscores the criticality of choosing the right metrics (such as recall) in predictive models for health diagnoses. It provides a foundation for leveraging machine learning in medical predictions, with potential implications for improving patient outcomes through early risk identification.

# Dependencies
To run this notebook, you'll need Python libraries such as pandas, numpy, sklearn, and plotnine. Ensure these are installed to replicate the analysis successfully.

# Methodology:
- Comprehensive data exploration and preprocessing, including handling missing values and encoding categorical variables.
- Application of multiple machine learning models (e.g., K-Nearest Neighbors, Decision Trees, Logistic Regression) to predict heart attack risk.
- Detailed model evaluation using cross-validation and metrics such as accuracy, precision, recall, and ROC AUC to assess model performance. Special emphasis is placed on minimizing false negatives through recall optimization, given the critical nature of false negatives in medical diagnosis.
- Insights into variable importance and model selection based on performance metrics and the clinical relevance of minimizing false negatives.

# Results:
- Highlighted the significance of recall as a crucial metric for model selection due to the emphasis on minimizing false negatives in medical predictions.
- Identified the model with the best recall score (81% cross-validated recall) for not_at_risk predictions, emphasizing its potential utility in clinical settings to accurately identify individuals at risk.

# Conclusion: 
Emphasized the importance of precise model selection in medical diagnoses and the potential for future enhancements by exploring sex-based models or varying variable combinations for improved prediction accuracy.

