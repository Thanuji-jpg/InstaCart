🛒 Instacart Predictions
This project focuses on analyzing and predicting customer purchasing behavior using Instacart datasets provided by Kaggle. It is structured into two key phases: data exploration and predictive modeling, each documented in a separate Jupyter notebook.

📁 Project Structure
Data Exploration.ipynb
This notebook performs comprehensive exploratory data analysis (EDA) on the Instacart dataset. It includes:

Understanding the dataset structure

Handling missing values

Identifying patterns and trends

Visualizing key statistics and distributions

Predictions.ipynb
This notebook focuses on building predictive models to forecast whether a product will be reordered. It includes:

Feature engineering (user-product interactions, reorder ratios, etc.)

Training and evaluating models including:

Logistic Regression

Random Forest Classifier

XGBoost Classifier

Comparing model performance using metrics like accuracy, F1 score, and AUC

Generating final predictions on test data

📊 Dataset
The data used in this project is publicly available on Kaggle - Instacart Market Basket Analysis. It includes information on customer orders, products, departments, and aisles.

⚙️ Requirements
Python 3.x

Jupyter Notebook

pandas, numpy, matplotlib, seaborn

scikit-learn

xgboost

You can install dependencies using:

bash

pip install -r requirements.txt


🔍 Goal
To understand customer purchasing behavior and accurately predict future reorders, helping improve inventory planning and personalized marketing in e-commerce.

📄 License
This project is licensed under the MIT License. See the LICENSE file for details.

