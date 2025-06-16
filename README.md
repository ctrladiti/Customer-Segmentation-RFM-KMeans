# Customer Segmentation with RFM and K-Means Clustering

This project performs customer segmentation on the UK-based Online Retail dataset using **RFM (Recency, Frequency, Monetary)** analysis and **K-Means Clustering**. Visual insights are provided via a custom **Power BI Dashboard**.

---

## 📌 Problem Statement
To group customers into distinct segments based on their purchasing behavior to enable targeted marketing and retention strategies.

---

## 📊 Data Source
- Dataset: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Online+Retail)
- Transactions from a UK-based online retailer from 2010-2011

---

## ⚙️ Methodology

1. **Data Cleaning**: Handled missing values, canceled orders, and filtered UK customers.
2. **RFM Calculation**:
   - Recency: Days since last purchase
   - Frequency: Number of purchases
   - Monetary: Total amount spent
3. **Standardization**: Scaled the RFM scores for clustering.
4. **K-Means Clustering**:
   - Used Elbow Method to select `k=4`
   - Applied KMeans to assign Cluster Labels
5. **Power BI Dashboard**:
   - Visualized segment-wise metrics: average RFM, count, distribution, monetary contribution.

---

## 📈 Results

- **Segment 3**: High frequency & high spend – loyal top customers.
- **Segment 1**: Majority segment with low monetary value.
- **Segment 2**: Repeat buyers with moderate frequency and spending.
- **Segment 0**: Least engaged segment.

---

## 🖥️ Dashboard Preview

![Dashboard](powerbi_dashboard/dashboard_screenshot.png)

> Built using Power BI, includes KPIs, pie chart, scatter plot, treemap, and bar charts.

---

## 📁 Files in This Repo

| File | Description |
|------|-------------|
| `Customer_seg.ipynb` | Jupyter notebook with all steps |
| `OnlineRetail.csv` | Dataset |
| `dashboard_screenshot.png` | Dashboard preview |
| `Customer_Segmentation_Dashboard.pbix` | Power BI dashboard |
| `requirements.txt` | Python packages |

---

## 🚀 How to Run

```bash
# Clone the repo
git clone https://github.com/your-username/Customer-Segmentation-RFM-KMeans.git
cd Customer-Segmentation-RFM-KMeans

# (Optional) Create a virtual environment
python -m venv venv
source venv/bin/activate  # or .\venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt

# Open Jupyter notebook
jupyter notebook notebook/Customer_seg.ipynb

```

---

## 🧑‍💻 4. **Portfolio Website Structure**

### 📁 Project Card or Section:

#### 🧾 Title:
**Customer Segmentation using RFM and Clustering**

#### 📄 Description:
> Leveraged RFM model and K-Means clustering to segment customers based on purchasing behavior from a retail dataset. Delivered actionable insights using a professional Power BI dashboard highlighting key customer segments, purchase trends, and revenue distribution.

#### 🔗 Buttons or Links:
- 🔍 **View Notebook** → link to GitHub `Customer_seg.ipynb`
- 📊 **View Dashboard** → link to Power BI screenshot or embed
- 🌐 **View GitHub Repo** → link to full repository

#### 🖼️ Preview:
- Add your dashboard screenshot thumbnail
- Include one sample cluster plot or heatmap if available

---

## 🧾 5. **requirements.txt (Sample)**

```txt
pandas
matplotlib
seaborn
scikit-learn
jupyter
```


