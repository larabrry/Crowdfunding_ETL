# Crowdfunding_ETL
- In this project, an ETL pipeline was built using Python, Pandas, and both Python dictionary methods and regular expressions to extract and transform the data. 
- After the data was transformed, four CSV files were created and the CSV file data were used to create an ERD and a table schema. 
- Finally, the CSV data files were uploaded into a Postgres database.
# Subsections

1. Category and Subcategory DataFrames
2. The Campaign DataFrame
3. The Contacts DataFrame
4. The Crowdfunding Database

## Subsection One: Category and Subcategory DataFrames
The Category and Subcategory DataFrames were created
 by extracting and transforming the `crowdfunding.xlsx` Excel data. 

- The category DataFrame was exported as the `category.csv`.
- The subcategory DataFrame was exported as the `subcategory.csv`.

## Subsection Two: The Campaign DataFrame
The Campaign DataFrames was created
 by extracting and transforming the `crowdfunding.xlsx` Excel data. 
- The Campaign DataFrame was exported as the ` campaign.csv`.

## Subsection Three: The Contacts DataFrame
The Contacts DataFrames was created
 by extracting and transforming the `crowdfunding.xlsx` Excel data using both:
1. Python dictionary methods

2. Regular expressions
- The Contacts DataFrame was exported as the ` contacts.xlsx`.

## Subsection Four: The Crowdfunding Database
The Crowdfunding Database was created by:
1. Inspecting the four CSV files, and then sketching an ERD of the tables by using QuickDBDLinks.

2. Using the information from the ERD to create a table schema for each CSV file.

3. Creating a new Postgres database, named `crowdfunding_db`.

4. Using the database schema to create the tables in the correct order to handle the foreign keys.

5. Importing each CSV file into its corresponding SQL table.
