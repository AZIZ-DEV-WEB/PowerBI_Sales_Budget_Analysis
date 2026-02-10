\# PowerBI Sales \& Budget Analysis



This project demonstrates data transformation, modeling, and visualization in Power BI using two datasets: AdventureWorks\_Database and Budget.



\## Features



\- Data cleaning and transformation for the Budget dataset:

&nbsp; - Reformatted headers and removed intermediate calculation rows

&nbsp; - Removed GrandTotal column

&nbsp; - Pivoted date columns into `Month` and `BudgetAmount`

&nbsp; - Corrected data types (Text, Integer, Date, Decimal)



\- AdventureWorks\_Database:

&nbsp; - Imported tables and verified data

&nbsp; - Standardized column names in uppercase



\- Data modeling:

&nbsp; - Created relationships between Sales, Calendar, and Budget tables

&nbsp; - Ensured model consistency and integrity



\- Interactive reports:

&nbsp; - KPI cards for Sales, Budget, Variance, and Variance%

&nbsp; - Visualizations of Sales vs Budget by Category and Month

&nbsp; - Variance analysis by Category

&nbsp; - Temporal trends of Sales and Budget

&nbsp; - Detailed product and customer tables



\## Measures Created



\- `Sales = SUM(Sales\[SalesAmount]) + SUM(Sales\[TaxAmt])`

\- `Budget = SUM(Budget\[BudgetAmount])`

\- `Variance = \[Sales] - \[Budget]`

\- `Variance% = DIVIDE(\[Variance], \[Budget])`



\## Tools Used



\- Power BI Desktop

\- DAX (Data Analysis Expressions)



