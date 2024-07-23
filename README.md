# Market Segmentation in Insurance
![Header Image](images\dataset-cover.png)

## Objective

This case requires developing a customer segmentation model to give recommendations like saving plans, loans, wealth management, etc., targeting specific customer groups.

## Data Description

The sample dataset summarizes the usage behavior of about 9000 active credit card holders during the last 6 months. The file is at a customer level with 18 behavioral variables.

## Algorithms Used

In this dataset, I've used five clustering algorithms to perform segmentation. These algorithms are given below:

1. K-Means Clustering
2. Agglomerative Clustering
3. Spectral Clustering
4. DBSCAN Clustering
5. Gaussian Mixture Model based Clustering

## Final Model

We have created a Streamlit application based on this clustering technique, where we are taking the customer details and identifying which cluster the customer belongs to.

## Demo

Below are some demo pictures of the application:

### Input Form
![Input Form](images\app · Streamlit - Google Chrome 23-07-2024 13_56_01.png)

### Customer Segmentation
![Customer Segmentation](images\app · Streamlit - Google Chrome 23-07-2024 13_56_23.png)

## Installation

To run this project locally, make sure you have the following dependencies installed:

```plaintext
pandas
numpy
matplotlib
seaborn
scikit-learn
streamlit
plotly
pickle