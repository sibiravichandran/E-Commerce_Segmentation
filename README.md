# E-commerce Customer Segmentation

##  Abstract:

A key challenge for e-commerce businesses is to analyze the trend in the market to increase their sales. The trend can be easily observed if the companies can group the customers; based on their activity on the e-commerce site. This grouping can be done by applying different criteria like previous orders, mostly searched brands and so on.

##  Problem Statement:

Given the e-commerce data, use k-means clustering algorithm to cluster customers with similar interest.

##  Dataset Information:

The data was collected from a well known e-commerce website over a period of time based on the customer’s search profile.

##  Variable Description:

|    Column     |                     Description                      |
| ------------- | -----------------------------------------------------|
| Cust_ID       | Unique numbering for customers                       |
| Gender        | Gender of the customer                               |
| Orders        | Number of orders placed by each customer in the past |

## Remaining 35 features (brands) contains the number of time customers have searched them

## Scope:
         ● Analyzing the existing customer data and getting valuable insights about the purchase pattern
         ● Data pre-processing including missing value treatment
         ● Segmenting customer based on the optimum number of clusters (‘k’) with the help of silhouette score
         
## WORKFLOW:
*        Importing necessary libraries
*        Data Loading
*        Exploratory Data Analysis
*        Handling Missing Values
*        Data Visualizations
*        Encoding Variables
*        Feature Handling
*        Performing MinMax Scaling
*        Deriving insights based on the analysis for the following criteria's like grouping custers based on orders, based on orders and total brands searched and based on brands.
*        Implementing Elbow method and Silhouette Analysis for Optimal K valueand visualizing using the KElbow Visualizer
*        Implementing KMeans Algorithm
*        Derive Insights based on the output of the model with the clusters data
*        Output Data along with the Clusters details is saved as a CSV file

Cluster A : ANALYSIS BASED ON ORDERS
Cluster B : ANALYSIS BASED ON ORDERS AND TOTAL BRANDS SEARCHES
Cluster C : ANALYSIS BASED ON BRANDS

 
 
 
