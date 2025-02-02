# eCommerce Transactions Data Analysis

## Overview
This repository contains the exploratory data analysis (EDA), lookalike model, and customer segmentation tasks for an eCommerce transactions dataset. The dataset includes three primary files: **Customers.csv, Products.csv, and Transactions.csv**, and the analysis has been performed on each dataset individually as well as in combination.

## Repository Structure
### 1. **Exploratory Data Analysis (EDA)**
EDA has been performed on each dataset separately and in combination. The following Jupyter Notebooks contain detailed analysis:

- **Kishan_Jaiswal_Customer_EDA.ipynb** → EDA on Customers dataset
- **Kishan_Jaiswal_Product_EDA.ipynb** → EDA on Products dataset
- **Kishan_Jaiswal_Transaction_EDA.ipynb** → EDA on Transactions dataset
- **Kishan_Jaiswal_Transaction_Customer_EDA.ipynb** → Combined analysis of Transactions and Customers dataset
- **Kishan_Jaiswal_Transaction_Product_Customer_EDA.ipynb** → Combined analysis of Transactions, Products, and Customers dataset

**EDA Reports:**
- **Kishan_Jaiswal_EDA.pdf** → Summary of business insights derived from EDA

### 2. **Task 2: Lookalike Model**
A Lookalike Model was developed to find the top 3 similar customers based on transaction history and profile data. 

- **Kishan_Jaiswal_Lookalike.ipynb** → Jupyter Notebook explaining the Lookalike Model implementation
- **Kishan_Jaiswal_Lookalike.csv** → Output file mapping each customer to their top 3 similar customers along with similarity scores

### 3. **Task 3: Customer Segmentation (Clustering)**
Customer segmentation was performed using clustering techniques. The number of clusters was optimized using evaluation metrics such as the Davies-Bouldin Index.

- **Kishan_Jaiswal_Clustering.ipynb** → Jupyter Notebook detailing the clustering approach
- **Kishan_Jaiswal_Clustering.pdf** → Report summarizing the clustering results

## Submission Details
This project follows the required submission structure, ensuring proper file naming conventions. All scripts and reports are included in the repository for easy access and reproducibility.

## How to Use This Repository
1. Clone the repository using:
   ```bash
   git clone <repository_url>
   ```
2. Open the respective **.ipynb** files in Jupyter Notebook to explore the analysis and modeling steps.
3. Refer to the **PDF reports** for summarized insights and explanations.
4. Check **Lookalike.csv** for similar customer mappings.

## Author
**Kishan Jaiswal**

---
This repository serves as a comprehensive data science project on eCommerce transactions, covering EDA, predictive modeling, and customer segmentation. 🚀
