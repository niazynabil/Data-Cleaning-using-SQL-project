# Data-Cleaning-using-SQL-project
Data cleaning is a critical process in data analysis. This project focuses on data cleaning using SQL (Microsoft SQL Server) on the Nashville Housing Market dataset. The project involves several essential skills such as converting data types, populating null values, breaking out columns, changing values using case when statements, removing duplicates, and deleting unused columns.

The project aims to enhance your data analysis skills by demonstrating how to clean and transform data using SQL. The first step involves converting the SaleDate column to a Date type using CAST or CONVERT function. Next, we populate Property Address data that is null by using a self join to compare duplicated records and use an update statement to update null values. We also break out Address into individual columns (Address, City, State) to make the data more structured and organized.

Another important step is changing Y and N to Yes and No in the "Sold as Vacant" field. We can use distinct values to know what values exist in this field and then use an update statement with case when condition to replace them.

We also remove duplicates from the dataset using windowing functions such as RowNumber along with CTEs (Common Table Expressions) to identify duplicate records and remove them from our dataset. Finally, we delete unused columns to make the data more concise and streamlined.

By following the step-by-step instructions, code snippets, and examples of SQL queries provided in this project, you can enhance your data analysis skills and make your data more useful for further analysis. This project is a valuable resource for anyone interested in data cleaning and transformation 
