# 🛍 Customer Segmentation Using K-Means Clustering

> A Machine Learning project developed using the K-Means Clustering algorithm to segment customers into different groups based on their annual income and spending behavior.
---

# 👨‍💻 Developer Information

**Student Name:** Tanushree Kotamkar

**Roll Number:** 119

**College:** Priyadarshani College Of Engineering, Nagpur

**Department:** Industrial Internet Of Things

**Academic Year:** 2025–2026

---

# 📌 Project Overview

This project demonstrates the implementation of the K-Means Clustering algorithm using Python and Jupyter Notebook. The primary objective is to segment customers into distinct groups based on their annual income and spending behavior.

The project follows the complete machine learning pipeline, including data loading, data preprocessing, exploratory data analysis (EDA), feature selection, cluster formation, visualization, and cluster analysis.

The implementation is intended for educational purposes and demonstrates how unsupervised machine learning techniques can discover hidden patterns and customer segments from structured datasets without using predefined target labels.
---

# 🎯 Project Objectives

- Understand the K-Means Clustering algorithm.
- Implement K-Means Clustering using Python.
- Perform data preprocessing and exploratory data analysis (EDA).
- Identify the optimal number of clusters using the Elbow Method.
- Segment customers based on annual income and spending score.
- Visualize customer clusters using scatter plots.
- Analyze customer behavior and characteristics within each cluster.
- Demonstrate an end-to-end unsupervised machine learning workflow.

---

# 🛠 Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
---


    # 🏗 Project Architecture

```
                Dataset
                   │
                   ▼
          Data Collection
                   │
                   ▼
        Data Preprocessing
                   │
                   ▼
        Exploratory Data Analysis
                   │
                   ▼
          Feature Selection
                   │
                   ▼
            Elbow Method
                   │
                   ▼
        K-Means Clustering
        ┌──────────────────────┐
        │ Cluster Initialization │
        │ Distance Calculation   │
        │ Cluster Assignment     │
        │ Centroid Update        │
        └──────────────────────┘
                   │
                   ▼
         Cluster Visualization
                   │
                   ▼
          Cluster Analysis
                   │
                   ▼
      Customer Segmentation
```

---
# 🔄 Project Workflow

### Step 1 – Data Collection

The Mall Customers dataset is loaded into the notebook for analysis.

↓

### Step 2 – Data Cleaning

- Check missing values
- Check duplicate records
- Prepare a clean dataset

↓

### Step 3 – Data Preprocessing

- Select relevant features
- Handle categorical and numerical data
- Prepare data for clustering

↓

### Step 4 – Exploratory Data Analysis (EDA)

- Analyze customer demographics
- Visualize data using histograms and count plots
- Generate a correlation heatmap

↓

### Step 5 – Feature Selection

The following features are selected for clustering:

- Annual Income (k$)
- Spending Score (1–100)

↓

### Step 6 – Finding the Optimal Number of Clusters

The Elbow Method is used to determine the optimal number of clusters.

↓

### Step 7 – K-Means Clustering

The K-Means algorithm groups customers into different clusters based on similar characteristics.

↓

### Step 8 – Cluster Visualization

Customer clusters are visualized using scatter plots, and cluster centers are identified.

↓

### Step 9 – Cluster Analysis

Each customer segment is analyzed to understand spending behavior and income patterns.
---

# 📂 Project Structure

```
Customer-Segmentation-KMeans/
│
├── Customer_Segmentation_KMeans.ipynb
├── Mall_Customers.csv
├── customer_segmentation_kmeans.pkl
├── README.md
├── outputs/
│   ├── histogram.png
│   ├── countplot.png
│   ├── heatmap.png
│   ├── elbow_method.png
│   └── cluster_visualization.png
└── requirements.txt
```
```

---

# 🛍 K-Means Clustering Architecture

```
          Customer Dataset
                 │
                 ▼
        Input Features
 (Annual Income, Spending Score)
                 │
                 ▼
        Feature Selection
                 │
                 ▼
         Elbow Method
 (Find Optimal Number of Clusters)
                 │
                 ▼
      K-Means Clustering Algorithm
                 │
        ┌────────┴────────┐
        ▼                 ▼
  Cluster Assignment   Centroid Update
        │                 │
        └────────┬────────┘
                 ▼
        Customer Segments
                 │
                 ▼
      Cluster Visualization
```

---
# ⚙ Key Features

- Data preprocessing
- Exploratory Data Analysis (EDA)
- Customer data visualization
- Feature selection for clustering
- Elbow Method to determine the optimal number of clusters
- K-Means Clustering implementation
- Customer segmentation based on income and spending score
- Cluster visualization using scatter plots
- Cluster center analysis
- Model saving using Joblib
- Complete Unsupervised Machine Learning workflow

---

# 💡 Key Skills Demonstrated

- Python Programming
- Machine Learning
- Unsupervised Learning
- K-Means Clustering
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Selection
- Customer Segmentation
- Data Visualization
- Cluster Analysis
- Model Saving with Joblib
- Problem Solving

---

# 📊 Expected Outputs

- Cleaned and preprocessed dataset
- Exploratory Data Analysis (EDA) visualizations
- Elbow Method graph for optimal cluster selection
- Customer segmentation using K-Means Clustering
- Cluster visualization with scatter plots
- Cluster centroids and customer group analysis
- Saved K-Means model (`customer_segmentation_kmeans.pkl`)
- Insights into customer purchasing behavior

---

# 📈 Future Improvements

- Optimize the number of clusters using advanced evaluation techniques
- Apply feature scaling for improved clustering performance
- Use larger and more diverse customer datasets
- Compare K-Means with other clustering algorithms such as Hierarchical Clustering and DBSCAN
- Build an interactive customer segmentation dashboard
- Deploy the clustering model using Flask or FastAPI
- Integrate the project into a web application for real-time customer segmentation
---

# 📚 Learning Outcomes

Through this project, the following concepts were explored:

- Machine Learning fundamentals
- Artificial Neural Networks
- Data preprocessing
- Model optimization
- Deep learning workflow
- Performance evaluation

---
# 📚 Learning Outcomes

Through this project, the following concepts were explored:

- Machine Learning fundamentals
- Unsupervised Learning
- K-Means Clustering algorithm
- Data preprocessing
- Exploratory Data Analysis (EDA)
- Feature selection for clustering
- Customer segmentation techniques
- Cluster visualization and interpretation
- Model saving using Joblib
- Complete Unsupervised Machine Learning workflow

---

# 📄 License

This project is created for academic and educational purposes.

---

# 🙏 Acknowledgement

I sincerely thank my faculty members, department, and college for their continuous guidance and support throughout the development of this project. This work provided me with practical knowledge of K-Means Clustering, Unsupervised Machine Learning, Data Preprocessing, Exploratory Data Analysis (EDA), and Customer Segmentation techniques. It also enhanced my understanding of applying machine learning algorithms to solve real-world business problems.
---

⭐ If you found this project useful, consider giving it a star on GitHub.
