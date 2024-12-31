# Customer Churn Prediction Project

## Introduction

Customer churn refers to the loss of clients or subscribers. It is a critical metric for businesses as acquiring new customers is often more costly than retaining existing ones. Understanding and predicting customer churn enables companies to implement strategies to improve customer retention.

This project focuses on analyzing and predicting customer churn using two real-world datasets: a bank customer churn dataset and a telecom customer churn dataset.

## Datasets

This project utilizes two datasets obtained from Kaggle:

1. **Telco Customer Churn Dataset**
   - **Description**: Contains information about a telecom company's customers, including demographics, account details, services subscribed, and whether they have churned.
   - **Link**: [Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

2. **Bank Customer Churn Dataset**
   - **Description**: Includes data on bank customers, their personal information, account activity, and churn status.
   - **Link**: [Bank Customer Churn Dataset](https://www.kaggle.com/datasets/gauravtopre/bank-customer-churn-dataset)

## Project Overview

The goal of this project is to build predictive models that can accurately identify customers who are likely to churn. By analyzing the patterns and factors that contribute to churn, businesses can take proactive measures to enhance customer satisfaction and loyalty.

### Objectives:

- Perform exploratory data analysis (EDA) to understand the datasets.
- Preprocess the data, handling missing values and encoding categorical variables.
- Engineer features that improve model performance.
- Build and evaluate machine learning models.
- Interpret the results to provide actionable business insights.

## Installation

To run this project locally, please ensure you have the following software installed:

- Python 3.6+
- Jupyter Notebook or JupyterLab



### Create a Virtual Environment (Optional but Recommended)

```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

**Note**: The `requirements.txt` file contains all the necessary Python packages for this project.

## Usage

Open the Jupyter notebooks to explore the analysis and modeling steps:

```bash
jupyter notebook
```

- **For the Telco dataset**: Open `Telco_Customer_Churn.ipynb`
- **For the Bank dataset**: Open `Bank_Customer_Churn.ipynb`

Each notebook includes step-by-step explanations and code to:

- Load and explore the data.
- Preprocess and prepare the data for modeling.
- Train and evaluate various machine learning models.
- Visualize results and interpret model performance.

## Results

### Telco Customer Churn

- **Key Features Influencing Churn**:
  - Contract type.
  - Tenure.
  - Monthly charges.
- **Best Performing Model**: Gradient Boosting Classifier with an accuracy of 80% and ROC-AUC score of 0.85.

### Bank Customer Churn

- **Key Features Influencing Churn**:
  - Credit score.
  - Balance.
  - Number of products.
- **Best Performing Model**: Random Forest Classifier with an accuracy of 86% and ROC-AUC score of 0.89.

### Insights

- Customers with shorter tenure and month-to-month contracts are more likely to churn in the telecom sector.
- Higher account balances and multiple products are associated with lower churn rates in banking.
- Personalized retention strategies can be developed targeting high-risk customer segments.

## Contributing

Contributions are welcome! If you'd like to improve this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes with clear messages.
4. Push to your branch and submit a pull request.


## Acknowledgments

- **Kaggle** for providing the datasets:
  - [Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
  - [Bank Customer Churn Dataset](https://www.kaggle.com/datasets/gauravtopre/bank-customer-churn-dataset)
- **Community Contributors** for their insights and support.

---

Feel free to explore, modify, and use the code and insights from this project for your own learning or business needs. If you have any questions or suggestions, please open an issue or contact me directly.

