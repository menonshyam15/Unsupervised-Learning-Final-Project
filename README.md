# **Customer Segmentation Using Unsupervised Learning**  

## **Overview**  
This project applies **unsupervised machine learning** to segment customers based on purchasing behavior using the **Online Retail dataset** from the UCI Machine Learning Repository. By leveraging clustering techniques, we uncover hidden patterns in transaction data to help businesses make **data-driven decisions** on marketing, sales, and inventory management.  

## **Problem Statement**  
Retail businesses struggle with understanding diverse customer behaviors, leading to generic marketing and inefficient resource allocation. **Customer segmentation** allows businesses to identify distinct customer groups, personalize promotions, and optimize stock levels.  

## **Approach**  
1. **Data Preprocessing**  
   - Cleaned missing values and filtered out invalid transactions.  
   - Engineered key features like total purchases, quantity bought, and average unit price per customer.  

2. **Exploratory Data Analysis (EDA)**  
   - Analyzed sales trends, purchase distributions, and customer demographics.  
   - Visualized key patterns in product sales and regional customer behavior.  

3. **Clustering with K-Means**  
   - Standardized the dataset for better clustering performance.  
   - Used **PCA (Principal Component Analysis)** for dimensionality reduction.  
   - Determined the optimal number of clusters using **Elbow Method** and **Silhouette Score**.  

4. **Cluster Interpretation**  
   - Identified meaningful customer segments, such as:  
     - **Frequent small-scale buyers**  
     - **Bulk purchasers**  
     - **High-value product customers**  

## **Results & Business Impact**  
- **Actionable insights** for targeted marketing, pricing strategies, and customer retention.  
- **Efficient inventory management** by predicting product demand per segment.  
- **Enhanced customer engagement** through personalized recommendations.  

## **Technologies Used**  
- **Python** (Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn)  
- **Machine Learning** (K-Means Clustering, PCA, Silhouette Analysis)  
- **Jupyter Notebook** for development and visualization  

## **How to Run the Project**  
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```
3. Open Jupyter Notebook and run the script:  
   ```bash
   jupyter notebook
   ```
4. Follow the step-by-step analysis inside the notebook.  

## **Next Steps**  
- Implement **Hierarchical Clustering** and compare with K-Means.  
- Deploy as a web-based analytics dashboard for business users.  
- Integrate **RFM analysis** (Recency, Frequency, Monetary Value) for advanced segmentation.  

## **Contributors**  
👤 **Shyam Menon**  
🔗 [LinkedIn](https://www.linkedin.com/in/menonshyam703/)
