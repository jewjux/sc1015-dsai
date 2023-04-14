# SC1015 DSAI Project

## About

Our project uses [the Movie Database APIs](https://developers.themoviedb.org/3/getting-started) dataset sample. We studied the dataset and were able to identify trends and conclusions from the EDA and clustering. This led us to develop a mini recommendation tool which recommended similar movies from an input movie based on the trends identified. The following details the purpose of each script in this project.

## Scripts
| Workflow | File | Description |
| --- | --- | --- |
|1| [`data_extraction.ipynb`](data_extraction.ipynb) | Data extraction |
|2| [`data_cleaning_and_EDA.ipynb`](data_cleaning_and_EDA.ipynb) | Data visualisation and exploratory data analysis |
|3| [`kmeansclustering.ipynb`](kmeansclustering.ipynb) & [`kmodesclustering.ipynb`](kmodesclustering.ipynb) | Machine learning using KMeans and KModes |
|4| [`recommendations.ipynb`](recommendations.ipynb) | Recommendation System to generate similar movies |

## Assets
| File | Source | Description |
| --- | --- | --- |
| [`data/uncleaned_1015.csv`](data/uncleaned_1015.csv) | Local | Contains raw extracted data from the Movie Database API |
| [`data/cleaned_1015.csv`](data/cleaned_1015.csv) | Local | Contains cleaned data after processing |
| [`data/kmodes_cluster.csv`](data/kmodes_cluster.csv) | Local | Dataframe of the clustered movies using Kmodes |
| [`data/kmeans_cluster.csv`](data/kmeans_cluster.csv) | Local | Dataframe of the clustered movies using Kmeans |

## What did we learn?

* Using API for data extraction
* Using Treemap as a way of visualising data
* K means and k modes clustering algorithms

## Contributors
* @jewjux - Data Extraction, KModes Clustering
* @CelesteAng1812 - Data Cleaning and EDA, Recommendations
* @emmelynkek - Data Extraction, KMeans Clustering

## References
* [The Movie Database APIs](https://developers.themoviedb.org/3/getting-started)
* [Introduction to k-Means Clustering with scikit-learn in Python](https://www.datacamp.com/tutorial/k-means-clustering-python?utm_source=google&utm_medium=paid_search&utm_campaignid=19589720821&utm_adgroupid=143216588577&utm_device=c&utm_keyword=&utm_matchtype=&utm_network=g&utm_adpostion=&utm_creative=645433043010&utm_targetid=dsa-1947282172981&utm_loc_interest_ms=&utm_loc_physical_ms=9062504&utm_content=dsa~page~community-tuto&utm_campaign=230119_1-sea~dsa~tutorials_2-b2c_3-row-p1_4-prc_5-na_6-na_7-le_8-pdsh-go_9-na_10-na_11-na-marayc23&gclid=CjwKCAjwq-WgBhBMEiwAzKSH6GZtN-FSRi2TqpBM__wSv04-x41HMcg_UA4Q5Q1mrII-HBZgroxSiRoCDPwQAvD_BwE)
* [The k-modes as Clustering Algorithm for Categorical Data Type](https://medium.com/geekculture/the-k-modes-as-clustering-algorithm-for-categorical-data-type-bcde8f95efd7)
