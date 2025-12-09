# 🚗 HMA Accounting Manual Chart of Accounts (CSV)

This repository contains the full Chart of Accounts for the Hyundai Motor America (HMA) Accounting Manual, converted into machine-readable **CSV (Comma Separated Values)** format.

The HMA Accounting Manual provides a standardized structure for classifying financial transactions within a Hyundai dealership. This repository serves as a data resource for developers, analysts, and accountants who need to integrate, query, or analyze this standardized financial data.

---

## 💾 Repository Structure

The data is logically organized into six separate CSV files, corresponding to the major financial categories:

| File Name | Contains | Description |
| :--- | :--- | :--- |
| `assets.csv` | Accounts 200–296 | Cash, Receivables, Inventories (Vehicle & Parts), Prepaids, and Fixed Assets. |
| `liabilities_equity.csv` | Accounts 300–399 | Current & Long-Term Liabilities, Accrued Expenses, Depreciation, and Net Worth (Equity). |
| `sales_cost_of_sales.csv` | Accounts 401–708 | All Revenue and Cost of Sales accounts, broken down by department (New Vehicle, Used Vehicle, Service, Parts, Body Shop). |
| `additions_deductions.csv` | Accounts 652B, 800-859 | Non-operating Income and Expense items, including Interest Income/Expense and miscellaneous adjustments. |
| `expenses.csv` | Accounts 11–99, 802, 852 | Operational Expenses, including compensation, advertising, facility costs, and general administrative expenses. |
| `guidelines.csv` | Management Information | Non-financial metrics and operational guidelines (e.g., Personnel Summary, Hourly Labor Rates, Service Bays). |

---

## 🛠️ Data Usage

Each CSV file is structured with the following columns:

* **"Account Number"**: The unique 3-digit number used for the general ledger.
* **"Account Name"**: The official description of the account.
* **"Category" / "Classification" / "Department"**: A high-level grouping to aid in filtering and analysis.

This format is ideal for direct import into tools like **Microsoft Excel**, **Google Sheets**, **SQL databases**, or data analysis libraries in **Python** or **R**.
