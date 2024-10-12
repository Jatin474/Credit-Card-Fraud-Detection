# Normalizing Flows for Data Generation and Credit Card Fraud Detection

## Overview

This project combines two powerful concepts: **Normalizing Flows** for data generation and **Credit Card Fraud Detection** using machine learning techniques. The primary objectives are to generate synthetic data using Normalizing Flows and utilize this data to enhance the performance of fraud detection models on real-world credit card transaction datasets.

## Project Structure

```Normalizing_Flows_Credit_Card_Fraud/ │ ├── data/ │ ├── credit_card_data.csv # Original credit card dataset │ ├── generated_data.csv # Synthetic data generated using Normalizing Flows │ ├── notebooks/ │ ├── normalizing_flows_analysis.ipynb # Jupyter Notebook for Normalizing Flows analysis │ ├── fraud_detection_analysis.ipynb # Jupyter Notebook for fraud detection analysis │ ├── src/ │ ├── normalizing_flows.py # Implementation of Normalizing Flows │ ├── data_preprocessing.py # Data preprocessing functions │ ├── model_training.py # Functions for training and evaluating fraud detection models │ ├── requirements.txt # Required libraries for the project └── README.md # Project overview and documentation```

## Dataset

### Credit Card Dataset

The credit card dataset consists of various features relevant to transactions, including:

- **scaled_amount**: The transaction amount, scaled for normalization.
- **scaled_time**: The time of the transaction, scaled for normalization.
- **V1 to V28**: Anonymized features representing various characteristics of the transactions.
- **Class**: The target variable, where 1 indicates a fraudulent transaction and 0 indicates a non-fraudulent transaction.

### Generated Data

Synthetic data is generated using Normalizing Flows, which can be used to augment the existing dataset or to test the robustness of fraud detection models.

## Installation

To run this project, you need to install the following Python libraries. You can install them using pip:
- **scaled_amount**
