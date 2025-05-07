# CryptoClustering
This project applies K-Means clustering and Principal Component Analysis (PCA) to group cryptocurrencies based on their price fluctuations over time.

### Overview
The goal is to identify natural groupings of cryptocurrencies by examining their price changes across multiple timeframes, including:
24 hours

7 days

14 days

30 days

60 days

200 days

1 year

We use clustering techniques to better understand how different coins behave and whether they follow similar trends.

### Methods
Data Normalization using StandardScaler
K-Means Clustering on original scaled data
Elbow Method to determine optimal k
Principal Component Analysis (PCA) to reduce dimensionality to 3 features
K-Means Clustering repeated on PCA data
Scatter Plots to visualize clusters
PCA Loadings analyzed to understand feature influence

### Files
Crypto_Clustering.ipynb: Main notebook containing all analysis
crypto_market_data.csv: Input dataset
README.md: Project overview
### Results
Best number of clusters: 4
PCA revealed that long-term and short-term trends influence different components
PCA-based clustering produced similar groupings with fewer features

### Requirements
Python 3.x

pandas

scikit-learn

matplotlib

