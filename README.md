# Second-Hand Car Sales Data Analysis with Supervised and Unsupervised Learning

This project explores a mock dataset of second-hand car sales in the UK using both supervised and unsupervised machine learning techniques. The objective is two-fold: to accurately predict car prices using 
regression models, and to discover meaningful clusters within the data using k-means and hierarchical clustering.

---

## Techniques Used

### 🔹 Supervised Learning:
- **Linear Regression** with individual features (engine size, mileage, year)
- **Polynomial Regression** for improved price prediction
- **Random Forest Regressor** using full feature set (numerical + one-hot encoded categorical)
- **Artificial Neural Networks (ANN)** with dropout regularization and hyperparameter tuning

### 🔹 Unsupervised Learning:
- **KMeans Clustering**: Applied to various feature combinations with silhouette & Davies-Bouldin scores
- **Hierarchical Clustering**: Using Agglomerative Clustering for comparison and evaluation

---

## Dataset

- A mock dataset with **50,000 rows** simulating UK second-hand car listings
- Features include:
  - Manufacturer, Model, Engine Size, Fuel Type, Year, Mileage, and Price
- Dataset is preprocessed using scaling and one-hot encoding as needed

---

## Tools & Libraries

- Python, pandas, NumPy, seaborn, matplotlib
- scikit-learn (regression, classification, clustering)
- TensorFlow/Keras (for ANN model)
- imbalanced-learn (for sampling, if needed)

---

## 🚀 How to Run

1. Clone the repo:
```bash
git clone https://github.com/yourusername/second-hand-car-sales-analysis.git
