# Adventure-Works-SQL-practice-Questions
## Adventure Works Database
Adventure Works is a fictitious sample database that was created by Microsoft for educational and demonstration purposes. It is often used as a sample database in various Microsoft products and technologies, such as SQL Server, Azure SQL Database, and Power BI.

The Adventure Works database represents a fictional bicycle manufacturing company and contains a set of tables that store information related to different aspects of the company's operations. These tables include data about products, customers, orders, employees, vendors, and more. The database schema is designed to showcase various database concepts and features, making it a useful tool for learning and practicing database management.

The file can be downloaded here https://github.com/Microsoft/sql-server-samples/releases/download/adventureworks/AdventureWorks2022.bak

## Questions and the solutions
### 1. Retrieve from product tables all colours except blanks,Red, silver/black and white with unit price between £75 and £750. Rename the column standard cost price. Sort price in ascending order.
![1](https://github.com/DapoAdeola/Adventure-Works-SQL-practice-Questions/assets/130672823/ee83147f-ba5b-4978-b8f0-d80df48112b4)
![11](https://github.com/DapoAdeola/Adventure-Works-SQL-practice-Questions/assets/130672823/652fb8b6-ed26-4e50-aef8-9e465b93f32f)

### 2. Find all male employees born from 1962 to 1970 and their hire date greater than 2001 and female employees born between 1972 to 1975 and hire date between 2001/2002.
![2](https://github.com/DapoAdeola/Adventure-Works-SQL-practice-Questions/assets/130672823/ae717019-f456-483b-99fc-7329045f6ab7)
![22](https://github.com/DapoAdeola/Adventure-Works-SQL-practice-Questions/assets/130672823/fa369074-e187-456d-a035-7d7714359ac6)

### 3. Create a list of 10 most expensive products from the Production.Product table that have a product number beginning with ‘BK’. Include only the product ID, Name and colour.
![3](https://github.com/DapoAdeola/Adventure-Works-SQL-practice-Questions/assets/130672823/cbb16378-8fa1-47b3-b98b-1befbb9b8696)
![33](https://github.com/DapoAdeola/Adventure-Works-SQL-practice-Questions/assets/130672823/00d990a5-b19a-4dc7-8844-ecaf02bbbe7e)

### 4. Create a list of all contact persons where the first 4 characters of the front of the last name is the same as the first four characters of the email address in small letters. Also, for all contacts whose first name and the last name begin with the same characters, create a new column called full name combining first name and the last name only. Would also like information on the length of the full name?
![4](https://github.com/DapoAdeola/Adventure-Works-SQL-practice-Questions/assets/130672823/3972cdad-63bb-402d-b05e-e38b89920198)
![44](https://github.com/DapoAdeola/Adventure-Works-SQL-practice-Questions/assets/130672823/edcf470c-c458-402a-9345-43245c56ada6)

### 5. If commission is calculated based on 14.790% of standard cost, extract product item and calculate the margin if standard cost is increased or decreased as follows for each product colours as follows: Black +22%, Red - 12%, Silver +15%, Multi +5% White (2) times original price divided by the square root of the margin price, while other colours remain the same.
![5](https://github.com/DapoAdeola/Adventure-Works-SQL-practice-Questions/assets/130672823/91899d2c-8286-43c8-97e0-5a201bbb76b7)
![55](https://github.com/DapoAdeola/Adventure-Works-SQL-practice-Questions/assets/130672823/bb3e5959-eb39-413b-a4a7-717898373d74)

### 6. Return all product subcategory record that take an Average 3 days or longer to manufacture.
![6](https://github.com/DapoAdeola/Adventure-Works-SQL-practice-Questions/assets/130672823/c632f8da-d3b9-4a12-b25a-c074069c73bb)
![66](https://github.com/DapoAdeola/Adventure-Works-SQL-practice-Questions/assets/130672823/45d214a2-c90d-4701-a168-d2b56761cb15)

### 7. Create a list of product segmentation by defining criteria that places each item in a predefined segment as follows. If price gets less than £200 then low value. If price is between £201 and £750 then mid value. If between £750 and £1250 then mid to high value else higher value. For colours “black, silver and red” products.
![7](https://github.com/DapoAdeola/Adventure-Works-SQL-practice-Questions/assets/130672823/031602c9-3a55-456b-a97d-f1dcd72854ad)
![77](https://github.com/DapoAdeola/Adventure-Works-SQL-practice-Questions/assets/130672823/dc8454c8-e609-48de-9d38-ef21b5fa3083)

### 8. How many Distinct Jobtitle are available in Employee table
![8](https://github.com/DapoAdeola/Adventure-Works-SQL-practice-Questions/assets/130672823/900bd84a-2ce6-47d8-bc20-a3bf8c3e1c3f)
![88](https://github.com/DapoAdeola/Adventure-Works-SQL-practice-Questions/assets/130672823/ac052c02-3982-4cac-82d6-165f51fe3033)

### 9. Use employee table and calculate the ages of each employee at the time of hiring
![9](https://github.com/DapoAdeola/Adventure-Works-SQL-practice-Questions/assets/130672823/a14ee6c3-8a7d-47eb-997c-d7477b9912d7)
![99](https://github.com/DapoAdeola/Adventure-Works-SQL-practice-Questions/assets/130672823/de2ca517-9b7c-4d8e-854c-c86790cf1d56)

### 10. How many employees will be due a long service award in the next 5 years if long service is 20 years?
![10](https://github.com/DapoAdeola/Adventure-Works-SQL-practice-Questions/assets/130672823/7cd910dc-e7b0-4cf1-a6a8-943f37232e97)
![1010](https://github.com/DapoAdeola/Adventure-Works-SQL-practice-Questions/assets/130672823/00620891-841c-4105-9102-7b5362e7f338)

### 11. How many more years does each employee have to work before reaching sentiment. If sentiment age is 65? 
![111](https://github.com/DapoAdeola/Adventure-Works-SQL-practice-Questions/assets/130672823/500a5722-84d2-4a69-98bf-2f48c7c81a69)
![1111](https://github.com/DapoAdeola/Adventure-Works-SQL-practice-Questions/assets/130672823/b31ac154-023d-462e-b66d-11d2d5f3db5e)

### 12. Derive the week day, month name and year from the hire. Also how long has each female employee been employed?
![12](https://github.com/DapoAdeola/Adventure-Works-SQL-practice-Questions/assets/130672823/c89afef4-a151-43cd-a288-3ec970aa8b76)
![1212](https://github.com/DapoAdeola/Adventure-Works-SQL-practice-Questions/assets/130672823/a5bbab1d-d125-4ac8-b1d1-9304c5dc4899)

### 13. Implement new price policy on the product table base on the colour of the item If white increase price by 8%, If yellow reduce price by 7.5%, If black increase price by 17.2%, If multi, silver, silver/black or blue take the square root of the price and double the value. Column should be called Newprice, while other colours remain thesame. For each item, also calculate commission as 37.5% of newly computed list price.
![13](https://github.com/DapoAdeola/Adventure-Works-SQL-practice-Questions/assets/130672823/2ed982d0-2a7c-4349-a549-339c5123b195)

### 14. I would like information Sales.Person and their sales quota. For every Sales person should have a FirstName, LastName, HireDate, SickLeave Hours and Region where they Work
![14](https://github.com/DapoAdeola/Adventure-Works-SQL-practice-Questions/assets/130672823/d8a6f0e0-afb8-4545-99cc-eac8a8136f5e)

### 15. Using adventure works, write a query to extract a data table that must contain the following variables:  Product name  Product category name  Product subcategory name  Sales person  Revenue  Month of transaction  Quarter of transaction  Region
![15](https://github.com/DapoAdeola/Adventure-Works-SQL-practice-Questions/assets/130672823/6da98001-922f-48e8-9b99-c053ffff9a28)
![1515](https://github.com/DapoAdeola/Adventure-Works-SQL-practice-Questions/assets/130672823/1b16b696-4353-4384-8a56-943829d644d5)

### 16. Produce an up to date report on all products sold between January and December 2007, showing number of sales, sales proportions the financial performance. Ensure your analysis can be used to determine whether there is growth or decline on any of the product lines.
#### Compare 2007 and 2008 figures to highlight year on year results.
#### Reproduce the report at higher levels such as Product category and sub category.
#### What key products are the drivers of performance?
#### If we would like to discontinue any product sub categories due to poor outcomes, what would this be? 

