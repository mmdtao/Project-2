# Project-2
The main script for this project is a jupyter notebook python script titled "ETL_Mini_Project_Starter_Code" and is located inthe Project2 directory. The raw data which will be imported into the script are contained in xlxs files located in the "Resources" folder. The files are named "contacts" and "crowdfunding". When executed, the python script will generate and export four csv files to the "Cleaned_dfs" folder. Please note that there are two files named contacts. One is a cleaned dataframe exported from jupyter notebook. This will be imported into PGAdmin. The other contains raw data which will be imported into jupyter notebooks to be modified. To ensure smooth execution, please follow the instructions in the order in which they are given below.

Instructions:
1. Open the python script titled "ETL_Mini_Project_Starter_Code".
2. Run all cells. This will create and export 4 excel files to the "Cleaned_dfs" folder.
3. Open PGAdmin and create a new database named "crowdfunding_db".
4. Navigate to the "Queries" folder in the Project-2 directory and open "crowdfunding_db_schema".
5. Copy the code from the "crowdfunding_db_schema" script.
6. Go back to PGAdmin, click on "crowdfunding_db" and start a new query.
7. Paste the code from the "crowdfunding_db_schema" script into the new query window.
8. This will create 4 new tables in the database (category, subcategory, campaign, and contacts).
10. Under the schema tab, right click on the category table and import the "category" csv file located in the "Cleaned_dfs" folder.
11. Right click on the subcategory table and import the "subcategory" csv file located in the "Cleaned_dfs" folder.
12. Right click on the contacts table and import the "contacts" csv file located in the "Cleaned_dfs" folder.
13. Right click on the campaign table and import the "campaign" csv file located in the "Cleaned_dfs" folder.
14. Please make sure to import the csv files in the order specified above to avoid any errors.
15. To view the newly created tables, copy and paste the code into individual queries (SELECT * FROM <table name>) from crowdfunding_db_campaign, crowdfunding_db_category, crowdfunding_db_subcategory, crowdfunding_db_contacts, all of which are located in the "Queries" folder. 
16. If you need an overview of the data structures in the crowdfunding_db database, please open the "crowdfunding_db_ERD" png file.
    
