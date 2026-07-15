DAYTONA PEOPLES PHARMACY
Sales & Nomba Payment Reconciliation Report

Report Title: Sales Report vs. Nomba Payment Reconciliation

Prepared By: Accounting & Data Analytics Department

Prepared By: Erigitola Wahab Olatunji

Reporting Period: [14/7/2026]

Date Prepared: [15/7/2026]

1. **Executive Summary**

This report presents the reconciliation of transactions recorded in the Sales Report against payment transactions processed through the Nomba payment platform.

The reconciliation process was developed using Python to automate the comparison between both datasets. Transactions were matched using the following criteria:

Transaction Amount
Payment Method
Transaction Time (Maximum difference of one hour)

The objective of this exercise was to improve payment verification, reduce manual reconciliation efforts, identify unmatched transactions, and strengthen financial controls.

2. **Objectives**

The reconciliation was performed to achieve the following objectives:

Verify that sales transactions were successfully received through Nomba.
Detect transactions that could not be matched.
Identify missing or delayed payment records.
Improve the accuracy of daily financial reconciliation.
Reduce manual reconciliation time.
Strengthen internal financial controls.

**Scope**

The reconciliation covered:

Sales Report
Nomba Payment Report


 **Criteria   **         **Description **                        

 Transaction Amount  Payment amounts must be equal       
 Payment Method      Payment methods must correspond     
 Transaction Time    Maximum time difference of one hour 

 4. Reconciliation Methodology

The reconciliation process involved the following steps:

Step 1

Imported both datasets into Python.

Step 2

Performed data cleaning by:

Removing extra spaces
Standardizing column names
Converting transaction dates into datetime format
Converting amount columns into numeric values
Removing invalid records
Step 3

Standardized payment methods.

Step 4

Matched transactions using:

Payment Amount
Payment Method
Time Difference (≤ 1 Hour)
Step 5

Generated three reports:

Matched Transactions
Unmatched Sales Transactions
Unmatched Nomba Transactions



 KPI                       Result 

 Total Sales Transactions     14115
 Total Nomba Transactions    729
 Successfully Matched          21 
 Unmatched Sales             14094
 Unmatched Nomba             708
 
 6. Key Findings

The reconciliation identified several observations:

Successfully Matched Transactions

A total of 21 transactions were successfully matched between the Sales Report and the Nomba payment report based on the defined reconciliation criteria.
Matching payment amount
Matching payment method
Transaction timestamps within one hour

