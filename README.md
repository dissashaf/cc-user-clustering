# CC User Clustering
**Exercises**  
_dissashaf | May 9, 2023_

This project focuses on building a clustering model to segment credit card users into several groups. Customer segmentation enables more targeted strategies related to marketing, risk control, customer retention, and other business needs.

---

**Problem Statement**

A clustering model is required to perform customer segmentation using credit card data collected over the last six months.

---

**Dataset**

The dataset used is **“Credit Card Information”**, which contains various attributes such as credit limit, balance, purchase behavior, and other financial indicators.  
It consists of **19 columns**, each representing a specific characteristic of the credit card holder.

Below is the table description:

| Table Name                 | Column Name                         | Data Type | Description                                                                                           |
|----------------------------|-------------------------------------|-----------|-------------------------------------------------------------------------------------------------------|
| credit-card-information    | CUST ID                             | INT64     | Identification of the credit card holder                                                              |
| credit-card-information    | BALANCE                             | FLOAT64   | Remaining balance available for purchases                                                             |
| credit-card-information    | BALANCE FREQUENCY                   | FLOAT64   | Frequency of balance updates, scored 0–1                                                              |
| credit-card-information    | PURCHASES                           | FLOAT64   | Total amount of purchases made                                                                        |
| credit-card-information    | ONEOFF PURCHASES                    | FLOAT64   | Maximum single purchase amount                                                                        |
| credit-card-information    | INSTALLMENTS PURCHASES              | FLOAT64   | Total amount of installment purchases                                                                 |
| credit-card-information    | CASH ADVANCE                        | FLOAT64   | Cash advance received by the user                                                                     |
| credit-card-information    | PURCHASES FREQUENCY                 | FLOAT64   | Purchase frequency, scored 0–1                                                                        |
| credit-card-information    | ONEOFF PURCHASES FREQUENCY          | FLOAT64   | Frequency of single large purchases (scored 0–1)                                                      |
| credit-card-information    | PURCHASES INSTALLMENTS FREQUENCY    | FLOAT64   | Frequency of installment purchases (scored 0–1)                                                       |
| credit-card-information    | CASH ADVANCE FREQUENCY              | FLOAT64   | Frequency of cash advance usage                                                                       |
| credit-card-information    | CASH ADVANCE TRX                    | INT64     | Number of cash advance transactions                                                                   |
| credit-card-information    | PURCHASES TRX                       | INT64     | Number of purchase transactions                                                                       |
| credit-card-information    | CREDIT LIMIT                        | FLOAT64   | User’s credit card limit                                                                              |
| credit-card-information    | PAYMENTS                            | FLOAT64   | Total payment amount made by the user                                                                 |
| credit-card-information    | MINIMUM PAYMENTS                    | FLOAT64   | Minimum payment amount made                                                                           |
| credit-card-information    | PRC FULL PAYMENT                    | FLOAT64   | Percentage of full payment completed by the user                                                      |
| credit-card-information    | TENURE                              | INT64     | Duration of credit card usage                                                                         |

---

**Key Questions & Assumptions**

This project explores several questions and assumptions, including:

1. **What does the data distribution look like, and what initial findings stand out?**  
2. **What insights can be extracted from the resulting customer segments?**  
3. **What are the strengths and limitations of the clustering model in relation to the business domain?**  
4. **What improvements can be made in future iterations, whether in modeling or the overall process?**

---
