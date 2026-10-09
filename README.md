
# Customer Segmentation Using Data Analysis & Clustering

## Project Overview
This project uses data analysis and unsupervised machine learning to identify customer groups based on their transaction behavior.

## Objectives
- Analyze customer transaction data using Pandas.
- Perform exploratory data analysis and visualization.
- Calculate Recency, Frequency, and Monetary (RFM) metrics.
- Apply feature transformation and standardization.
- Use MiniBatch K-Means clustering to identify customer segments.
- Interpret the segments and propose business recommendations.

## Tools and Technologies
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook
- VS Code

## Methodology
1. Data inspection and cleaning
2. Exploratory data analysis
3. Customer-level RFM calculation
4. Log transformation and feature scaling
5. Cluster evaluation using the Elbow Method and Silhouette Score
6. MiniBatch K-Means clustering
7. Customer segment interpretation

## Results
- Unique customers analyzed: 884,265
- Number of clusters: 4
- Final silhouette score on a 10,000-customer sample: approximately 0.355

The four segments differ in transaction recency, frequency, and total transaction amount.

## Business Applications
The segmentation can help businesses explore customer engagement strategies, encourage repeat transactions, and develop targeted marketing approaches.

## How to Run
1. Clone this repository.
2. Install the required dependencies.
3. Open `customer_segmentation.ipynb` in VS Code or Jupyter Notebook.
4. Obtain the dataset separately from its authorized source.
5. Place the dataset in the project folder and run the notebook cells.

## Note
The raw dataset and customer-level CSV exports are excluded from version control. Results describe the available transaction records and may not represent customers' complete banking behavior.
