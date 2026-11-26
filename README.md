🏦 Capital Bank: Performance & Loan Analytics

🎯 Objective:
The objective of this project is to analyze Capital Bank's data in order to:
- Understand customer distribution across states and account types.
- Identify which account types retain customers, maintain healthy balances and generate the most interest.
- Evaluate branch performance based on transaction volume.
- Monitor loan repayment behavior and identify accounts with a high number of overdue loans.
- Track account-opening trends over time.
- Provide data-driven recommendations to improve customer retention, customer acquisition and loan risk management.


❓ Business Questions Solved:
1. Which account type has the highest closure rate?
2. In which states are the maximum and minimum numbers of customers?
3. Which type of account maintains a good balance?
4. Which branch performs the highest number of transactions?
5. Which type of account pays the maximum interest amount?
6. Which type of account has the maximum number of overdue loans?

🗂️ Data Source:
This is a synthetic dataset downloaded from Kaggle.com.

🛠️ Tools Used:
| Tool | Purpose |
|------|---------|
| **Microsoft Excel** | Data summarization and Exploratory Data Analysis (EDA) |
| **Python (Pandas)** | Data cleaning in a Jupyter Notebook |
| **SQL (MySQL)** | Database creation and end-to-end data analysis |
| **Power BI** | DAX measures, KPIs and an interactive dashboard |

🔄 Project Workflow

```
Raw Data (Kaggle)
      │
      ▼
 Excel ──────────► Data summarization & EDA
      │
      ▼
 Python (Pandas) ► Data cleaning in Jupyter Notebook
      │
      ▼
 MySQL ──────────► Database creation & SQL analysis
      │
      ▼
 Power BI ───────► DAX measures, KPIs & 2-page dashboard
```

### 1️⃣ Excel: Data Summarization & EDA
Summarized the data and performed exploratory data analysis to understand its structure and quality.

### 2️⃣ Python (Pandas): Data Cleaning
Performed in a Jupyter Notebook:

1. Removing duplicate values
2. Handling null values
3. Removing extra white spaces
4. Detecting and removing outliers
5. Fixing data types
6. Fixing language translation issues

### 3️⃣ SQL: Database & Analysis
Created a MySQL database and performed end-to-end data analysis using SQL queries.

### 4️⃣ Power BI: Dashboard
- Connected the MySQL database to Power BI.
- Created DAX measures and calculated columns for KPIs.
- Designed a **two-page interactive dashboard**.



💡 Key Insights:
1. **Payroll and Saving accounts** maintain a good balance compared to other account types.
2. **Texas** has the highest number of customers, while **Florida** has the fewest.
3. The **account closure rate of Saving accounts** is higher than that of other account types.
4. **Business accounts** earn the highest interest, while **Payroll accounts** earn less interest.
5. The percentage of **paid loans is high** compared to overdue loans.
6. **Youth accounts** have a high number of overdue loans, while **Business accounts** have the fewest.
7. The number of **new account openings dropped heavily from 2022**.

✅ Recommendations:
1. **Reduce closure of Saving accounts:** offer incentives and benefits on Saving accounts to lower the account closure rate.
2. **Grow customers in Florida:** build a strong marketing strategy to attract new customers for account opening, especially in Florida.
3. **Control overdue loans:** introduce a stricter loan issuance policy to reduce overdue loans, especially for Youth accounts.

<img width="587" height="329" alt="Screenshot 2026-11-23 110012" src="https://github.com/user-attachments/assets/7958e77f-e9c4-4e67-abe8-31ceed1ada2f" />
<img width="586" height="335" alt="Screenshot 2026-11-23 110101" src="https://github.com/user-attachments/assets/6b8932f7-4c1a-4ab1-88c8-21f698f50e7a" />
