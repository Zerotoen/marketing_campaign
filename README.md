# Marketing Campaign Analysis

This project analyzes a marketing campaign dataset using various data preprocessing, visualization, and clustering techniques. The dataset contains information about customers and their responses to different marketing campaigns. The analysis aims to gain insights into customer demographics and preferences to tailor future marketing campaigns.

## Dataset

The dataset used in this analysis is called marketing_campaign.csv. It contains information about customer demographics, such as age, income, and marital status, as well as their purchasing behavior and responses to marketing campaigns.

## Dependencies

This project uses the following Python libraries:

- pandas
- numpy
- seaborn
- pymrmr
- matplotlib
- datetime
- scipy
- yellowbrick
- sklearn

## Data Preprocessing

The data is first read into a pandas DataFrame and preprocessed to remove any inconsistencies or missing values. Several new features are also created, such as Be_Customer, Spent, Children, and Parent. The dataset's categorical variables are then encoded using label encoding.

## Data Visualization

Various visualizations are used to explore the dataset, including pie charts, bar plots, and box plots. These visualizations help identify patterns, trends, and potential outliers in the data.

## Feature Engineering

The dataset is then subjected to feature engineering using the Box-Cox transformation to remove skewness from the data. Outliers are removed from the dataset using the interquartile range (IQR) method.

## Principal Component Analysis

Principal Component Analysis (PCA) is performed to reduce the dataset's dimensionality. The first three principal components are visualized using a 3D scatter plot.

## Clustering

The KMeans clustering algorithm is applied to the dataset to identify customer segments. The optimal number of clusters is determined using the elbow method. The resulting clusters are visualized using a 3D scatter plot.

## Evaluation Metrics

The quality of the clustering is assessed using the silhouette score and inertia.

## Cluster Analysis

The original dataset is grouped by the assigned cluster labels, and the median values of each feature are calculated for each cluster. Box plots of each feature by cluster are created to visualize the differences between the clusters.

To view the complete code and visualizations, please refer to the attached Jupyter Notebook file.

## File Structure

- .ipynb_checkpoints: Jupyter Notebook checkpoints
- csv: Folder containing the CSV dataset
- photo: Folder containing visualization images
- Customer Marketing(K-means).ipynb: Jupyter Notebook file with the complete code and visualizations
- README.md: This file with the project description
