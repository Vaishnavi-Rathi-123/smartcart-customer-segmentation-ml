# 🛒 SmartCart Customer Segmentation System

An **Unsupervised Machine Learning Project** that analyzes customer behavior and groups customers into meaningful segments using clustering algorithms.

This project demonstrates how businesses can use **data-driven insights** to improve marketing strategies, customer engagement, and customer retention.

---

## 📌 Project Overview

SmartCart is a growing e-commerce platform serving customers across multiple countries. The company collects large amounts of customer data including demographics, purchasing behavior, website activity, and marketing responses.

Currently, SmartCart applies **generic marketing strategies to all customers**, which leads to:

- Inefficient marketing campaigns  
- Missed high-value customer opportunities  
- Difficulty identifying churn-prone users  

To address this issue, this project builds a **Customer Segmentation System using Unsupervised Machine Learning**.

The system analyzes historical customer data and groups customers into **behavior-based clusters** that help businesses make better marketing decisions.

---

## 📊 Dataset Information

The dataset contains:

- **2240 customer records**
- **22 attributes**

Each record includes information such as:

- Customer demographics
- Purchase behavior
- Website engagement
- Marketing campaign responses

---

## 🧹 Data Preprocessing

Several preprocessing steps were applied before clustering.

### Data Cleaning
- Checked data types and consistency
- Removed unnecessary columns

### Feature Engineering
- Selected relevant features
- Removed redundant attributes

### Outlier Handling
- Detected and handled extreme values

### Feature Encoding
- Converted categorical variables into numerical format

### Feature Scaling
- Applied **StandardScaler** to normalize numerical features

Feature scaling is important because clustering algorithms rely on **distance-based calculations**.

---

## 📊 Exploratory Data Analysis (EDA)

EDA was performed to understand the structure of the dataset and discover patterns.

Key analysis steps included:

- Visualizing feature distributions
- Correlation analysis using a **heatmap**
- Studying relationships between customer behavior variables

These insights helped guide the clustering process.

---

## 🤖 Clustering Algorithms Used

### 1️⃣ K-Means Clustering

K-Means groups customers based on similarity in their behavior.

To determine the optimal number of clusters:

- **Elbow Method** was used
- **Silhouette Score** evaluated cluster quality

---

### 2️⃣ Agglomerative Hierarchical Clustering

Hierarchical clustering builds clusters by merging similar data points step by step.

This method helps understand **relationships between clusters at different levels**.

---

## 📈 Model Evaluation

Cluster performance was evaluated using:

- **Silhouette Score**
- Cluster separation visualization
- Interpretability of clusters

These metrics help ensure clusters are **meaningful and well-separated**.

---

## 🧠 Cluster Profiling & Business Insights

After clustering, each group of customers was analyzed to understand its characteristics.

Cluster profiling helps convert machine learning results into **practical business insights**.

### Example Customer Segments

**High Value Customers**
- High spending behavior
- Frequent purchases
- High engagement

Strategy:
- Loyalty rewards
- Premium offers
- Exclusive membership benefits

---

**Moderate Customers**
- Average spending
- Occasional purchases

Strategy:
- Personalized recommendations
- Targeted promotional campaigns

---

**Low Engagement Customers**
- Low spending
- Rare purchases

Strategy:
- Re-engagement campaigns
- Special discounts

---

**New / Occasional Customers**
- Limited purchase history

Strategy:
- Welcome offers
- Product discovery recommendations

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 💡 Key Learnings

Through this project I learned:

- How **unsupervised learning discovers hidden patterns**
- Importance of **data preprocessing for clustering**
- Techniques to determine the **optimal number of clusters**
- How to convert machine learning output into **business insights**

---

## 👩‍💻 Author

**Vaishnavi Rathi**

