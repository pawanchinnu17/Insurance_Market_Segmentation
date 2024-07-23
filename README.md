# Market Segmentation in Insurance

![dataset-cover](https://github.com/user-attachments/assets/6dedd8c8-c7eb-482b-ba57-2fce3ccf9e6c)

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
![app · Streamlit - Google Chrome 23-07-2024 13_56_01](https://github.com/user-attachments/assets/b65465c6-7d86-479d-b806-01dddb2f4172)


### Customer Segmentation

![app · Streamlit - Google Chrome 23-07-2024 13_56_23](https://github.com/user-attachments/assets/a27679c1-961b-4dff-b244-d3e41709a69c)

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
