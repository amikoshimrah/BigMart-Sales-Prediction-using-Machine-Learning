# BigMart-Sales-Prediction-using-Machine-Learning
This repository demonstrates a complete data engineering and machine learning pipeline involving both loan and retail datasets.

Data Loading:

Extract data (item_info, outlet_info, sales_info) from xml.

Clean and preprocess data for missing values.

Create a MySQL database (bigmart) and load tables.

Retail Sales Data:

Extract data from MySQL tables (item_info, outlet_info, sales_info).

Merge and preprocess datasets for training.

Machine Learning Workflow:

Perform exploratory data analysis (EDA).

Apply feature engineering and one-hot encoding.

Train regression models (Linear Regression, Gradient Boosting).

Evaluate using RMSE, MAE, and R² metrics.

Save trained models with pickle for deployment.

This project bridges data engineering and machine learning, showcasing how raw data from multiple sources can be cleaned, stored, and leveraged for predictive analytics in retail and loan-related domains.
