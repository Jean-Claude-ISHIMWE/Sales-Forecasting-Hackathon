# Sales-Forecasting-Hackathon

This repository contains a **Sales Forecasting Model** developed for the DTP Hackathon using the **Amazon Sale Report __ Copy dataset**. The model estimates future sales for e-commerce enterprises, providing them with valuable insights to make informed business decisions. An interactive dashboard allows you to visualize sales data.

## Project Vision

The aim of this project is to develop an advanced, scalable, and highly accurate **Sales Forecasting Model** using historical sales data. By leveraging state-of-the-art machine learning techniques, such as the **Prophet model**, we strive to help businesses predict future sales and make informed decisions to improve their operations.

## Key Features

- **Sales Forecasting**: Predict future sales for any given timeframe.
- **Interactive Dashboard**: Visualize sales trends, forecasts, and other important insights.
- **Data Cleaning and Preparation**: Handle missing values, outliers, and ensure clean data for modeling.
- **Modeling with Prophet**: Use the Prophet algorithm for time series forecasting.
- **Insightful Visualizations**: Display historical trends, predictions, and anomalies.

## Technologies Utilized

- **Python** (Programming Language)
- **Prophet** (Forecasting Library)
- **Pandas** (Data Processing)
- **Matplotlib** & **Seaborn** (Data Visualization)
- **Jupyter Notebook** (Development Environment)
- **GitHub** (Version Control and Collaboration)
- **Kaggle** (Dataset Source)

## Data Overview

The dataset used for this project is the **Amazon Sales Report __ Copy**, which contains transaction-level sales data. It includes multiple columns such as:
- **Order ID**, **Date**, **Status**, **Sales Channel**, **Amount**, **Qty**, **Ship-city**, **Ship-country**, and others.

The dataset has been processed to remove irrelevant columns and handle missing values. After cleaning the data, we used **Prophet** to forecast future sales.

## Getting Started

### Prerequisites

To get started with this project, ensure you have the following installed on your machine:
- Python 3.x
- Jupyter Notebook
- Anaconda or Virtual Environment (recommended)
- GitHub for version control

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Jean-Claude-ISHIMWE/Sales-Forecasting-Hackathon.git
2. Install the required libraries:
   " pip install -r requirements.txt "
3. Open the notebook:
   "jupyter notebook"
4. Run the notebook to start exploring and forecasting sales.

### How the Model Works
The forecasting model uses the Prophet algorithm to predict future sales. Prophet is particularly suited for time-series data, as it handles trends, seasonality, and holiday effects. The process follows these steps:

1. Data Preprocessing: The dataset is cleaned, and missing values are handled. We convert the 'Date' column to datetime and ensure the necessary columns are formatted.
2. Model Training: The Prophet model is trained on the historical data, where it learns from past trends.
3. Future Prediction: After training, the model predicts sales for the next 30 days or any specified period.

### Insights and Impact
- **Sales Trends**: The model identifies historical sales patterns, helping businesses understand their sales cycles.
- **Forecasting Accuracy**: The model can be used to predict the impact of external factors such as marketing campaigns, holidays, and new product launches.
- **Inventory Management**: With accurate sales forecasts, e-commerce businesses can plan better inventory management, reducing waste and optimizing stock levels.
- **Business Strategy**: The insights from the model help businesses make data-driven decisions, improving overall profitability.

### Dataset
The dataset for this project is sourced from Kaggle and consists of Amazon sales data. It includes columns like Order ID, Date, Status, Amount, Ship-city, and Fulfilment. The raw data has undergone preprocessing to handle missing values and irrelevant columns, ensuring the dataset is ready for analysis and forecasting.
```
[Link to Dataset on Kaggle ](https://www.kaggle.com/datasets/karkavelrajaj/amazon-sales-dataset) 


