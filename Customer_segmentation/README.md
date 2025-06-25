
# 🛍️ Customer Segmentation with Machine Learning

This project applies **unsupervised machine learning techniques** to perform **customer segmentation** - a crucial step in understanding and targeting different user groups based on their behavior. By analyzing purchasing data, we aim to group customers with similar traits and shopping habits into meaningful clusters.

---

## 🧠 What is Customer Segmentation?

Customer segmentation is the process of dividing a company's customer base into distinct groups that share similar characteristics. This allows businesses to:

- Tailor marketing strategies to each group
- Improve customer satisfaction and retention
- Increase sales through targeted promotions

In this project, we use clustering techniques to segment customers based on features like **purchase history**, **frequency**, **recency**, and **monetary value**.

---

## 📊 Dataset

The dataset used in this project is the **Online Retail dataset**, which contains transactional data for a UK-based retail company.

| Column           | Description                          |
|------------------|--------------------------------------|
| InvoiceNo        | Invoice number                       |
| StockCode        | Item code                            |
| Description      | Item description                     |
| Quantity         | Number of items bought               |
| InvoiceDate      | Date of purchase                     |
| UnitPrice        | Price per item                       |
| CustomerID       | Unique identifier for each customer  |
| Country          | Country of the customer              |

---

## 🔧 Techniques Used

- 🧹 **Data Cleaning**: Handling missing values, removing cancel orders
- 📏 **Feature Scaling**: StandardScaler
- 📊 **RFM Analysis**: Recency, Frequency, and Monetary value calculation
- 📈 **K-Means Clustering**: Optimal clusters selected using Elbow Method & Silhouette Score (priortized Silhoutte Score results).
- 🖼️ **Cluster Visualization**: Pie & Box plots and cluster profiling

---

## 📂 Project Structure

- `Customer_Segmentation.ipynb`: Main notebook with complete pipeline from data cleaning to clustering and visualization
- `Online Retail.xlsx`: Dataset (uploaded inside dataset folder)
- `README.md`: Project overview (this file)

---

## 🧪 How to Run

1. Clone this repository or open in Google Colab / Jupyter Notebook
2. Install dependencies if needed:

```bash
pip install pandas matplotlib seaborn scikit-learn openpyxl
```

3. Run the notebook:  
   Explore the steps and check out the customer segmentation results

---

## 📌 Results

The dataset was segmented into distinct customer groups based on purchasing patterns. These clusters can be interpreted as:

- 🛒 `Loyal Customers`
- 📦 `Potential Loyal Customers`
- 💤 `Lost Customers` 
- 🔁 `New Customers`

Each segment is visualized and profiled for strategic decision-making.

---

## 🎯 Business Impact

With customer segments clearly identified, businesses can:

- Run targeted marketing campaigns
- Design loyalty programs for high-value customers
- Re-engage inactive users
- Optimize inventory based on demand from specific groups

---

## 📜 License

This project is shared under the [MIT License](LICENSE).  
Feel free to use, modify, and build upon it for learning or commercial purposes.

---

