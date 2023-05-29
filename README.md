# Building an End-to-End Churn Prediction System on AWS

The project aims to analyze customer churn within a banking context using the "bank customer churn" dataset. It involves building a predictive model to identify factors influencing customer churn and creating visualizations using Tableau. The project incorporates AWS services, such as SageMaker, for machine learning and AWS RDS for data storage.

Project Workflow:

1. Data Exploration: Explore the "bank customer churn" dataset, understanding the features and their meanings.
2. Data Preparation: Preprocess and clean the data, handling missing values, and ensuring data quality.
3. AWS Integration: Utilize AWS services like AWS Glue, Lambda, and DMS to create an automated ETL pipeline for data transformation and loading.
4. RDS Database: Set up an RDS database to store the preprocessed data, allowing for efficient data management.
5. Tableau Visualization: Connect Tableau to the RDS database and create interactive dashboards to analyze churn patterns and trends.
6. Feature Selection: Identify relevant input variables from the dataset, such as credit score, country, gender, age, tenure, balance, products_number, credit_card, active_member, and estimated_salary.
7. Machine Learning with SageMaker: Train a predictive model using SageMaker, utilizing the selected input variables to predict customer churn.
8. Model Deployment: Deploy the trained model on a SageMaker endpoint to enable real-time predictions.
9. Model Evaluation: Evaluate the performance of the churn prediction model using appropriate metrics, such as accuracy, precision, recall, and F1-score.
10. Out-of-Sample Evaluation: Collect additional data points representing new customer interactions to assess the model's performance on unseen data.
11. Continuous Updates: Establish a system to handle periodic updates to the data pipeline, enabling the automatic update of the RDS database and Tableau dashboards when new data becomes available.

AWS work flow
![AWS Diagram](https://github.com/parisris/customer_churn_aws/blob/main/img/Diagram.png)
