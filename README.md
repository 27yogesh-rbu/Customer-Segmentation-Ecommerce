# 🛒 Customer Segmentation for an E-commerce Company

## 📌 **Project Overview**  
This project applies **RFM (Recency, Frequency, Monetary) analysis** and **K-Means clustering** to segment e-commerce customers based on their purchasing behavior. By analyzing transaction data, businesses can better understand customer loyalty and spending patterns, helping them tailor marketing strategies and improve customer retention.  

## 🔍 **Objective**  
- Identify different customer segments based on purchasing behavior.  
- Provide actionable insights to optimize marketing strategies.  
- Improve customer engagement and retention using data-driven decisions.  

## 📂 **Dataset**  
- **Source:** [Online Retail Dataset](https://archive.ics.uci.edu/ml/datasets/Online+Retail)  
- **Description:** Contains transactional data for an e-commerce business, including invoice numbers, product descriptions, quantities, customer IDs, and purchase dates.  

## 🛠 **Technologies Used**  
- **SQL** – Data extraction and preprocessing  
- **Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)** – Data analysis, visualization, and clustering  
- **Jupyter Notebook** – Development environment  

## 🔬 **Methodology**  

### **1️⃣ Data Preprocessing**  
- Removed missing and duplicate values  
- Filtered out canceled orders  
- Created **RFM scores** for each customer  

### **2️⃣ RFM Analysis**  
- **Recency (R):** How recently a customer made a purchase  
- **Frequency (F):** How often a customer makes a purchase  
- **Monetary (M):** Total spending by the customer  

### **3️⃣ K-Means Clustering**  
- Used the **Elbow Method** to determine the optimal number of clusters  
- Segmented customers into **three distinct groups**  

## 📊 **Results & Insights**  

After clustering, we identified **three customer segments:**  

1️⃣ **High-Value Customers (Cluster 2 - Yellow)**  
   - Frequent purchasers with high spending.  
   - Should be prioritized for **loyalty programs** and **premium offers**.  

2️⃣ **Moderate-Value Customers (Cluster 1 - Teal)**  
   - Moderate purchasing frequency and spending.  
   - Can be **engaged with targeted promotions** to boost revenue.  

3️⃣ **Low-Value Customers (Cluster 0 - Purple)**  
   - Infrequent buyers with low spending.  
   - Can be **re-engaged through discounts and personalized campaigns**.  

## 📉 **Visualizations**  
![Elbow Method](https://github.com/27yogesh-rbu/Customer-Segmentation-Ecommerce/blob/main/Screenshot%202025-03-31%20141735.png?raw=true)  
*Figure 1: Optimal number of clusters determined using the Elbow Method.*  

![Customer Segments](https://github.com/27yogesh-rbu/Customer-Segmentation-Ecommerce/blob/main/Screenshot%202025-03-31%20141726.png?raw=true)  
*Figure 2: Customer segmentation based on RFM analysis.*  

## 🚀 **Business Recommendations**  
- **High-value customers** should receive **exclusive discounts, early access, and personalized recommendations**.  
- **Moderate-value customers** can be **encouraged to spend more through seasonal promotions**.  
- **Low-value customers** should be **targeted with re-engagement campaigns** to increase frequency.  

## 📎 **Project Files**  
📂 `customer_segmentation.ipynb` – Jupyter Notebook containing all code and analysis  
📂 `Online Retail.xlsx` – Raw dataset used for analysis  
📂 `requirements.txt` – List of dependencies required to run this project  

## 📦 **Installation & Usage**  

### **1️⃣ Clone the Repository**  
```bash
git clone https://github.com/27yogesh-rbu/Customer-Segmentation-Ecommerce.git
cd Customer-Segmentation-Ecommerce
```
### **2️⃣ Install Dependencies**  
```bash
pip install -r requirements.txt
```
### **3️⃣ Run the Jupyter Notebook**  
```bash
jupyter notebook
```

## 🌟 **Future Improvements**  
- Apply **Hierarchical Clustering** for comparison.  
- Implement **Customer Lifetime Value (CLV) analysis**.  
- Develop a **dashboard for real-time customer insights**.  




