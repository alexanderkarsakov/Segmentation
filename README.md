# Customer Segmentation using K-Means Clustering

## Project Overview
This project focuses on customer segmentation using unsupervised machine learning, specifically the **K-Means Clustering** algorithm. The goal is to group customers based on their demographics, such as **Age**, **Annual Income**, and **Spending Score**, to create meaningful customer segments. These segments can then be targeted with personalized marketing campaigns to improve customer engagement and drive sales. We utilize a dataset from **Kaggle** that includes information about customers from a mall.

## Steps Involved

1. **Data Preprocessing**: 
   - We started by exploring the dataset to understand its structure and the different attributes available. 
   - We handled missing values and performed encoding where necessary (e.g., converting categorical variables like 'Gender' into numeric values).
   - Standardization was applied to the dataset using **StandardScaler** from scikit-learn to bring all features to a common scale, which is critical for distance-based algorithms like K-Means.

2. **Exploratory Data Analysis (EDA)**:
   - We visualized the distribution of features like **Age**, **Annual Income**, and **Spending Score** using histograms and kernel density estimation (KDE) plots.
   - We also examined the correlation between different variables through a heatmap, identifying potential relationships that could help in clustering.
   
3. **Feature Selection**:
   - We selected the relevant features, focusing on **Age**, **Annual Income**, and **Spending Score**, as these attributes provide valuable insights into customer behavior and purchasing patterns.

4. **Clustering using K-Means**:
   - We applied the **K-Means Clustering** algorithm to the dataset to segment customers into distinct clusters based on their spending and income patterns.
   - We used the **Elbow Method** to determine the optimal number of clusters and performed clustering for 3, 4, and 5 clusters to test different segmentation strategies.

5. **Analysis of Clusters**:
   - After performing clustering, we analyzed each segment to understand the characteristics of customers in each cluster, such as their income, spending score, and age.
   - We used tools like **cross-tabulation** and **mean aggregation** to summarize the behavior of each group.

6. **Marketing Strategy**:
   - Based on the segmentation, we crafted personalized marketing strategies for each cluster. 
   - These strategies include targeted campaigns for high-income, low-spending groups, exclusive promotions for high-spending customers, and budget-friendly offers for younger, price-sensitive segments.

## Conclusion
This project demonstrates how customer segmentation can be effectively achieved using unsupervised learning techniques, allowing businesses to target specific customer groups with tailored marketing strategies. By understanding the behaviors and preferences of different customer segments, companies can increase customer engagement and optimize their marketing efforts.

## Technologies Used
- Python
- Scikit-learn
- Pandas
- Matplotlib
- Seaborn

## Dataset
The dataset used in this project is the [**Mall Customer Segmentation**](https://www.kaggle.com/datasets/shwetabh123/mall-customers) dataset, available on Kaggle.

