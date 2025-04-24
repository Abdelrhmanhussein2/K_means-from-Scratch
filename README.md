
# 🧠 K-Means Clustering on Mall Customers Dataset

This project implements the **K-Means clustering algorithm** on the popular "Mall Customers" dataset. The goal is to segment customers into distinct groups based on their behavior and spending score.

## 📁 Dataset

- **Source**: [Mall_Customers.csv - Kaggle](https://www.kaggle.com/vjchoudhary7/customer-segmentation)
- **Attributes**:
  - CustomerID
  - Gender
  - Age
  - Annual Income (k$)
  - Spending Score (1-100)

## 🧪 Project Structure

- **Preprocessing**:
  - Handling and visualizing the data
  - Feature scaling using `StandardScaler`
  - Dimensionality reduction using `PCA` (for visualization)

- **Clustering**:
  - Implemented **from scratch** without using `KMeans` from `sklearn`
  - Elbow Method to determine the optimal number of clusters
  - Cluster visualization in 2D (PCA)

- **Visualization Tools**:
  - Matplotlib
  - Seaborn

## 🧰 Libraries Used

```python
Numpy
Pandas
Matplotlib
Seaborn
Sklearn
```

## 📊 Sample Output

- Elbow plot to determine optimal `k`
- 2D scatter plot of customer clusters (after PCA)
- Cluster analysis with color coding

## 🚀 How to Run

1. Download the dataset from Kaggle and place it in the appropriate path (`/kaggle/input/mall-customers/`).
2. Open the notebook `K_means.ipynb`.
3. Run all cells to see clustering in action.

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
