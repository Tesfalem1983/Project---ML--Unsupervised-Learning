# Project - Unsupervised Learning

## Project Goals:
- Perform unsupervised learning techniques specifically annual spending of product categories on a wholesale data dataset using KMeans clustering, hierarchical clustering, and PCA and communicate insights on the clustering result and what it means for our business.

## Process:
### Step 1: Explanatory Data Analysis:
- By creating visualizations and statistical summary  to spot abnormal distribution & outliers.
### Step 3:  Preprocessing & Feature Engineering
- Did one-hot encoding of the categorical features "Region" and "Channel" although we will not use the features going forward in th clustering.
- Considered only the 6 numerical features of the dataset for the purpose of our project.
- Normalizing the distribution of all the product categories as ML aligorithms assume normal distribution of features.
- Scaling data in order to avoid dominance of one feature over the other as the range of values of different features were different.
### Step 4 : Clustering & PCA analysis
- Applied Kmeans Clustering to find the optimal clustering for the originally six categories of producdts using elbow method.
- Applied hierarchical clustering to find the optimal clustering for the originally six categoies of products and plot it in dendogram.
- Applied PCA analysis to identify the dimensions that best maximize the variance in the dataset.
### Step 5 : Compare all three aligorithms on their results and performance.
### Step 6 : Communicate overall insights in bullet points.
- Convey the most important insights from the EDA and both models in bullet points  to stakeholders and decision makers.

## Findings:
- 1. Noticed from the distribution plot of  the 6 product that they are not normally distributed.
- 2. From the above heatmap we noticed that there was significant relationship between Milk & Grocery, Milk & Detergent_Paper and 
at last but not least between Grocery & Detergent_Paper
- 3. The result of the Kmeans clustering show that the optimal number of clusters is 3. That means the 6 products features can be 
reduced in to three categories based on their underlying patterns and relationships.
- 4. The hierarchical as well grouped the products in to three clusters based on the dendogram plot.
- 5. The result of the PCA show that dimensions can be reduced to 3(from the 6 dimensional dataset) as the three components explain 
around 85%  of the variablity in the dataset.
- 6. Since all the results are the similar we can conclude the annual spending can be cateogrized in to three categories based on 
the underlying relationship and correlation on the product category features.

## Challenges & Future Goals:
- Focusing was difficult given that I knew I was a bit behind on my materials and preparation for the final project.
- If I had more time, I could have done more commits, improve the analysis and try more clustering aligorithms.


