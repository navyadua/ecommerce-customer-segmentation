# E-Commerce Customer Segmentation 👨‍💼📊
![ecommerce-customer-segmentation](https://socialify.git.ci/navyadua/ecommerce-customer-segmentation/image?language=1&name=1&owner=1&theme=Light)
![](https://img.shields.io/badge/Jupyter-F37626.svg?style=for-the-badge&logo=Jupyter&logoColor=white) ![](https://img.shields.io/badge/Google%20Colab-F9AB00.svg?style=for-the-badge&logo=Google-Colab&logoColor=white)  ![](https://img.shields.io/badge/Python-3776AB.svg?style=for-the-badge&logo=Python&logoColor=white)
## Introduction 🚀

In this project, we aim to analyze and segment customers of an e-commerce company using the RFM (Recency, Frequency, Monetary) approach. This segmentation enables the company to enhance their marketing strategies by identifying high-value customers and optimizing retention and acquisition efforts.

## Objectives 🎯

- **Primary Objective:** 
  - Build an unsupervised learning model to analyze customer behavior using the RFM approach.
- **Secondary Objectives:**
  - Provide actionable insights to improve customer retention and acquisition.
  - Segment customers into loyalty categories to tailor marketing strategies.

## Data Description 📄

The dataset comprises e-commerce transaction records from 2016 to 2017, including:
- **Date of Purchase:** Date-time of sale.
- **CustomerID:** Unique identifier for each customer.
- **Shipping Location:** Customer's shipping address.
- **Price per Unit:** Price of a single unit purchased.

## Methodology 📈

- **Data Exploration:** Conducted initial exploration to understand the structure and content of the data, focusing on customer segmentation for targeted marketing and cost efficiency in e-commerce.
- **Exploratory Data Analysis (EDA):** Examined basic statistics of the dataset, handled missing values, removed duplicates, and converted date columns to datetime format during data cleaning. Categorized features into categorical and numerical for better analysis.
- **Data Preprocessing:** Removed irrelevant columns not required for RFM analysis and ensured consistency in column names for clarity.
- **RFM Calculation:** Calculated Recency as days since the customer's last purchase, Frequency as total number of purchases, and Monetary as total purchase value per customer.
- **RFM Scoring:** Determined quartiles for RFM metrics and assigned scores using defined functions for Recency, Frequency, and Monetary values. Created a combined RFM score for each customer.
- **Clustering:** Applied K-means clustering to segment customers based on RFM scores, determined the optimal number of clusters using the Elbow Method, and evaluated results for meaningful segmentation.
- **Loyalty Segmentation:** Segmented customers into loyalty categories (Platinum, Gold, Silver, Bronze) based on RFM scores, providing actionable insights and recommendations for marketing strategies.
- **Visualization and Results:** Visualized customer segments and proportions using a treemap and offered tailored recommendations to enhance retention and acquisition strategies.

## Results and Deliverables 📊

- **RFM Scores and Segmentation:** Saved in `Segmentation_analysis.csv`.
- **Clustering Results:** Saved in `customer_clusters.csv`.
- **Visualizations:** Provided in the Jupyter Notebook for better understanding.
- **Recommendations:** Based on analysis to help the business optimize its marketing strategies.

## Conclusion 🌟

By following a structured approach, we successfully segmented customers using the RFM approach, providing the e-commerce company with valuable insights to enhance their marketing efforts. This project highlights the importance of customer segmentation in achieving targeted marketing and cost efficiency in the e-commerce industry.

## Future Work 🔍

- **Additional Segmentation:** Further analysis could include geographic and demographic segmentation for more detailed customer insights.
- **Model Improvement:** Exploring other clustering algorithms and techniques to improve segmentation accuracy.
- **Extended Analysis:** Analyzing customer lifetime value (CLV) and implementing personalized marketing strategies based on customer segments.
