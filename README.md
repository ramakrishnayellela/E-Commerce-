# eCommerce Transactions Analysis

This repository contains the code and reports for an analysis of an eCommerce Transactions dataset. The dataset consists of three files:

* **Customers.csv:** Contains information about customers, including their IDs, names, regions, and signup dates.
* **Products.csv:** Contains information about products, including their IDs, names, categories, and prices.
* **Transactions.csv:** Contains information about customer transactions, including transaction IDs, customer IDs, product IDs, transaction dates, quantities, total values, and prices.

**Tasks:**

1. **Exploratory Data Analysis (EDA) and Business Insights:**
   - Performed EDA on the dataset.
   - Derived and documented 5 key business insights.

2. **Lookalike Model:**
   - Built a lookalike model to recommend 3 similar customers for each user based on their profile and transaction history.
   - Used both customer and product information to build the model.
   - Assigned a similarity score to each recommended customer.
   - Created a "Lookalike.csv" file containing the top 3 lookalikes with their similarity scores for the first 20 customers.

3. **Customer Segmentation:**
   - Performed customer segmentation using clustering techniques.
   - Utilized both profile and transaction information for segmentation.
   - Calculated and reported clustering metrics, including the DB Index.
   - Visualized the clusters using relevant plots.

**Files:**

* **Jupyter Notebooks:** Contain the code for EDA, lookalike model, and customer segmentation.
* **PDF Reports:** 
    - EDA Report: Contains the 5 key business insights derived from the EDA.
    - Clustering Report: Summarizes the clustering results, including the number of clusters, DB Index value, and other relevant metrics. 
* **Lookalike.csv:** Contains the top 3 lookalikes with their similarity scores for the first 20 customers.

**Tools:**

* Python (with libraries like pandas, scikit-learn, matplotlib)

**Note:**

This README provides a brief overview of the project. For more detailed information, please refer to the Jupyter Notebooks and PDF reports.
