# Data Science Assignment: eCommerce Transactions Dataset

## Overview
This repository contains the solutions to the **Data Science Assignment** focused on analyzing an eCommerce Transactions dataset. The assignment involved tasks like Exploratory Data Analysis (EDA), building predictive models, and customer segmentation. The repository demonstrates data science skills in analyzing business data, generating insights, and providing actionable solutions.

---

## Dataset Description
The dataset consists of three files:
1. **Customers.csv**:
   - `CustomerID`: Unique identifier for each customer.
   - `CustomerName`: Name of the customer.
   - `Region`: Continent where the customer resides.
   - `SignupDate`: Date when the customer signed up.

2. **Products.csv**:
   - `ProductID`: Unique identifier for each product.
   - `ProductName`: Name of the product.
   - `Category`: Product category.
   - `Price`: Product price in USD.

3. **Transactions.csv**:
   - `TransactionID`: Unique identifier for each transaction.
   - `CustomerID`: ID of the customer who made the transaction.
   - `ProductID`: ID of the product sold.
   - `TransactionDate`: Date of the transaction.
   - `Quantity`: Quantity of the product purchased.
   - `TotalValue`: Total value of the transaction.
   - `Price`: Price of the product sold.

---

## Assignment Tasks
### 1. Exploratory Data Analysis (EDA) and Business Insights
- Conducted EDA to understand customer behavior and sales trends.
- Generated 5 actionable business insights from the data.
- Deliverables:
   - [EDA Jupyter Notebook](https://github.com/Rakeek/Zeotap-Assignments/blob/main/Data%20Science%20Assignment%3A%20eCommerce%20Transactions%20Dataset/RakeekMirza_Kamarudeen_EDA.ipynb)
   - [EDA PDF Report](https://github.com/Rakeek/Zeotap-Assignments/blob/main/Data%20Science%20Assignment%3A%20eCommerce%20Transactions%20Dataset/RakeekMirza_Kamarudeen_EDA.pdf)

### 2. Lookalike Model
- Developed a model to recommend 3 similar customers for the first 20 customers based on profile and transaction history.
- Deliverables:
  - [Lookalike Jupyter Notebook](https://github.com/Rakeek/Zeotap-Assignments/blob/main/Data%20Science%20Assignment%3A%20eCommerce%20Transactions%20Dataset/RakeekMirza_Kamarudeen_Lookalike.ipynb)
  - [Lookalike Output CSV](https://github.com/Rakeek/Zeotap-Assignments/blob/main/Data%20Science%20Assignment%3A%20eCommerce%20Transactions%20Dataset/RakeekMirza_Kamarudeen_Lookalike.csv)

### 3. Customer Segmentation / Clustering
- Performed customer segmentation using clustering techniques.
- Evaluated clustering using Davies-Bouldin Index (DB Index) and visualized results.
- Deliverables:
  - [Clustering Jupyter Notebook](https://github.com/Rakeek/Zeotap-Assignments/blob/main/Data%20Science%20Assignment%3A%20eCommerce%20Transactions%20Dataset/RakeekMirza_Kamarudeen_Clustering.ipynb)
  - [Clustering PDF Report](https://github.com/Rakeek/Zeotap-Assignments/blob/main/Data%20Science%20Assignment%3A%20eCommerce%20Transactions%20Dataset/RakeekMirza_Kamarudeen_Clustering.pdf)

---


## Tools and Technologies Used
- **Programming Language**: Python
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Data Processing**: Exploratory Data Analysis, Feature Engineering
- **Machine Learning Models**: Clustering (K-Means), Similarity-based recommendation
- **Evaluation Metrics**: Davies-Bouldin Index (DB Index)

---

## Key Results
1. **EDA and Insights**:
   - Discovered seasonal trends, regional customer distribution, and high-performing products.
   - Identified key customer segments contributing to the revenue.

2. **Lookalike Model**:
   - Successfully recommended similar customers with similarity scores for the first 20 customers.

3. **Customer Segmentation**:
   - Segmented customers into 4 clusters based on transaction behavior and demographics.
   - Achieved a DB Index value of **0.88**, indicating well-separated clusters.


---

## How to Run
1. Clone the repository:
   ```bash
   git clone <repository_link>
   cd <repository_name>

---

## Contact
For any questions or suggestions, feel free to contact:

- **Name**: Rakeek Mirza Kamarudeen
- **Email**: rakeekmirza@gmail.com


## License

This project is licensed under the [MIT License](LICENSE).
