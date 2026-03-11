# Online-Retail-Analysis
EDA &amp; Business Insights on Online Retail dataset

**Project Goal:**  
Explore the UK Online Retail II dataset to generate actionable business insights on revenue, customers, and top products.

## Dataset
- Source: [Kaggle - Online Retail II](https://www.kaggle.com/datasets/lakshmi25npathi/online-retail-dataset)
- Format: Excel file, transactional data with Quantity, Price, Customer ID, Country, Invoice Date
- Size: ~500,000 transactions

### Dataset Columns

| Column Name    | Description |
|----------------|-------------|
| Invoice        | Unique invoice number for each transaction |
| StockCode      | Product (item) code |
| Description    | Product name / description |
| Quantity       | Number of units purchased in that transaction |
| InvoiceDate    | Date and time of the invoice |
| Price          | Unit price of the product |
| Customer ID    | Unique identifier for each customer |
| Country        | Country of the customer |

> **Note:** Additional calculated columns in the notebook include:
> - `Revenue` = Quantity × Price
> - `Month` = derived from InvoiceDate for time-based analysis

---

## Skills Demonstrated
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Data Aggregation & Grouping
- Visualization with Matplotlib & Seaborn
- Customer Revenue Analysis / Pareto Principle
- Product Analysis: Revenue vs Quantity
- Business Insights Interpretation

---

## Notebook
- `Online_Retail_Analysis.ipynb` → step-by-step EDA, plots, and observations
- All key findings are summarized in **Final Summary / Conclusions** section

---

## Usage
1. Clone the repository:
```bash
git clone https://github.com/<your-username>/Online-Retail-Analysis.git

Open the notebook in Google Colab
:

You can directly open the notebook with the link:

https://colab.research.google.com/github/<your-username>/Online-Retail-Analysis/blob/main/Online_Retail_Analysis.ipynb

If dataset is not included, download from Kaggle link above and place it in the data/ folder.

Repository Structure (recommended)

Online-Retail-Analysis/
│
├─ Online_Retail_Analysis.ipynb
├─ data/
│    └─ Online_Retail_II.xlsx

└─   README.md

