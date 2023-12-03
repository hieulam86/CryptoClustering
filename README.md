# CryptoClustering

1. I commence the process by employing the elbow curve technique with normalized data to determine the ideal k value for the K-Means model, which will utilize all the original features in the dataset.
![Elbow_original](https://github.com/hieulam86/CryptoClustering/assets/132635473/f526eae0-5872-4e3f-ade4-640b5f2df744)

   Subsequently, with the identified optimal k value, I proceed to train and predict the K-Means model, resulting in the creation of four clusters for cryptocurrencies. The inertia within each cluster proved substantial, prompting consideration for the reduction of features.
![Scatter_original](https://github.com/hieulam86/CryptoClustering/assets/132635473/7bd9b252-e05a-4ed9-bd37-de1270749cfa)

3. To trim down the number of utilized features, I implemented Principal Component Analysis (PCA) to establish three primary clusters.
![Elbow_pca](https://github.com/hieulam86/CryptoClustering/assets/132635473/f34b0b24-4562-4bb1-968a-efbf95f8f0f3)

    Ultimately, armed with the optimal k value for the PCA features, I proceed to visualize the newly formed clusters through plotting.
![Scatter_pca](https://github.com/hieulam86/CryptoClustering/assets/132635473/26d4086a-6c93-4cb1-a511-9c06e67029af)

## Results and Visualizations
  Elbow curves and cluster visualizations are available in the Jupyter Notebooks for both original and PCA-transformed data.

## Conclusion
  Analyze the impact of using fewer features through visual comparisons.
  Make observations on cluster separation, data compression, outliers, and computational efficiency.
