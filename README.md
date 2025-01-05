## Principal Component Analysis and K-Means Clustering of Dow Jones Stocks

Overview

This data science project performs an in-depth analysis of one year of daily stock returns from the Dow Jones Industrial Average (DJIA). Using Principal Component Analysis (PCA) and K-Means clustering, The undertakings are:

Analyze and visualize the principal components to understand the underlying structure of the data.

Perform K-Means clustering to group stocks based on dissimilarity.

Visualize the clustering results, including a graph showing the three cluster outputs.

The project utilizes the yfinance library to source stock data and employs powerful Python libraries like pandas, numpy, matplotlib, sklearn, and scipy for analysis and visualization.

Features

Data Sourcing: Fetches historical daily stock prices for one year using yfinance.

Preprocessing: Computes daily returns from the stock prices.

PCA Analysis:

Identifies the most significant components that explain variance in stock returns.

Visualizes the explained variance and the principal components.

K-Means Clustering:

Uses a dissimilarity metric to group stocks.

Creates clusters for visualization and analysis.

Visualization:

PCA results (e.g., scree plot, biplots).

K-Means clustering outputs with clearly labeled clusters.

Graph displaying the 3-cluster breakdown of Dow Jones stocks.

Dependencies

The project requires the following Python libraries:

yfinance: For sourcing historical stock data.

pandas: For data manipulation and preprocessing.

numpy: For numerical computations.

matplotlib: For data visualization.

scikit-learn: For PCA and K-Means clustering.

scipy: For advanced mathematical functions and distance calculations.
