# Topos-Data-Engineer-Intern

# Files:
1. Data_Engineer_Assessment.ipynb (Jupyter Notebook for ETL process)
2. US_City_Data.csv (Exported Data in CSV format)

# Project Description:
In this assignment we are going to visit https://en.wikipedia.org/wiki/List_of_United_States_cities_by_population website and extract the data about each cities which is displayed in the first table of the page. There are links to each city in that page which then gives us extra information about the city and has various other information, we are going to extract first short paragraph about the city i.e City Description and the list of Zipcodes available in that particular city and export the complete data to BigQuery importable csv file.

### Note: Please specify the path to csv_Path variable in the jupyter notebook where you want to export your CSV file in your system

# Steps to upload data to Google Clouds BigQuery DataWarehousing Solution:
1. Run the jupyter notebook to create csv file at desired location
2. Go to Google Cloud's BigQuery page from your account 
3. <b>Create</b> a <b>Project if there is no project</b> in your account else <b>select the project</b> in which you wish to upload the data
4. <b>Create</b> the <b>data-set</b> if there is no data-set in your project else <b>select</b> the <b>data-set</b> under which you want your data 
5. Once the data-set is selected Go-to <b>Create Table</b>
6. In <b>Source</b> Select create table from as - <b>Upload</b>
7. <b>Browse</b> the path where you have exported your <b>CSV file</b>
8. Select <b>File Format</b> as <b>CSV</b>
9. Go-to <b>Table Name</b> and <b>Give the Table the desired name</b>. Preferable Name: US_City_Data
10. Go-to <b>Schema</b> => And <b>select the Checkbox under Auto-detect Schema and input parameters</b> 
