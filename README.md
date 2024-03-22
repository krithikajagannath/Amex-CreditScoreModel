
**Amex Credit Score Model**

**Introduction:**

This project develops a statistical model for credit scoring based on customer data. The goal is to predict creditworthiness of American Express (Amex) customers using various financial and personal attributes. This model aims to assist in decision-making processes for loan approvals and credit limit assessments.

**Data Preparation:**

The dataset comprises financial records and personal information of Amex customers, including age, income, debt levels, and historical repayment behavior. We performed the following steps for data preparation:

**Data Cleaning:** 

Removed duplicates, handled missing values, and corrected data inconsistencies.

**Feature Engineering:**

Created new features that capture customer behavior and financial health from existing data.

**Model Building:**

We utilized the Weight of Evidence (WoE) method to transform categorical variables into numerical scores, facilitating logistic regression analysis.

**Model Selection:** 

Explored various statistical models, finally choosing logistic regression for its interpretability and efficiency in binary classification tasks.

**Training and Validation:** 

Employed cross-validation techniques to ensure model robustness and minimize overfitting.

**Analysis and Results:**

The model's performance was evaluated using accuracy, precision, recall, and ROC-AUC metrics. 

**Key findings include:**

Predictive accuracy of the model on test data.
Important features influencing credit score predictions.

**Conclusion:**

The model effectively identifies patterns and predictors of creditworthiness among Amex customers. Future work could explore more complex models, integrate additional data sources, or apply the model to other customer segments.
