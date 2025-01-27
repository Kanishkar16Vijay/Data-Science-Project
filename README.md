# eCommerce Transactions Dataset Analysis

This project analyzes an eCommerce transactions dataset to derive business insights, build a lookalike model, and perform customer segmentation. The goal is to demonstrate data science capabilities in exploratory data analysis (EDA), recommendation systems, and clustering techniques.

## Project Tasks

### 1. **Exploratory Data Analysis (EDA)**
- Perform EDA on the dataset to uncover trends, patterns, and actionable insights.
- Deliverables:
  - Python code (Jupyter Notebook)
  - PDF report summarizing 5 key business insights.

### 2. **Lookalike Model**
- Build a recommendation system that suggests 3 similar customers based on profile and transaction history.
- Deliverables:
  - CSV file containing lookalike recommendations for the first 20 customers.
  - Python code (Jupyter Notebook) for model development.

### 3. **Customer Segmentation / Clustering**
- Perform clustering to segment customers based on profiles and transactions.
- Deliverables:
  - Report with clustering results, including the number of clusters and evaluation metrics (e.g., DB Index).
  - Python code (Jupyter Notebook) for clustering.

---

## Dataset
The project uses three files:

1. **Customers.csv**:
   - `CustomerID`: Unique customer identifier.
   - `CustomerName`: Name of the customer.
   - `Region`: Customer's region.
   - `SignupDate`: Date of signup.

2. **Products.csv**:
   - `ProductID`: Unique product identifier.
   - `ProductName`: Name of the product.
   - `Category`: Product category.
   - `Price`: Product price (USD).

3. **Transactions.csv**:
   - `TransactionID`: Unique transaction identifier.
   - `CustomerID`: Customer who made the transaction.
   - `ProductID`: Product involved in the transaction.
   - `TransactionDate`: Date of transaction.
   - `Quantity`: Quantity purchased.
   - `TotalValue`: Total value of the transaction (USD).

---

## Repository Structure
```
├── data/
│   ├── Customers.csv
│   ├── Products.csv
│   ├── Transactions.csv
├── notebooks/
│   ├── FirstName_LastName_EDA.ipynb
│   ├── FirstName_LastName_Lookalike.ipynb
│   ├── FirstName_LastName_Clustering.ipynb
├── reports/
│   ├── FirstName_LastName_EDA.pdf
│   ├── FirstName_LastName_Clustering.pdf
├── results/
│   ├── Lookalike.csv
├── README.md
```

---

## Getting Started

### Prerequisites
- Python 3.7+
- Required libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/<username>/ecommerce-analysis.git
   cd ecommerce-analysis
   ```
2. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Upload the datasets to the `data/` directory.

---

## Usage

### Run EDA:
1. Navigate to the `notebooks/` directory.
2. Open and execute the `FirstName_LastName_EDA.ipynb` notebook to perform EDA and generate insights.

### Build Lookalike Model:
1. Open and execute the `FirstName_LastName_Lookalike.ipynb` notebook.
2. Check the output file `Lookalike.csv` in the `results/` directory.

### Perform Clustering:
1. Open and execute the `FirstName_LastName_Clustering.ipynb` notebook.
2. Review the clustering report in `reports/`.

---

## Results
- **EDA:** Uncovered trends in customer behavior, product sales, and revenue.
- **Lookalike Model:** Recommended 3 similar customers for each of the first 20 customers.
- **Clustering:** Segmented customers into distinct groups with detailed metrics.

---

## Author
Kanishkar V 
kanishvijay2005@gmail.com 
www.linkedin.com/in/kanishkar-v-3471782a2/

---

## License
This project is licensed under the MIT License. See the LICENSE file for details.

