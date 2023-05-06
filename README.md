# Data-Cleaning-using-SQL-project
The Data Cleaning using SQL project for Sales of Housing(NashvilleHousing market) Data involves several skills that are essential for cleaning and transforming data. The project aims to convert the SaleDate column to a Date type, populate Property Address data that is null, break out Address into individual columns (Address, City, State), change Y and N to Yes and No in the "Sold as Vacant" field, remove duplicates using windowing functions such as row number, use CTE to remove duplicates finally, and delete unused columns.

To begin with, the SaleDate column needs to be converted to a Date type. This conversion will make the data more readable and useful. To do this, we can use the CAST or CONVERT function in SQL Server.

Next, we need to populate Property Address data that is null by using duplicated records. We can use the UPDATE statement with a subquery that selects the first record with a non-null address.

After this step, we need to break out Address into individual columns (Address, City, State) using substring and charindex functions. We can also use parsename and replace functions to extract specific parts of the address.

The "Sold as Vacant" field contains Y and N values that need to be changed to Yes and No for accuracy. We can use distinct values to know what values exist in this field and then use case when statements to replace them.

Removing duplicates is another important step in data cleaning. We can use windowing functions such as row number along with CTEs (Common Table Expressions) to identify duplicate records and remove them from our dataset.

Finally, we need to delete unused columns from our dataset. This will make our data more manageable and easier to work with.

In conclusion, Data Cleaning using SQL is an essential skill for anyone working with large datasets. By following these steps outlined above for Sales Housing Data project in Microsoft SQL Server environment , we can transform raw data into clean and usable data that can be used for analysis and decision-making.
