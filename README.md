# Adventure-Works-SQL-practice-Questions
## Adventure Works Database
Adventure Works is a fictitious sample database that was created by Microsoft for educational and demonstration purposes. It is often used as a sample database in various Microsoft products and technologies, such as SQL Server, Azure SQL Database, and Power BI.

The Adventure Works database represents a fictional bicycle manufacturing company and contains a set of tables that store information related to different aspects of the company's operations. These tables include data about products, customers, orders, employees, vendors, and more. The database schema is designed to showcase various database concepts and features, making it a useful tool for learning and practicing database management.

The file can be downloaded here https://github.com/Microsoft/sql-server-samples/releases/download/adventureworks/AdventureWorks2022.bak

## Questions and the solutions
### 1. Retrieve from product tables all colours except blanks,Red, silver/black and white with unit price between £75 and £750. Rename the column standard cost price. Sort price in ascending order.
### 2. Find all male employees born from 1962 to 1970 and their hire date greater than 2001 and female employees born between 1972 to 1975 and hire date between 2001/2002.
### 3. Create a list of 10 most expensive products from the Production.Product table that have a product number beginning with ‘BK’. Include only the product ID, Name and colour.
### 4. Create a list of all contact persons where the first 4 characters of the front of the last name is the same as the first four characters of the email address in small letters. Also, for all contacts whose first name and the last name begin with the same characters, create a new column called full name combining first name and the last name only. Would also like information on the length of the full name?
### 5. If commission is calculated based on 14.790% of standard cost, extract product item and calculate the margin if standard cost is increased or decreased as follows for each product colours as follows: Black +22%, Red - 12%, Silver +15%, Multi +5% White (2) times original price divided by the square root of the margin price, while other colours remain the same.
### 6. Return all product subcategory record that take an Average 3 days or longer to manufacture.
### 7. Create a list of product segmentation by defining criteria that places each item in a predefined segment as follows. If price gets less than £200 then low value. If price is between £201 and £750 then mid value. If between £750 and £1250 then mid to high value else higher value. For colours “black, silver and red” products.
### 8. How many Distinct Jobtitle are available in Employee table
### 9. Use employee table and calculate the ages of each employee at the time of hiring
### 10. How many employees will be due a long service award in the next 5 years if long service is 20 years?
### 11. How many more years does each employee have to work before reaching sentiment. If sentiment age is 65? 
### 12. Derive the week day, month name and year from the hire. Also how long has each female employee been employed?
### 13. Implement new price policy on the product table base on the colour of the item If white increase price by 8%, If yellow reduce price by 7.5%, If black increase price by 17.2%, If multi, silver, silver/black or blue take the square root of the price and double the value. Column should be called Newprice, while other colours remain thesame. For each item, also calculate commission as 37.5% of newly computed list price.
### 14. I would like information Sales.Person and their sales quota. For every Sales person should have a FirstName, LastName, HireDate, SickLeave Hours and Region where they Work
### 15. Using adventure works, write a query to extract a data table that must contain the following variables:  Product name  Product category name  Product subcategory name  Sales person  Revenue  Month of transaction  Quarter of transaction  Region
### 16. Produce an up to date report on all products sold between January and December 2007, showing number of sales, sales proportions the financial performance. Ensure your analysis can be used to determine whether there is growth or decline on any of the product lines.
#### Compare 2007 and 2008 figures to highlight year on year results.
#### Reproduce the report at higher levels such as Product category and sub category.
#### What key products are the drivers of performance?
#### If we would like to discontinue any product sub categories due to poor outcomes, what would this be? 

