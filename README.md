
# 🧠 Customer Segmentation Using RFM Analysis and Clustering

## 📌 Project Overview

This project analyzes a retail dataset to segment customers based on their purchasing behavior using RFM (Recency, Frequency, Monetary) analysis and unsupervised machine learning (K-Means clustering). The goal is to uncover customer personas and provide actionable insights for targeted marketing and retention strategies.

---

## 📁 Dataset

- **Source**: UCI Machine Learning Repository / Kaggle
- **File**: `Online Retail.xlsx`
- **Records**: ~500,000 transactions
- **Time Period**: December 2010 to December 2011
- **Fields**: InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country

---

## 🛠️ Tools & Libraries

- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- **Jupyter Notebook / Google Colab**
- **Optional**: Tableau or Power BI for dashboards

---

## 📈 Project Workflow

1. **Data Cleaning**
   - Removed null CustomerIDs
   - Removed negative quantities (returns)
   - Created `TotalPrice = Quantity * UnitPrice`

2. **RFM Feature Engineering**
   - Recency: Days since last purchase
   - Frequency: Number of unique purchases
   - Monetary: Total spending

3. **Standardization & Clustering**
   - Scaled RFM features using StandardScaler
   - Applied K-Means clustering to group customers

4. **Cluster Analysis**
   - Identified segments: Loyal, New, At-Risk, One-time buyers
   - Visualized results with boxplots and segment summaries

---

## 📊 Results & Insights

| Cluster | Description             | Strategy                      |
|---------|-------------------------|-------------------------------|
| 0       | Loyal Customers         | Loyalty rewards, upselling    |
| 1       | One-time Buyers         | Re-engagement offers          |
| 2       | At-Risk Customers       | Win-back campaigns            |
| 3       | New Customers           | Onboarding and welcome deals |

---

## 📂 Project Files

- `customer_segmentation.ipynb` – Full Python notebook
- `rfm_clustered_customers.csv` – Final segmented customer data
- `visuals/` – Charts and plots (optional)
- `Online Retail.xlsx` – Source dataset

---

## 📌 How to Run

1. Clone the repo  
   `git clone https://github.com/yourusername/customer-segmentation-rfm.git`

2. Install dependencies  
   `pip install pandas matplotlib seaborn scikit-learn`

3. Open and run `customer_segmentation.ipynb`

---

## ✨ Future Improvements

- Compare with DBSCAN / Hierarchical clustering
- Deploy as a Streamlit or Flask app
- Create an interactive Tableau dashboard

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙋‍♂️ About Me

**Parth Grewal**  
Aspiring Data Analyst | Python & SQL Enthusiast  
📧 parthgrewal2004@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/your-profile)
