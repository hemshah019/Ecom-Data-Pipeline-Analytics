# E-Commerce Data Integration & Regional Analytics Pipeline

An end-to-end data engineering and analytics pipeline that extracts raw, multi-table retail transactional data, structures it programmatically into an enterprise relational database, and generates business intelligence insights.

## 🚀 Project Architecture
[Raw CSV Datasets] ➡️ [Python / Pandas Automation Loop] ➡️ [Local MySQL Server Instance] ➡️ [SQL Analytics Query] ➡️ [Seaborn Data Visualization]

## 🛠️ Tech Stack & Tools Used
* **Language:** Python 3 (Anaconda Distribution)
* **Libraries:** Pandas, NumPy, SQLAlchemy, PyMySQL, Matplotlib, Seaborn
* **Database Engine:** MySQL Server 8.x & MySQL Workbench
* **Version Control:** Git & GitHub via CLI

## 📊 Analytical Insights Uncovered
By executing an advanced structural SQL multi-table join across our migrated schema, we analyzed regional purchasing patterns across Brazil:
* **Market Dominance:** The state of **São Paulo (SP)** heavily dominates market distribution, accounting for over **41,700 total orders**.
* **Regional Disparity:** São Paulo's purchasing activity is more than triple that of the next highest economic region, Rio de Janeiro (RJ).

## 📁 Pipeline Execution Breakdown
1. **Dynamic Environment Configuration:** Initialized an isolated analytics kernel via Anaconda.
2. **Automated Migration Loop:** Developed an `os` filesystem scanning script in Python to strip string headers from source filenames and systematically inject data into MySQL without manual table configuration.
3. **Database Layer Integration:** Handled programmatic database handshakes using URL character-escaping protocols to securely bypass cryptographic database authentication parameters.
4. **Visual Reporting Layer:** Formatted publication-ready geographic visualizations to display business-critical transactional clusters to corporate stakeholders.