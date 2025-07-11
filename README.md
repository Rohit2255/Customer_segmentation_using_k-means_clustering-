# 🧠 Customer Segmentation using K-Means Clustering and PCA

This project is part of my **#100DaysOfFinanceDataScience** challenge – **Day 6** focuses on unsupervised learning and customer segmentation.

---

## 📌 Project Objective

The goal is to identify distinct groups of credit card customers based on their spending behavior and financial profile. By clustering similar customers, businesses can tailor marketing strategies, personalize offers, and manage credit risk more effectively.

---

## 🧰 Tools & Techniques Used

- **Python**
- **Pandas, NumPy** for data handling
- **Matplotlib, Seaborn, Plotly** for visualization
- **Scikit-learn** for:
  - K-Means Clustering
  - Principal Component Analysis (PCA)
  - StandardScaler for feature normalization

---

## 🧪 Workflow

### 1. Data Preprocessing
- Loaded and cleaned the dataset.
- Handled missing values using median imputation.
- Scaled numerical features using StandardScaler.

### 2. Clustering
- Applied the **Elbow Method** to find the optimal number of clusters.
- Used **K-Means Clustering** to segment customers.

### 3. Dimensionality Reduction
- Applied **PCA** to reduce features to 2D for better visualization.

### 4. Visualization
- Created a PCA scatter plot to visualize cluster separation.
- Analyzed cluster statistics to interpret customer types.

---

## 📊 Key Insights

| Cluster | Segment Description                                                                 |
|---------|--------------------------------------------------------------------------------------|
| 0       | High balance, high cash advance users – potential risk                             |
| 1       | Low balance, low activity – dormant customers                                       |
| 2       | High purchases and transaction frequency – valuable, active users                   |
| 3       | Low purchase and credit usage – budget-conscious or new users                       |

---

## 📁 Project Structure

📦 customer-segmentation-kmeans-pca
│
├── 📁 data
│ └── CC GENERAL.csv
│
├── 📁 notebooks
│ └── customer_segmentation_kmeans.ipynb
│
├── 📁 images
│ ├── elbow_plot.png
│ └── pca_2d_plot.png
│
├── README.md


---

## 🚀 Real-World Use Cases

- **Banking**: Segment credit card customers for risk profiling and offer optimization.
- **Marketing**: Personalized campaigns based on behavioral segments.
- **Finance**: Detect unusual usage patterns or defaults early.

---

## 📌 Challenge Info

🗓️ **Day 6/100** of my `#100DaysOfFinanceDataScience` challenge  
💼 Focus: Unsupervised Learning, Clustering, PCA  
📍 Topic: Customer Segmentation with K-Means  

---

## 🔗 Connect With Me

Let's connect on [LinkedIn](https://www.linkedin.com/in/rohit-kumar-yadav-b97360194/)  
Check out more projects on [GitHub](https://github.com/rohit2255)

---



