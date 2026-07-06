# Smart-cart-customer-segmentation

# 🛒 SmartCart Customer Segmentation

An end-to-end **Machine Learning** project that segments SmartCart customers based on their demographic information, purchasing behavior, and marketing campaign responses. Using **K-Means Clustering**, the project identifies groups of similar customers, helping businesses create targeted marketing strategies and improve customer engagement.

---

## 📌 Project Objectives

- Clean and preprocess raw customer data.
- Perform feature engineering to create meaningful variables.
- Encode and scale data for machine learning.
- Apply K-Means clustering to identify customer segments.
- Generate datasets ready for business analysis and visualization.

---

## 📂 Dataset

The dataset contains customer information such as:

- Demographics (Age, Education, Marital Status)
- Income
- Product spending
- Purchase behavior
- Campaign responses
- Website visits

---

## 🔄 Project Workflow

1. **Data Cleaning**
   - Handled missing values
   - Removed unnecessary columns
   - Treated outliers
   - Checked duplicates

2. **Feature Engineering**
   - Created Age and Total Spending features
   - Simplified Education levels
   - Grouped Marital Status into `Living_With`

3. **Data Preprocessing**
   - One-Hot Encoding for categorical features
   - Feature Scaling using StandardScaler

4. **Exploratory Data Analysis**
   - Analyzed customer demographics
   - Visualized spending patterns and feature relationships

5. **Customer Segmentation**
   - Applied K-Means Clustering
   - Assigned cluster labels to each customer
   - Exported the final clustered dataset

---

## 📁 Project Structure

```
SmartCart-Customer-Segmentation/
│
├── smartcart_customers.csv      # Original dataset
├── Cleaned Smartcart.csv        # Cleaned dataset
├── Encoded Smartcart.csv        # Encoded dataset
├── With Cluster.csv             # Dataset with cluster labels
├── Smartcart.ipynb              # Complete project notebook
├── README.md
└── requirements.txt
```

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📈 Results

This project successfully:

- Prepared raw customer data for machine learning.
- Engineered meaningful features to improve analysis.
- Segmented customers into distinct groups using K-Means.
- Produced clean, encoded, and clustered datasets for business decision-making.

---

## 🚀 Future Improvements

- Compare multiple clustering algorithms (DBSCAN, Agglomerative Clustering, Gaussian Mixture Models).
- Evaluate clusters using Silhouette Score and Davies-Bouldin Index.
- Use PCA or t-SNE for cluster visualization.
- Build an interactive dashboard using Streamlit or Power BI.
- Deploy the project as a web application.

---

## 📚 Skills Demonstrated

- Data Cleaning & Preprocessing
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Feature Encoding & Scaling
- Unsupervised Machine Learning
- Customer Segmentation
- Business Analytics

---

## ▶️ Getting Started

```bash
git clone https://github.com/yourusername/SmartCart-Customer-Segmentation.git

cd SmartCart-Customer-Segmentation

pip install -r requirements.txt

jupyter notebook
```

Open **`Smartcart.ipynb`** and run all cells to reproduce the analysis.

---



This project was developed as part of a machine learning portfolio to demonstrate practical skills in data preprocessing, customer segmentation, and business analytics.

⭐ *If you found this project useful, consider giving it a star on GitHub!*
