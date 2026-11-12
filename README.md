# social-network-ads-logistic-regression
A Machine Learning project using Logistic Regression to predict customer purchasing behaviour based on Age and Estimated Salary using the Social Network Ads dataset. Includes data preprocessing, EDA, feature scaling, model training, evaluation, and predictions using Python and Scikit-learn.
# Social Network Ads – Logistic Regression

## 📌 Project Overview

This project uses **Logistic Regression**, a supervised machine learning classification algorithm, to predict whether a customer will purchase a product after viewing an advertisement on a social networking platform.

The model uses customer information such as **Age** and **Estimated Salary** to predict purchasing behaviour.

The main objective is to understand how machine learning can help businesses identify potential customers and improve their advertising strategies.

## 🎯 Project Objectives

- Understand and implement Logistic Regression.
- Perform Exploratory Data Analysis (EDA).
- Clean and preprocess the dataset.
- Identify important features for prediction.
- Train and test a classification model.
- Evaluate model performance using different metrics.
- Predict purchasing behaviour for new customers.

## 📂 Dataset Information

**Dataset Name:** Social_Network_Ads.csv

**Dataset Size:** 400 rows and 5 columns.

| Column | Description |
|---|---|
| User ID | Unique identification number of customers |
| Gender | Gender of the customer |
| Age | Age of the customer |
| EstimatedSalary | Estimated salary of the customer |
| Purchased | Target variable (0 or 1) |

### Target Variable

- `0` – Customer did not purchase the product.
- `1` – Customer purchased the product.

## 🛠️ Technologies and Libraries Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## ⚙️ Project Workflow

1. Import required Python libraries.
2. Load the dataset using Pandas.
3. Perform data exploration and inspection.
4. Check missing values and duplicate records.
5. Perform Exploratory Data Analysis (EDA).
6. Visualize customer purchasing behaviour.
7. Select independent and dependent variables.
8. Split the dataset into training and testing sets.
9. Apply feature scaling using StandardScaler.
10. Build and train the Logistic Regression model.
11. Make predictions using testing data.
12. Evaluate the model performance.
13. Predict purchasing behaviour for new customers.
14. Save the trained model.

## 📊 Exploratory Data Analysis

The following visualizations are used:

- Purchase distribution using Count Plot.
- Customer age distribution using Histogram.
- Estimated salary distribution using Histogram.
- Age vs Estimated Salary using Scatter Plot.
- Logistic Regression decision boundary.

## 🤖 Machine Learning Algorithm

**Logistic Regression**

Logistic Regression is a supervised machine learning algorithm used for classification problems.

In this project, it predicts whether a customer will purchase a product based on their age and estimated salary.

### Features Used

**Independent Variables (X):**
- Age
- EstimatedSalary

**Dependent Variable (y):**
- Purchased

The `User ID` column is excluded because it is an identification field rather than a meaningful predictive feature.

## 📈 Model Evaluation

The model is evaluated using the following performance metrics:

- Accuracy Score
- Confusion Matrix
- Precision Score
- Recall Score
- F1 Score
- Classification Report

The actual performance results are generated after training and testing the model.

## 🚀 Installation and Execution

### Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/Social-Network-Ads-Logistic-Regression.git
```

### Step 2: Navigate to Project Folder

```bash
cd Social-Network-Ads-Logistic-Regression
```

### Step 3: Install Required Libraries

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter joblib
```

### Step 4: Launch Jupyter Notebook

```bash
jupyter notebook
```

### Step 5: Open the Notebook

Open `Social_Network_Ads_Logistic_Regression.ipynb` and execute the cells sequentially.

## 📁 Project Structure

```text
Social-Network-Ads-Logistic-Regression/
│
├── Social_Network_Ads.csv
│
├── Social_Network_Ads_Logistic_Regression.ipynb
│
├── logistic_regression_model.pkl
│
├── standard_scaler.pkl
│
└── README.md
```

## 🔮 Sample Prediction

The trained model can predict the purchasing behaviour of a new customer.

Example input:

- Age: 35
- Estimated Salary: 60000

The model provides:
- Predicted class (0 or 1).
- Probability of purchasing the product.

## 💡 Applications

- Customer purchase prediction.
- Targeted advertising.
- Customer segmentation.
- Marketing campaign optimization.
- Understanding customer purchasing behaviour.

## 📝 Conclusion

This project demonstrates the practical implementation of Logistic Regression for a binary classification problem.

By using customer age and estimated salary, the model learns patterns in purchasing behaviour and predicts whether a customer is likely to purchase a product.

This project provides hands-on experience with data preprocessing, exploratory data analysis, feature scaling, model training, prediction and evaluation.

## 👨‍💻 Author

**Hardik Ravriya**

Machine Learning | Python | Data Science

## ⭐ Acknowledgement

This project was developed for learning and practicing supervised machine learning techniques using Python and Scikit-learn.
