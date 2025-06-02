# Consumer Complaints Analysis

## Overview
This repository contains the analysis of consumer complaints from the "Consumer Complaints Case Study.xlsx" dataset, focusing on identifying trends, key issues, and company performance in handling complaints. The analysis is divided into two tasks: **Task 4 (Reporting)** and **Task 5 (Dashboard)**, providing insights into complaint patterns, resolution times, and prioritization strategies.

## Dataset
The dataset includes 14,000 complaints with details such as:
- **Complaint ID**: Unique identifier
- **Company**: Company name
- **Product**: Financial product (e.g., Mortgage, Credit card)
- **Issue**: Specific complaint issue
- **State**: U.S. state of origin
- **Submitted via**: Channel (Web, Email, etc.)
- **Timely response?**: Yes/No
- **Consumer disputed?**: Yes/No
- **Resolution time**: Days to resolve
- **Year**: 2013–2016

## Analysis

### Task 4: Reporting
1. **Top 5 Companies by Complaints**:
   - Bank of America: 1,066
   - Wells Fargo & Company: 947
   - JPMorgan Chase & Co.: 877
   - Citibank: 764
   - Equifax: 531
2. **Top 5 Issues**:
   - Loan servicing, payments, escrow account: 2,354
   - Account opening, closing, or management: 1,047
   - Loan modification, collection, foreclosure: 883
   - Communication tactics: 814
   - Deposits and withdrawals: 618
3. **Monthly Trends**:
   - Visualized via a line chart showing peaks in 2015 (93 complaints) and a decline in 2016 (47 complaints).

### Task 5: Dashboard
1. **KPIs**:
   - **Total Complaints (YoY)**:
     - 2013: 1,944
     - 2014: 2,748 (+41.36%)
     - 2015: 3,390 (+23.36%)
     - 2016: 2,780 (-17.99%)
   - **Timely Responses (YoY)**:
     - 2013: 8
     - 2014: 36 (+28)
     - 2015: 93 (+57)
     - 2016: 47 (-46)
   - **Average Resolution Time (YoY)**:
     - 2013: 12.13 days
     - 2014: 6.97 days (-5.15)
     - 2015: 8.08 days (+1.10)
     - 2016: 11.04 days (+2.97)
2. **Complaints by Product**:
   - Debt collection: 50.00%
   - Mortgage: 18.48%
   - Bank account or service: 8.70%
3. **Complaints by Channel**:
   - Web: 80.98%
   - Email: 7.07%
   - Phone: 8.15%
4. **Priority Issues**:
   - Communication tactics (15.76%), Loan servicing (10.87%), Loan modification (9.78%)
5. **Monthly Trends**:
   - Line chart showing complaint spikes in 2015.

## Key Takeaways
- **High-Volume Companies**: Bank of America and Wells Fargo lead in complaints, indicating a need for improved customer service.
- **Dominant Issues**: Loan servicing and debt collection issues are prevalent, requiring targeted process improvements.
- **Channel Preference**: Web-based submissions dominate (80.98%), suggesting a focus on digital complaint platforms.
- **Resolution Efficiency**: Resolution times worsened in 2016, highlighting potential operational bottlenecks.
- **Prioritization**: Focus on communication tactics and loan-related issues for maximum impact.

## Usage
- **Prerequisites**: Excel or data analysis tools (e.g., Python, R) for processing the dataset.
- **Files**:
  - `Consumer Complaints Case Study.xlsx`: Raw dataset
  - `Report_Task4.xlsx`: Reporting outputs
  - `Report_Task5.xlsx`: Dashboard outputs
- **Instructions**:
  1. Clone the repository.
  2. Open the Excel files to view the analysis.
  3. Use the provided charts and KPIs for further insights.

## License
This project is licensed under the MIT License.
