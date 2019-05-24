# Topos-Data-Engineer-Intern

# Files
1. Jupyter Notebook for ETL process
2. Exported Data in CSV format

# Project Description
In this assignment we are going to visit https://en.wikipedia.org/wiki/List_of_United_States_cities_by_population website and extract the data about each cities which is displayed in the first table of the page. There are links to each city in that page which then gives us extra information about the city and has various other information, we are going to extract first short paragraph about the city i.e City Description and the list of Zipcodes available in that particular city and export the complete data to BigQuery importable csv file.

### Note: Please specify the path to csv_Path variable where you want to export yore CSV file in your system

# Steps to upload data to Google Clouds BigQuery DataWarehousing Solution
1. Run the jupyter notebook to create csv file at desired location
2. Go to Google Cloud's BigQuery page from your account 
3. Create a Project if there is no project in your account else select the project in which you wish to upload the data
4. Create the data-set if there is no data-set in your project else select the data-set under which you want your data 
5. Once the data-set is selected Go-to Create Table
6. In Source Select create table from as - Upload
7. Browse the path where you have exported your CSV file
8. Select <b>File Format</b> as CSV
9. Go-to Table Name and Give the Table the desired name. Preferable Name: US_City_Data
10. Go-to Schema => And select the Checkbox under Auto-detect Schema and input parameters 
