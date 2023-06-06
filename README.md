# Disease-Symptoms - Exploratory Data Analysis and Classification Alogrithms

## Disease Symptoms and Patient Profile Dataset

### Overview
The "Disease Symptoms and Patient Profile" dataset is a collection of medical records that captures various symptoms and patient profiles for a range of diseases or medical conditions. It provides valuable insights into the relationship between symptoms, patient characteristics, and disease outcomes.

### Dataset Features
The dataset contains the following features:

    - Disease: The name of the disease or medical condition under consideration.
    - Fever: Indicates whether the patient has a fever (Yes/No).
    - Cough: Indicates whether the patient has a cough (Yes/No).
    - Fatigue: Indicates whether the patient experiences fatigue (Yes/No).
    - Difficulty Breathing: Indicates whether the patient has difficulty breathing (Yes/No).
    - Age: The age of the patient in years.
    - Gender: The gender of the patient (Male/Female).
    - Blood Pressure: The blood pressure level of the patient (Normal/High).
    - Cholesterol Level: The cholesterol level of the patient (Normal/High).
    - Outcome Variable: The outcome variable indicating the result of the diagnosis or assessment for the specific disease (Positive/Negative).

### Analysis and Modeling
 EDA (Exploratory Data Analysis) and classification algorithms were performed on the dataset. The following steps were taken:

    1. Exploratory Data Analysis: The dataset was explored to gain insights into the distribution of variables, identify any missing values, and understand the relationships between different features.

    2. Data Preprocessing: Data preprocessing techniques such as handling missing values, encoding categorical variables, and scaling numerical variables were applied to prepare the dataset for modeling.

    3. Feature Selection: Relevant features were selected based on their importance and correlation with the outcome variable.

    4. Model Selection: Several classification algorithms were evaluated, including Logistic Regression, Decision Tree, Random Forest, SVM, Naive Bayes, and Gradient Boost. The Gradient Boost algorithm was identified as the best performing model based on various evaluation metrics.

    5. Model Evaluation: The selected model (Gradient Boost) was evaluated using various performance metrics such as mean absolute error, mean squared error, root mean squared error, AUC (Area Under the Curve), sensitivity, specificity, and Matthews correlation coefficient.

    6. Model Deployment: The trained Gradient Boost model can be used to predict the outcome (Positive/Negative) for new patient profiles based on their symptoms and characteristics.
    
### Conclusion
The "Disease Symptoms and Patient Profile" dataset provides valuable insights into the relationship between symptoms, patient characteristics, and disease outcomes. Through EDA and classification modeling, the Gradient Boost algorithm was identified as the best performing model for predicting the outcome of the diagnosis or assessment for specific diseases. The trained model can be used to make predictions on new patient profiles and assist in disease diagnosis and treatment decisions.

### Acknowledgement
I would like to express our gratitude to the contributors of the "Disease Symptoms and Patient Profile" dataset on Kaggle for providing this valuable resource for research and analysis. The dataset can be accessed [here](https://www.kaggle.com/datasets/uom190346a/disease-symptoms-and-patient-profile-dataset)

