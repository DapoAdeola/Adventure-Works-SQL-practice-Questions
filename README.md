# Adventure-Works-SQL-practice-Questions
## Adventure Works Database
Adventure Works is a fictitious sample database that was created by Microsoft for educational and demonstration purposes. It is often used as a sample database in various Microsoft products and technologies, such as SQL Server, Azure SQL Database, and Power BI.

The Adventure Works database represents a fictional bicycle manufacturing company and contains a set of tables that store information related to different aspects of the company's operations. These tables include data about products, customers, orders, employees, vendors, and more. The database schema is designed to showcase various database concepts and features, making it a useful tool for learning and practicing database management.

The file can be downloaded here https://github.com/Microsoft/sql-server-samples/releases/download/adventureworks/AdventureWorks2022.bak

## Questions and the solutions
### 1. Retrieve from product tables all colours except blanks,Red, silver/black and white with unit price between £75 and £750. Rename the column standard cost price. Sort price in ascending order.
SELECT Color, StandardCost AS StandardCost_Price
FROM Production.Product
WHERE  Color != 'Red' AND Color!='Silver/Black' AND Color!='White' AND Color IS NOT NULL AND StandardCost BETWEEN 75 AND 750
ORDER BY StandardCost

Color	StandardCost_Price
Black	77.9176
Black	92.8071
Black	96.7964
Black	104.7951
Black	108.7844
Black	110.2829
Black	113.8816
Black	122.2709
