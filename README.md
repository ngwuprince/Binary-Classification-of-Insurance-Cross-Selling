**Binary Classification of Insurance Cross Selling**

**Project Overview**

This project focuses on predicting which health insurance policyholders would be interested in subscribing to car insurance, using a binary classification model. The project was part of the Kaggle Playground Series ML competition, where participants were challenged to build and optimize models to improve the prediction accuracy.

Competition Link: [Kaggle Playground Series S4E7](https://www.kaggle.com/competitions/playground-series-s4e7/overview)

**Dataset Description**

The dataset provided by the competition consists of features related to health insurance policyholders. These features include demographic information, policy details, and other relevant attributes that could influence a policyholder's decision to purchase additional car insurance.

**Key Features:**

- Age: The age of the policyholder.
- Gender: The gender of the policyholder.
- Region Code: The region code indicating the location of the policyholder.
- Annual Premium: The annual premium paid by the policyholder.
- Policy Tenure: The number of years the policyholder has held the policy.
- Vehicle Age: The age of the policyholder's vehicle.
- Vehicle Damage: Whether the policyholder’s vehicle was previously damaged.
- Driving License: Whether the policyholder holds a driving license.
- Previously Insured: Whether the policyholder already has vehicle insurance.
- Response: The target variable indicating if the policyholder is interested in the car insurance cross-sell.

**Project Objectives**
- Data Preprocessing: Clean and prepare the data for analysis by handling missing values, encoding categorical variables, and normalizing numerical data.
- Exploratory Data Analysis (EDA): Gain insights into the data distribution and feature relationships to guide the modeling process.
- Model Development: Implement various binary classification models to predict policyholder interest in car insurance.
- Model Optimization: Optimize model performance through hyperparameter tuning and feature engineering.
- Model Evaluation: Evaluate models using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.

**Methodology**

**Data Preprocessing:**

- Handle missing values appropriately to maintain data integrity.
- Encode categorical variables using techniques like one-hot encoding or label encoding.
- Normalize numerical features to ensure they are on a comparable scale for model training.

**Exploratory Data Analysis:**

- Analyze the distribution of features and their correlation with the target variable.
- Visualize data patterns and relationships using plots and charts.

**Model Building:**

- Develop multiple binary classification models, including Logistic Regression, Decision Trees, Random Forest, and Gradient Boosting.
- Implement advanced models such as XGBoost and LightGBM for improved performance.

**Model Evaluation:**

- Assess model performance using metrics like accuracy, precision, recall, F1-score, and ROC-AUC to select the best model.
- Use cross-validation to ensure model generalizability and reduce overfitting.

**Hyperparameter Tuning:**

- Perform grid search or random search to find the optimal hyperparameters for the models.

**Final Model Selection:**

- Choose the best-performing model based on evaluation metrics and deploy it for predictions.

**Results & Findings**
- The final model demonstrated strong performance in predicting which policyholders are likely to subscribe to car insurance.
- Features like Vehicle Damage, Previously Insured, and Policy Tenure showed significant importance in the prediction.
- The ROC-AUC score and F1-score were used as the primary metrics to evaluate the model's performance.

**Conclusion**
This project successfully built a binary classification model to predict insurance cross-selling opportunities. The insights gained from the analysis can be utilized by insurance companies to target potential customers more effectively, thereby improving conversion rates for car insurance subscriptions.

**Technology Stack**

- Programming Language: Python
- Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, XGBoost, LightGBM
- Jupyter Notebook: For code development and documentation
