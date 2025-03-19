# RFM & KMeans Segmentation 🚀

This project focuses on **customer segmentation** using **RFM analysis** and **K-Means clustering** based on **Recency, Frequency, and Monetary (RFM) features**. 

The **goal** is to:

✔ Use both models to perform customer segmentation  
✔ Derive meaningful insights for the customer base  
✔ Understand customer behavior with **simple yet effective models**  
✔ Be used on real and more complex databases  

💡 **Why a simple model?**  
From my experience, **minimal effort models** like RFM + a simple KMeans can provide **valuable customer insights** and **quick business gains**. More advanced clustering approaches can be explored in the future.

---

## 📌 Steps
- ✅ **Data Cleaning & Processing**
- ✅ **RFM Analysis (Recency, Frequency, Monetary)**
- ✅ **Finding the Optimal K for Clustering (Elbow Method & Silhouette Score)**
- ✅ **KMeans Clustering with Grid Search**
- ✅ **Interactive Data Visualizations with Plotly**

---

## 📂 Project Structure
```
📁 RFM & Clustering Project/
│── 📂 Data_Lake/         # Processed data
│── 📂 _archive/          # Archived scripts
│    ├── full_script.ipynb  # Full version of the workflow (archived)
│── 📜 data_processing.ipynb     # Cleans & preprocesses the dataset
│── 📜 rfm_analysis.ipynb        # Computes RFM metrics
│── 📜 k_means_clustering.ipynb  # Runs clustering & assigns segments
│── 📜 README.md                 # Project documentation
```

---
## 📊 Data Source
This project uses **real-world transactional data** from:  
📌 **A UK-based, registered, non-store online retail company** 📊  
🗄 **Dataset from Kaggle**: [Ecommerce Data](https://www.kaggle.com/datasets/carrie1/ecommerce-data)

📢 **Data Description**:  
- Transactions from **2010-2011**
- Contains **invoices, customer IDs, purchase quantities, and prices**
- Used to derive **Recency, Frequency, and Monetary (RFM) values** for segmentation

---

## 🚀 Usage
Run each script **in order**:
```sh
python data_processing.py
python rfm_analysis.py
python kmeans_clustering.py
```

---

## 🏆 Business Impact
This approach helps businesses:

✔ Identify **high-value customers**  
✔ Detect **churn risk & win-back opportunities**  
✔ Target **loyal customers with special offers**  
✔ Quickly implement **data-driven marketing strategies**  

---

## 📌 License
This project is **open-source**.

---
