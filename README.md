Mental Health Clustering

This project analyzes the prevalence of mental illnesses across different countries and years, and performs clustering to group countries based on the rates of various mental disorders.

Dataset

The dataset used in this project is mental-illnesses-prevalence.csv. It contains information about the prevalence of five types of mental disorders:

Schizophrenia

Depressive disorders

Anxiety disorders

Bipolar disorders

Eating disorders

The dataset includes the following columns:

Column	Description
Entity	Country name
Code	Country code (some values may be missing)
Year	Year of data
Schizophrenia	Prevalence of schizophrenia
Depressive	Prevalence of depressive disorders
Anxiety	Prevalence of anxiety disorders
Bipolar	Prevalence of bipolar disorders
Eating	Prevalence of eating disorders
Project Overview

The main goals of this project are:

Data Exploration:

Display general information and statistical description of the dataset.

Visualize the distributions and correlations between different mental health disorders using plots and heatmaps.

Clustering Analysis:

Apply K-Means Clustering to group countries based on mental health disorder prevalence.

Determine the optimal number of clusters using the Elbow Method and Silhouette Score.

Apply Spectral Clustering for comparison.

Visualize the clusters with scatter plots to see how countries are grouped.

Libraries Used

pandas

numpy

matplotlib

seaborn

plotly

scikit-learn (KMeans, SpectralClustering, silhouette_score)

kneed (KneeLocator)

Usage

Clone the repository or download the files.

Install the required libraries (if not installed):

pip install pandas numpy matplotlib seaborn plotly scikit-learn kneed


Run the notebook or script to:

Load and explore the dataset.

Visualize mental health data.

Perform clustering analysis (K-Means and Spectral Clustering).

Display scatter plots showing the clusters.

Results

The Elbow Method suggested that 3 clusters are optimal for K-Means clustering.

Cluster centers provide insight into how countries group based on different mental health disorder rates.

Scatter plots illustrate the differences between countries before and after clustering.

Spectral Clustering produces comparable clustering results for validation.

Conclusion

This project demonstrates how clustering algorithms can be used to group countries based on the prevalence of mental health disorders. The analysis provides a visual and quantitative understanding of the patterns and similarities between countries regarding mental health.
