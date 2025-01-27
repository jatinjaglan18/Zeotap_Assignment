# eCommerce Transactions Analysis and Modeling

This repository contains the solution to an **eCommerce Transactions Dataset** assignment. The tasks involve exploratory data analysis (EDA), predictive modeling, and customer segmentation to derive actionable business insights.

---

## Project Overview

This project utilizes three datasets:
1. **Customers.csv**: Contains customer profile data.
2. **Products.csv**: Contains product information.
3. **Transactions.csv**: Contains transactional records.

### Tasks:

1. **Exploratory Data Analysis (EDA)**:
   - Analyzed the datasets for trends, patterns, and anomalies.
   - Derived actionable insights about customer behavior and purchasing trends.

2. **Lookalike Model**:
   - Built a recommendation model to suggest 3 similar customers for each user based on profile and transaction history.
   - Utilized features like spending habits, transaction frequency, product categories, and customer region.

3. **Customer Segmentation (Clustering)**:
   - Grouped customers into distinct segments based on profile and transaction data.
   - Evaluated clustering quality using metrics like **DB Index**.
   - Visualized customer clusters using scatter plots and heatmaps.

---

## Dataset Description

### Customers.csv:
- **CustomerID**: Unique customer identifier.
- **CustomerName**: Name of the customer.
- **Region**: Continent of residence.
- **SignupDate**: Customer signup date.

### Products.csv:
- **ProductID**: Unique product identifier.
- **ProductName**: Name of the product.
- **Category**: Product category.
- **Price**: Price of the product in USD.

### Transactions.csv:
- **TransactionID**: Unique transaction identifier.
- **CustomerID**: ID of the purchasing customer.
- **ProductID**: Product sold in the transaction.
- **TransactionDate**: Date of the transaction.
- **Quantity**: Quantity purchased.
- **TotalValue**: Total transaction value.
- **Price**: Price of the product sold. 

---

## Project Files

| File                       | Description                                                                                  |
|----------------------------|----------------------------------------------------------------------------------------------|
| `Jatin_Jaglan_EDA.ipynb`                | Contains the exploratory data analysis and insights generation code.                         |
| `Jatin_Jaglan_EDA.pdf`     | PDF report summarizing key business insights derived from the dataset.                       |
| `Jatin_Jaglan_Lookalike.ipynb`    | Code for building the lookalike model and generating recommendations.                        |
| `Jatin_Jaglan_Lookalike.csv`            | Output file: Top 3 similar customers for each user (CustomerID: C0001 - C0020).              |
| `Jatin_Jaglan_Clustering.ipynb` | Code for customer segmentation using clustering techniques.                             |
| `Jatin_Jaglan_Clustering.pdf` | PDF for number of cluster, evaluation and visualization of Clusterng results                            |
| `README.md`                | This readme file describing the project.                                                    |


---

## Author
Jatin Jaglan
