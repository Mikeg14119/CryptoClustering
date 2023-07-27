### CryptoClustering

Introduction


This repository contains a Python project focused on cryptocurrency clustering using unsupervised learning techniques. The main goal is to predict if cryptocurrencies are affected by 24-hour or 7-day price changes. This ReadMe provides an overview of the project, including installation instructions, data preprocessing, model building, and visualizations.


Prerequisites


To run this project, you'll need the following installed on your machine:

Python

Jupyter Notebook or JupyterLab

Required Python libraries: pandas, hvplot, scikit-learn, numpy, holoviews


You can install the required Python libraries using pip:

pip install pandas hvplot scikit-learn numpy holoviews


Getting Started


Follow these steps to get the project up and running on your local machine:

Clone the repository:

git clone https://github.com/Mikeg14119/CryptoClustering.git

cd <repository_folder>

Install the required libraries, if not already installed, using the command provided above.


Run Jupyter Notebook or JupyterLab:

jupyter notebook

Open the "crypto_clustering.ipynb" file in Jupyter and follow the instructions.


Project Structure

crypto_clustering.ipynb: The main Jupyter Notebook containing the code for data processing, model building, and visualizations.

Resources: Folder containing the input data file "crypto_market_data.csv".

README.md: The ReadMe file you are currently reading.


Data


The input data is stored in the "crypto_market_data.csv" file located in the "Resources" folder. The dataset contains daily price change percentages for various cryptocurrencies. Columns include "price_change_percentage_24h", "price_change_percentage_7d", "price_change_percentage_14d", "price_change_percentage_30d", "price_change_percentage_60d", "price_change_percentage_200d", and "price_change_percentage_1y".


Data Preprocessing


The data preprocessing steps include:

Loading the data into a Pandas DataFrame

Normalizing the data using StandardScaler

Applying Principal Component Analysis (PCA) for dimensionality reduction


Model Building

The project uses K-means clustering algorithm for grouping cryptocurrencies based on their price change percentages. The optimal number of clusters (k) is determined using the Elbow method for both the original data and the data reduced by PCA.


Visualizations

The project includes visualizations to better understand the data and clustering results. It includes line plots, scatter plots, and elbow curves.


Conclusion

The Crypto Clustering project aims to group cryptocurrencies based on their price change percentages. By utilizing unsupervised learning techniques like K-means clustering and PCA, it provides valuable insights into the behavior of cryptocurrencies. The ReadMe and Jupyter Notebook provide a step-by-step guide to recreate the results and visualize the clustering patterns.

Feel free to explore and experiment with the project to gain deeper insights into the cryptocurrency market!
