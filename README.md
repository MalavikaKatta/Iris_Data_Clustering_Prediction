# 🌸 Iris Dataset Clustering Prediction using Unsupervised Machine Learning

---

## 📌 Task Description

> From the given ‘Iris’ dataset, predict the **optimum number of clusters** using an unsupervised machine learning algorithm and **represent it visually**.

---

## ✅ Tools & Technologies Used
- Python
- Jupyter Notebook
- Libraries: `pandas`, `numpy`, `matplotlib`, `scikit-learn`

---

## 🔍 Approach

1. **Data Loading**
   - Loaded the Iris dataset from `sklearn.datasets`.

2. **Data Preprocessing**
   - Converted the dataset to a DataFrame for easier handling.

3. **Finding Optimum Clusters**
   - Applied **K-Means Clustering**.
   - Used the **Elbow Method** to determine the best value of `k`.

4. **Model Training**
   - Trained the KMeans model with the optimal number of clusters (`k=3`).

5. **Visualization**
   - Visualized clusters and centroids using a scatter plot.

---

## 📊 Output

- The **Elbow curve** suggested the optimum number of clusters is **3**.
- The clusters are visualized using color-coded scatter plots.

---

## 🧠 What I Learned

- Basics of **unsupervised learning** and **K-Means Clustering**
- Use of **inertia_** and the **elbow method**
- Visualizing high-dimensional data using 2D scatter plots
