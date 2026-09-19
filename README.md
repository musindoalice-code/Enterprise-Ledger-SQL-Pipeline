
# Enterprise Ledger & Analytical Data Engineering Pipeline

## 📌 Project Overview
Engineered a scalable SQL-driven relational database architecture designed to ingest complex multi-source General Ledger data extracts and run continuous control monitoring audits for corporate financial risks.

## 🛠️ Tech Stack & SQL Architecture
- **Engine:** PostgreSQL / SQLite Engine ANSI Compliant
- **Core Operations:** Common Table Expressions (CTEs), Subqueries, Window Analytics (`SUM OVER`, `LAG`), Aggregations.

## 💼 Business Impact & Findings
- **Data Integrity:** Normalizes messy character strings and punctuation variants to map parent-subsidiary company relationships across fragmented transaction streams.
- **Risk Mitigation:** Isolates systemic automated system approval vulnerabilities on values over R45,000.00 and surfaces time-proximate transactions designed to circumvent operational internal controls.
