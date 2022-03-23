Requirements

1. Objective: my Capstone project aims to provide recommendations for which cryptocurrencies to invest in. 
An investor can either find another cryptocurrency similar to what they already have in their portfolio, 
or they can find a cryptocurrency distinct from what they have already invested in, as a diversifying investment strategy.

2. Data Ingestion: data about crypocurrencies are obtained from the free tier CoinGecko API. 
The data were then preprocessed before passing onto the machine learning algorithm in step 4.

3. Visualizations: low dimensional projection of the feature space was computed using t-SNE and plotted as a scatterplot. 
A second type of visualization is the lineplots for 30-day historical prices of the trending coins.

4a. Machine Learning: unsupervised learning was used. Specifically, the clustering method, DBSCAN, 
was used to find different clusters of cryptocurrencies. The model also identifies outliers from 
all the cryptocurrencies available on CoinGecko.com. NLP was used on text based features, 
such as description of a coin or its hashing algorithm and platform.

5. Deliverable: The deliverable of this project takes on the form of Jupyter notebooks.
