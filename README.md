# Credit-Card-Fraud-Detection

## Introduction

In this project, we address credit card fraud detection using graph-based modeling with Neo4j. Inspired by a Fortune 500 financial services case study, we aim to detect fraudulent transactions by leveraging relationships between users, transactions, merchants, and categories. Neo4j's graph database helps visualize these connections and detect anomalies more efficiently than traditional relational databases.

## Problem Statement

Our goal is to detect fraudulent transactions based on the disputed status of credit card transactions in the dataset. We use Neo4j to model relationships between various entities such as users, credit cards, merchants, and transactions.

## Dataset

The dataset is synthetic and sourced from Kaggle: [Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/kartik2112/fraud-detection). It includes simulated credit card transactions from January 2019 to December 2020 for 1000 customers and 800 merchants.

### Key Entities:

- **User**: Performs transactions.
- **Credit Card**: Owned by the user.
- **Transaction**: Contains details such as amount, time, and disputed status.
- **Merchant**: Receives the transactions from users.
- **Category**: Merchant categories.

## Data Preprocessing

Data cleaning and transformation tasks:
1. Removed `null` and `NaN` values.
2. Removed duplicate entries.

## Conclusion

Using Neo4j, we successfully modeled credit card transactions and detected patterns of fraud. The graph-based approach allowed us to uncover difficult-to-detect patterns that traditional relational databases struggled to identify.
