# Heart-Disease-Classification-Using-Logistic-Regression
Led a data-driven project utilizing logistic regression to predict heart disease based on input features. Achieved 91% accuracy and uncovered vital risk factors, contributing to improved cardiovascular health insights.

Project Approach:

- Importing Libraries: The project begins with importing necessary Python libraries for data manipulation, visualization, and modeling.
- Basic Data Exploration: Initial exploration of the dataset includes checking for missing values and obtaining a statistical summary.
- Data Visualization: Data is visualized using various plots, including a heatmap to explore correlations and count plots to understand the distribution of the target variable.
- Feature Engineering: Binary categorical columns are encoded, and label encoding is applied to categorical columns with more than two unique values.
- Train-Test Split: The dataset is divided into training and test sets, and feature scaling is performed using StandardScaler.
- Logistic Regression Modeling: A logistic regression model is created, trained on the training data, and evaluated on the test data.
- Performance Evaluation: Model performance is evaluated using accuracy, precision, recall, F1-score, and ROC curve analysis.
- Loss Convergence Curve: The loss convergence curve is plotted to visualize the model's learning process.

Key Insights:

- BMI Impact: BMI values between 20 and 29.99 indicate a lower likelihood of heart disease. Deviating from this range increases the probability of heart disease.
- Smoking Risk: Smokers have a significantly higher risk of heart disease compared to non-smokers.
- Gender Susceptibility: Males exhibit a greater susceptibility to heart diseases than females.
- Age Factor: Individuals aged between 55 and 75 are more likely to experience heart-related issues.
- Difficulty Walking: Difficulty walking or climbing stairs is associated with a higher likelihood of heart ailments.
- Key Features: Features such as BMI, smoking status, history of stroke, physical health, mental health, difficulty walking, gender, age category, race, diabetes, asthma, and kidney disease are vital in predicting heart disease.
- Model Performance: The logistic regression model achieves an accuracy of 0.91 but suffers from low recall due to class imbalance.
- AUC Score: The AUC score of 0.54 indicates that the model's ability to distinguish between individuals with and without heart disease is limited.
