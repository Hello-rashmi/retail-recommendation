# retail-recommendation
A product recommendation system using customer purchase history with Python, EDA, and item-based collaborative filtering

# Online Retail Recommendation System

This project demonstrates the development of a basic product recommendation system for an online retail platform using customer transaction history. The aim is to provide relevant product suggestions and gain insights into customer behavior and sales performance.

---

## Project Features

-  Exploratory Data Analysis (EDA)
  - Top 10 Customers
  - Top 10 Best-Selling Products
  - Country-wise Sales Analysis
  - Top Product Pairs Frequently Bought Together

-  Item-Based Collaborative Filtering
  - Cosine Similarity Calculation
  - Top-N Product Recommendations
  - Binary User-Item Matrix

-  Visualizations using `Matplotlib` and `Seaborn`

---

##  Dataset

The dataset used comes from a historical online retail store. It includes the following fields:

- InvoiceNo
- StockCode
- Description
- Quantity
- InvoiceDate
- UnitPrice
- CustomerID
- Country

>  The original dataset is available in `.xlsx` format and was uploaded via Google Drive or Google Sheets.

---

##  Tools & Technologies

- **Language**: Python
- **Libraries**: pandas, numpy, scikit-learn, matplotlib, seaborn
- **Platform**: Google Colab / Jupyter Notebook

---

##  How It Works

1. **Data Preprocessing**
   - Handle missing values
   - Filter positive quantity purchases
   - Create user-item interaction matrix

2. **Recommendation Logic**
   - Apply cosine similarity on binary purchase patterns
   - Return Top-N product suggestions for a selected item

3. **Analysis**
   - Identify customer and product trends
   - Visualize insights for easier interpretation
