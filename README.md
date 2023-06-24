# DataWarehouse
#ETL-project
We used a datasets from the public platform Kaggle which lead us to the Order Management website. The data in included the following information:

Sales and benefit
Customer information
Order information and delivery information

The fields of interest include the following:

Customer
Order
Detail Order
Delivery
Department and category

The following sources for our datasets used:



Transformation
In order to transform the public data and use it in our study we performed the following:

Used Pandas functions in Jupyter Notebook to load CSV files.
Reviewed the files and transformed into data frames.
check the field data type.
Check all of fieds which has any error data and remove that columm if they had too much errors.
Remove all of rows if they have some errors.
Didn't use the operator’s column and the address column due to missing information which was not relevant to the focus of this study
Idenfied duplicates by doing an inner merge on the incident id column across data sets.
split theShipping date (DateOrders) column into 3 columns month, quarter, year and remove the date column.
Export to csv file to share for my team mate

The last step was to transfer our final output into a Database. We created a database and respective table to match the columns from the final Panda's Data Frame using My SQL database using cursor to store our original clean data sets. We reconnected to the database and generated additional tables for the data frames.

Summary
There were some limitations to our findings due to the data available. However, we were able to address our hypothesis quetion in our intial project proposal listed in the ETL Project Final Write UP.
Make OLTP model.
