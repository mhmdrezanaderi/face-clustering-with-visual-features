# Face Clustering with Visual Features
This project aims to implement unsupervised face clustering based on visual facial features such as skin color, eye color, and other pre-encoded attributes. Working with a large-scale dataset of celebrity images (50,000 samples), the goal is to identify natural groupings among faces using clustering algorithms. The project involves feature engineering, statistical analysis, machine learning, and visualization techniques to explore, group, and evaluate facial data meaningfully.

## Key Achievements
- **Extracted facial features**: (skin and eye color) from raw images using image processing techniques.
- **Selected optimal features**: based on correlation analysis and thresholding.
- **Applied three clustering algorithms**: KMeans, DBSCAN, and MeanShift to compare their effectiveness.
- **Performed hyperparameter tuning**: to improve clustering accuracy and interpretability.
- **Visualized clusters**: using dimensionality reduction methods (PCA or t-SNE) for intuitive insights.
- **Generated heatmaps**: to highlight key attributes that differentiate each cluster.
- **Validated clustering**: by using KNN to test consistency between cluster centers and nearest data points.
- **Predicted clusters for unseen test images**: and visualized similarities with training samples.
- **Organized and saved representative images**: from each cluster for qualitative evaluation.
