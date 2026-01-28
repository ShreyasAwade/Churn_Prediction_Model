Customer Churn Prediction – End-to-End Machine Learning Project
Problem Statement
Customer churn is a major challenge for subscription-based businesses, directly impacting revenue and growth. Organizations need predictive systems to identify customers likely to leave so that proactive retention strategies can be applied.
Objective
To build, evaluate, and deploy an end-to-end Machine Learning model that predicts customer churn using demographic and service usage data, and make predictions accessible through a Streamlit web application.
Dataset Description
The dataset contains customer-level information such as age, gender, tenure, and monthly charges. The target variable indicates whether a customer has churned (1) or not (0).
Approach
• Data Collection and Understanding
• Data Cleaning and Preprocessing
• Encoding Categorical Variables
• Feature Scaling using StandardScaler
• Model Training and Evaluation
• Model Persistence using Joblib
• Deployment using Streamlit
Steps of Execution
Step 1: Load the dataset using Pandas.
Step 2: Inspect and clean the data.
Step 3: Encode categorical variables.
Step 4: Split data into training and testing sets.
Step 5: Apply StandardScaler to numerical features.
Step 6: Train the ML model.
Step 7: Evaluate model performance.
Step 8: Save model and scaler using Joblib.
Step 9: Build Streamlit UI.
Step 10: Load model and generate predictions.
Technology Stack
Python, Pandas, NumPy, Scikit-learn, Streamlit, Joblib
Business Impact
Helps organizations identify high-risk customers early, enabling targeted retention strategies and reducing revenue loss.
