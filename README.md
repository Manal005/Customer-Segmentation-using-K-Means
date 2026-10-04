# Customer Segmentation using K-Means

##  Project Overview

This project applies the **K-Means Clustering** algorithm to segment mall customers into different groups based on their:

* Annual Income
* Spending Score

The goal is to identify groups of customers with similar spending behavior and income levels.

##  Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Google Colab

##  Dataset

The project uses the **Mall Customers Dataset**, which contains information about mall customers.

The main features used for clustering are:

* `Annual Income (k$)`
* `Spending Score (1-100)`

##  Project Steps

1. Upload the dataset.
2. Load the dataset using Pandas.
3. Explore the dataset using:

   * `head()`
   * `shape`
   * `info()`
   * `isnull().sum()`
4. Visualize the customers before applying K-Means.
5. Select the features used for clustering.
6. Apply the K-Means algorithm with 5 clusters.
7. Predict the cluster assigned to each customer.
8. Visualize the resulting clusters and their centroids.
9. Count the number of customers in each cluster.

##  Visualization

The project includes visualizations showing:

* Customer distribution before clustering.
* Customer clusters after applying K-Means.

##  Output

The program prints:

* The coordinates of the cluster centroids.
* The number of customers in each cluster.

##  How to Run

### Using Google Colab

1. Open the notebook in Google Colab.
2. Run the cells in order.
3. Upload `Mall_Customers.csv` when requested.
4. The clustering results and visualizations will be displayed.

### Using Jupyter Notebook

Install the required libraries:

```bash
pip install pandas numpy matplotlib scikit-learn scipy
```

Then open and run the notebook.

##  Project Structure

```text
K-Means-Customer-Segmentation/
│
├── kmeans.ipynb
├── Mall_Customers.csv
└── README.md
```

##  Objective

The main objective of this project is to practice **unsupervised machine learning** using K-Means and understand how clustering can be used for customer segmentation.

