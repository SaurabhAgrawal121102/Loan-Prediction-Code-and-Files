🧪 Model Training & Analysis (Jupyter Notebook)

This part of the project focuses on the end-to-end Machine Learning pipeline to predict loan eligibility.

Key Steps Performed:

Data Cleaning: Handled missing values in features like Credit_History, Self_Employed, and LoanAmount.

Exploratory Data Analysis (EDA): Visualized relationships between Applicant Income, Credit History, and Loan Status.

Feature Engineering:Applied One-Hot Encoding for categorical variables (Gender, Education, Property_Area).
Optimized feature selection for Android deployment.

Model Selection: Compared multiple algorithms including Logistic Regression, Decision Trees, and Random Forest to find the best balance of accuracy and speed.

Serialization: Exported the final trained model using joblib for deployment in the Android application.

Tools Used:

Pandas & NumPy for data manipulation.

Matplotlib & Seaborn for visualization.

Scikit-Learn for model training and evaluation.
