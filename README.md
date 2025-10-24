# Cohort-Analysis-Customer-Segmentation-using-RFM-and-K-Means

> 🚀 Data-Driven Customer Analytics | RFM Scoring | K-Means Clustering | Cohort Retention Analysis

---

## 📘 Project Overview

This project focuses on **analyzing customer behavior** using **RFM (Recency, Frequency, Monetary)** metrics and **Cohort Analysis** to understand **retention trends** and **segment customers** for targeted business strategies.  

It combines **data analytics**, **machine learning**, and **business intelligence** concepts to extract actionable insights that support **customer retention**, **personalization**, and **marketing optimization**.

---

## 🎯 Objectives

1. **Segment customers** based on purchasing patterns using RFM and K-Means.
2. **Analyze cohorts** to study customer retention and behavioral trends over time.
3. **Visualize** customer groups and retention using interactive and heatmap plots.
4. **Translate data insights into business strategies** for improved customer engagement.

---

## 🧩 Concepts Used

| Concept | Description |
|----------|--------------|
| **RFM Analysis** | Evaluates customers using Recency (last purchase), Frequency (number of purchases), and Monetary (total spent). |
| **K-Means Clustering** | Machine learning algorithm to group customers based on their RFM behavior. |
| **Cohort Analysis** | Groups customers by their signup/purchase month to track retention over time. |
| **Customer Retention** | Measures how many customers stay active in subsequent months. |

---

## 🛠️ Tech Stack

- **Language:** Python 🐍  
- **Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly`, `scikit-learn`
- **Data Source:** [Online Retail Dataset](https://www.kaggle.com/datasets) or any e-commerce transaction dataset
- **Environment:** Jupyter Notebook / VS Code

---

## 📂 Project Structure

📦 Cohort_RFM_KMeans
┣ 📜 RFM_Cohort_Cohort_RFM_KMeans.ipynb # Main Jupyter Notebook
┣ 📜 README.md # Project documentation (this file)
┣ 📜 OnlineRetail.csv # Dataset (not included, add manually)
┗ 📜 outputs/ # (optional) Exported plots & CSVs


---

## ⚙️ How to Run the Project

### 1️⃣ Clone this repository
```bash
git clone https://github.com/<your-username>/Cohort-RFM-KMeans.git
cd Cohort-RFM-KMeans

2️⃣ Install dependencies
pip install pandas numpy matplotlib seaborn plotly scikit-learn

3️⃣ Place the dataset

Download OnlineRetail.csv (or your transactional data) and place it in the same directory.

4️⃣ Run the notebook
jupyter notebook RFM_Cohort_Cohort_RFM_KMeans.ipynb

5️⃣ View results

Interactive 3D cluster visualization (Plotly)

Cohort retention heatmap (Seaborn)

Summary tables for customer segments

##📊 Example Outputs
RFM Segmentation
Segment	Behavior	Strategy
High-Value	High Freq + High Spend + Recent	Loyalty programs, exclusive deals
At-Risk	Low Recency, Medium Frequency	Reactivation offers
New Customers	High Recency, Low Frequency	Welcome campaigns
Low-Value	Low Freq + Low Spend	Targeted cross-sells
Cohort Retention Heatmap

Shows retention percentages month-over-month for each customer cohort.

💡 Business Impact
Insight	Strategic Decision
Loyal customers drive 60% of revenue	Focus retention campaigns on top 20%
Drop in 3rd-month retention	Launch engagement emails at month 2
Seasonal peaks in December	Prepare inventory and marketing in advance

This project demonstrates how data analytics can guide digital strategy decisions, aligning with consulting goals such as customer retention, churn reduction, and revenue optimization.

🧠 Learnings & Skills Gained

Out-of-memory data handling and cleaning using Pandas

Customer behavior modeling with RFM scoring

Clustering and unsupervised ML (K-Means)

Cohort-based retention analysis

Visualization and storytelling with data

Translating analytics to actionable business insights

References

Kaggle: Online Retail Dataset

Customer Segmentation Guide - Towards Data Science

Scikit-learn Documentation

👩‍💻 Author

Thandu Sirivalli
B.Tech – Electronics and Communication Engineering, NIT Trichy
📧 sirivalligoud141@gmail.com
