# Customer Segmentation for an E-commerce Platform

This project uses transaction data from an online retail store to segment customers using the RFM (Recency, Frequency, Monetary) model and K-Means clustering. The goal is to help the business understand customer value and tailor marketing strategies.

## 🔍 Problem Statement

Identify different customer groups based on their shopping behavior to:

- Improve targeted marketing
- Personalize offers
- Boost customer retention

## 📊 Dataset

[Kaggle: Online Retail Customer Clustering](https://www.kaggle.com/datasets/hellbuoy/online-retail-customer-clustering)

## 🧰 Tools & Technologies

- Python (Pandas, Matplotlib, Scikit-learn, Seaborn)
- K-Means Clustering, PCA
- Power BI (for dashboard)

## 🧮 Methodology

1. **Data Cleaning**: Handled nulls, removed canceled orders
2. **Feature Engineering**: Built RFM table
3. **Normalization**: Used `StandardScaler`
4. **Clustering**: K-Means with Elbow method for k selection
5. **Visualization**: Scatter plots and Power BI dashboard
6. **Dashboard**: Key metrics, customer counts, RFM segment averages, cluster treemaps

## 📊 Dashboard Snapshot

![Dashboard](images/dashboard.png)

## 📁 File Structure

- `Customer_seg.ipynb`: Notebook with data preprocessing, clustering, and plots
- `images/`: Dashboard and visualizations
- `PowerBi_Dashboard/`: PBIX file for Power BI (optional)
- `requirements.txt`: Python packages

## 💡 Key Insights

- Most customers fall into Segment 1 (high frequency, low monetary)
- Segment 3 contains high-value but infrequent customers
- Recency varies heavily by cluster, indicating loyalty differences

## 📜 License

This project is for educational and demo purposes. Dataset © its original owner (see Kaggle link).
