# 🛒 Customer Segmentation for an E-commerce Company

This project applies **RFM analysis** and **K-Means clustering** to segment customers based on their purchasing behavior. The goal is to help businesses create targeted marketing strategies using data-driven insights.

## 📌 Project Overview
- **Dataset**: Online retail transactions (includes InvoiceNo, CustomerID, Quantity, Price, etc.)
- **Tech Stack**: SQL, Python, pandas, scikit-learn, matplotlib, seaborn
- **Key Methods**: 
  - RFM Analysis (Recency, Frequency, Monetary)
  - K-Means clustering for segmentation
  - Elbow Method for optimal k
  - Data visualization to interpret results

## 📊 Results & Insights
After applying RFM (Recency, Frequency, Monetary) analysis and K-Means clustering, the customers were segmented into three groups based on their purchasing behavior.

🔹 Cluster Insights:
1️⃣ High-Value Customers (Cluster 2 - Yellow)

These customers have high monetary value and low recency, meaning they purchase frequently.

They are the most profitable segment and should be prioritized for loyalty programs and premium offers.

2️⃣ Moderate-Value Customers (Cluster 1 - Teal)

These customers have moderate spending habits and purchase less frequently.

Engaging them with targeted promotions can increase their spending behavior.

3️⃣ Low-Value Customers (Cluster 0 - Purple)

These customers make infrequent purchases and have low monetary value.

Strategies like re-engagement campaigns and discount offers can help retain them.

📌 Key Takeaways:
The elbow method helped identify the optimal number of clusters (k=3).

High-value customers are the most loyal and contribute significantly to revenue.

Most customers are in the low-value segment, requiring better engagement strategies.

RFM segmentation provides actionable insights to improve customer retention and marketing strategies.

## 📷 Visualizations
### **1️⃣ Elbow Method for Optimal Clusters**
![Elbow Method](https://github.com/27yogesh-rbu/Customer-Segmentation-Ecommerce/blob/main/Screenshot%202025-03-31%20141735.png?raw=true)

### **2️⃣ Customer Segments Based on RFM**
![Customer Segments](https://github.com/27yogesh-rbu/Customer-Segmentation-Ecommerce/blob/main/Screenshot%202025-03-31%20141726.png?raw=true)

## 🚀 How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/24yogesh-rbu/Customer-Segmentation-Ecommerce.git

