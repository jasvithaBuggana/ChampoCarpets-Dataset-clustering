## Champo Carpets Dataset Analysis using Clustering Models

## Overview

This Python code comprises an Exploratory Data Analysis (EDA) of the Champo Carpets dataset, employing clustering models. The analysis provides actionable recommendations based on insights derived from the dataset.

## Approach

1. **Data Preparation:**
   - Convert all numerical data types to float for ease of normalization.

2. **Normalization:**
   - Normalize the dataframe using the StandardScaler() method.

3. **Euclidean Matrix Calculation:**
   - Calculate the distance between data points using the Euclidean matrix.

4. **Hierarchical Clustering:**
   - Utilize the Linkage function with different methods: ['single', 'complete', 'average', 'ward'] to generate dendrograms.

5. **Dendrogram Analysis:**
   - Choose the number of clusters based on the dendrograms.

6. **Cluster Assignment:**
   - Assign cluster labels to the data points using the selected linkage method.

7. **Cluster Line Chart:**
   - Create a line chart to visualize clusters, grouping data points belonging to the same cluster.
   - This helps identify each cluster's characteristic.

## Recommendations

1. **Focus on USA Preferences:**
   - Since the USA contributes to more than 86.2% of sales, prioritize inventory for the preferences of USA orders.
   - Example: USA orders often include Hand Tufted carpets with rectangular-shaped designs.
   - Be prepared with these carpets or establish procurement partnerships for raw materials to meet USA preferences.

2. **Strategic Approach for UAE Orders:**
   - Recognize that UAE places significant big orders, indicating a trend of bulk purchasing with higher average quantities.
   - Maintain strong business relations with UAE and leverage predictive analytics to anticipate their next big order items in advance.

3. **Customer Loyalty Strategy:**
   - Identify and focus on the top customers in the top 5 countries.
   - Offer targeted discounts or exclusive deals to these top customers to foster loyalty and prevent revenue losses.

