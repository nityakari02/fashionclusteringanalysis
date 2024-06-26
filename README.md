# Clustering Fashion Retail Sales Data

## Project Description

This project focuses on performing a clustering analysis on fashion retail sales data to uncover patterns in customer satisfaction based on purchase amounts. The primary goal is to identify whether the satisfaction ratings of customers cluster into meaningful groups based on the amount they spend. By exploring these clusters, we aim to gain insights into customer behavior and the relationship between purchase amounts and satisfaction levels.

## Project Components

1. **R Markdown File (ClusteringAnalysisFashion.Rmd):** 
   This file contains the complete R code used for the clustering analysis. It includes sections for loading and preparing the dataset, performing the clustering analysis using k-means, and visualizing the results.

2. **CSV Data File (Fashion_Retail_Sales.csv):**
   The dataset consists of sales transactions from a fashion retail store. It includes variables such as the type of clothing item purchased, the purchase amount in USD, the date of purchase, customer satisfaction levels, and payment method.

3. **PDF Report (ClusteringAnalysisFashion.pdf):**
   A comprehensive report that summarizes the findings of the clustering analysis. It includes visualizations and discussions on the results.

4. **Alternate R Markdown File (ClusteringAnalysisFashion.Rmd):**
   Another version of the R Markdown file for the clustering analysis, providing additional perspectives or methods used in the analysis.

## Research Question

The core research question driving this analysis is: *"Does the customer satisfaction rating, based on the purchase amount, cluster into meaningful groups?"* The investigation aims to explore if higher purchasing amounts correlate with higher satisfaction ratings.

## Analysis Steps

- **Data Loading:** The dataset is loaded into R and essential packages for clustering and visualization are imported.
- **Data Wrangling:** Relevant variables are selected, renamed, and cleaned to prepare for analysis.
- **Clustering Analysis:** K-means clustering is performed to group the data into clusters based on purchase amount and satisfaction rating. The optimal number of clusters is determined using the elbow method and silhouette method.
- **Visualization:** The clustering results are visualized to interpret and understand the patterns and relationships within the data.
- **Discussion:** The findings are discussed, highlighting the significance of the clusters and the implications for customer satisfaction.

## Technologies and Skills Used

- **Programming Languages:** R
- **Libraries and Packages:**
  - **Data Manipulation and Wrangling:**
    - `tidyverse`: Comprehensive collection of packages for data manipulation and wrangling.
  - **Clustering Analysis:**
    - `cluster`: For performing clustering analysis.
    - `NbClust`: For determining the optimal number of clusters.
    - `aricode`: For additional clustering metrics.
  - **Visualization:**
    - `factoextra`: For visualizing clustering results.
    - `ggplot2`: For creating detailed and customized data visualizations.
- **Data Analysis Skills:** 
  - Data wrangling and preprocessing.
  - Clustering analysis using k-means.
  - Determining the optimal number of clusters.
  - Data visualization and interpretation.
- **Tools:** RStudio for coding and analysis, GitHub for version control and project sharing.

## Requirements

- R
- R libraries: factoextra, cluster, NbClust, tidyverse, ggplot2, aricode

## How to Run

To replicate the analysis, open the `KARI_NITYA_Assignment-4.Rmd` or `ClusteringAnalysisFashion.Rmd` file in RStudio and knit the document. Ensure that the necessary R libraries are installed.

## Results

The analysis aims to reveal whether there is a significant relationship between the amount customers spend and their satisfaction levels. By clustering these variables, we seek to provide actionable insights into customer behavior in the fashion retail sector.
