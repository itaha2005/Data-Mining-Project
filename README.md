**Customer Segmentation & Spending Analysis **(Data Mining Project)
📌 Project Overview

This project focuses on Customer Segmentation and Spending Behavior Analysis using Machine Learning techniques. It involves data preprocessing, exploratory data analysis (EDA), regression, classification, and clustering to extract meaningful insights and predict customer behavior.

The goal is to:

Analyze customer demographics and spending patterns
Predict spending scores
Segment customers into groups for better business decisions
📂 Dataset

The project uses two datasets:

train.csv – Used for training models
test.csv – Used for testing and predictions
Features include:
Gender
Age
Profession
Work Experience
Family Size
Spending Score
Graduation Status
Marital Status
Segmentation (Target Variable)
⚙️ Technologies & Libraries Used
🐍 Programming Language
Python 3
📚 Libraries
Data Handling
pandas
numpy
Visualization
matplotlib
seaborn
Machine Learning (scikit-learn)
LinearRegression
LogisticRegression
DecisionTreeRegressor
RandomForestRegressor
GradientBoostingRegressor
RandomForestClassifier
GradientBoostingClassifier
KMeans (Clustering)
Preprocessing
LabelEncoder
StandardScaler
Evaluation Metrics
mean_squared_error
accuracy_score
classification_report
confusion_matrix
cross_val_score
cross_val_predict
🔍 Project Workflow
1. Data Preprocessing
Handling missing values using forward fill
Encoding categorical variables using Label Encoding
Feature scaling using StandardScaler
2. Exploratory Data Analysis (EDA)
Gender distribution (Pie chart)
Age distribution
Family size analysis
Spending score distribution
Spending by profession
Work experience vs gender
Correlation heatmap
3. Regression Models (Spending Prediction)

Used to predict numerical spending score:

Linear Regression
Decision Tree Regressor
Random Forest Regressor
Gradient Boosting Regressor

📌 Evaluation Metric:

Mean Squared Error (MSE)
4. Clustering (Customer Segmentation)
K-Means Clustering
Elbow Method used to find optimal clusters
Customers grouped into 4 clusters

📊 Visualization:

Age vs Work Experience clustering plot
5. Classification Models (Customer Segmentation Prediction)

Used to predict customer segments (A, B, C, D):

Logistic Regression
Random Forest Classifier
Gradient Boosting Classifier

📌 Evaluation:

Cross-validation accuracy
Confusion matrix
Classification report
6. Feature Importance Analysis

Feature importance extracted for:

Linear Regression
Decision Tree
Random Forest
Gradient Boosting
📈 Results & Insights
Different ML models were compared using MSE and accuracy
Clustering revealed distinct customer groups
Classification models successfully predicted customer segments
Feature importance helped identify key factors influencing spending
