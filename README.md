# Mall Customer Segmentation Using K-Means Clustering

## Introduction

This repository contains a Python script that performs customer segmentation using the K-Means Clustering algorithm on a dataset of mall customers. The dataset contains information about customers' gender, age, annual income, and spending score. The goal of the project is to group customers based on their annual income and spending score, which can help businesses understand their customer base better and develop targeted marketing strategies.
The task was performed on Google Collab.
## Dependencies

The following Python libraries are required to run the script:

- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Dataset

The dataset used in this project is the `Mall_Customers.csv` file, which contains the following columns:

- `CustomerID`: A unique identifier for each customer.
- `Gender`: The gender of the customer (Male or Female).
- `Age`: The age of the customer.
- `Annual Income (k$)`: The annual income of the customer in thousands of dollars.
- `Spending Score (1-100)`: A score assigned to the customer based on their spending habits, ranging from 1 (lowest) to 100 (highest).

## Usage

1. Clone the repository or download the source code.
2. Place the `Mall_Customers.csv` dataset in the same directory as the Python script.
3. Install the required dependencies if you haven't already.
4. Run the Python script.

The script will perform the following tasks:

1. Load the dataset into a Pandas DataFrame.
2. Explore the dataset by printing the first few rows, checking for missing values, and displaying basic information about the data.
3. Preprocess the data by selecting the relevant features (Annual Income and Spending Score) for clustering.
4. Determine the optimal number of clusters using the Elbow method and visualize the Elbow curve.
5. Train the K-Means Clustering model with the optimal number of clusters.
6. Visualize the clusters and their centroids on a scatter plot.

## Results

The script will output a scatter plot displaying the customer clusters and their centroids. Each cluster is represented by a different color, and the centroids are marked with cyan dots. The plot is labeled with the feature names (Annual Income and Spending Score) for better interpretation.

The results can be used to segment customers based on their income and spending habits, allowing businesses to tailor their marketing strategies and product offerings to specific customer groups.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## Acknowledgments 

- The dataset used in this project is provided by[(https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)].
- The project utilizes the following open-source libraries: NumPy, Pandas, Matplotlib, Seaborn, and Scikit-learn.

##License
This project is licensed under the MIT License.
