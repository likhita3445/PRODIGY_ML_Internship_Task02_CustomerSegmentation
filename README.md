# PRODIGY_ML_Internship_Task02_CustomerSegmentation
Customer segmentation using K-Means Clustering based on annual income and spending score.

# Prodigy InfoTech ML Internship – Task 02

## Customer Segmentation using K-Means Clustering

This project is completed as part of my **Machine Learning Internship at Prodigy InfoTech**.

### 📌 Project Overview

The objective of this task is to segment mall customers into different groups based on their **Annual Income** and **Spending Score** using the **K-Means Clustering** algorithm.

Customer segmentation helps businesses understand customer behavior and create suitable marketing strategies for different customer groups.

### 📊 Dataset

The project uses the **Mall Customers Dataset** containing information about:

* Customer ID
* Gender
* Age
* Annual Income (k$)
* Spending Score (1–100)

### 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Google Colab

### 🔍 Steps Performed

1. Loaded the Mall Customers dataset
2. Explored the dataset and checked for missing values
3. Selected Annual Income and Spending Score as features
4. Applied the **Elbow Method** to determine the suitable number of clusters
5. Applied **K-Means Clustering**
6. Divided customers into **5 clusters**
7. Visualized the customer segments
8. Analyzed the average characteristics of each cluster
9. Saved the clustered dataset as a CSV file

### 📈 Cluster Analysis

The model divided the 200 customers into five clusters:

| Cluster | Annual Income | Spending Score | Customer Group                      |
| ------- | ------------: | -------------: | ----------------------------------- |
| 0       |        55.30k |          49.52 | Average income and average spending |
| 1       |        86.54k |          82.13 | High income and high spending       |
| 2       |        25.73k |          79.36 | Low income and high spending        |
| 3       |        88.20k |          17.11 | High income and low spending        |
| 4       |        26.30k |          20.91 | Low income and low spending         |

### 👥 Customer Distribution

* Cluster 0 → 81 customers
* Cluster 1 → 39 customers
* Cluster 2 → 22 customers
* Cluster 3 → 35 customers
* Cluster 4 → 23 customers

### 📁 Project Files

* `Task_02_Customer_Segmentation.ipynb` – Complete notebook containing code, outputs, and visualizations
* `Mall_Customers_Clustered.csv` – Dataset with assigned cluster labels
* `README.md` – Project documentation

### 🎯 Conclusion

K-Means Clustering successfully grouped the mall customers into different segments based on their annual income and spending behavior. These segments can help businesses understand customer patterns and develop targeted marketing strategies.

### 📚 Learning Outcome

Through this task, I gained practical experience in **K-Means Clustering, the Elbow Method, data visualization, feature selection, customer segmentation, and cluster analysis**.

### 👩‍💻 Internship

**Machine Learning Internship – Prodigy InfoTech**

Task: **02 – Customer Segmentation using K-Means Clustering**
