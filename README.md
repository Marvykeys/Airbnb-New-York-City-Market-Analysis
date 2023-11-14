# Airbnb-New-York-City-Market-Analysis
## Scope :page_with_curl:
This report is focused on analysing Airbnb's New York City Market, which is made up of 3 datasets, airbnb_last_review.csv, airbnb_price.csv and airbnb_room_type.xlsx. 
Useful insights were obtained and key questions were answered.
## Data Design :bar_chart:
The raw data provided were downloaded in CSV and Xlsx file formats from kaggle.com and it came with some of its contents being improperly formatted hence, a proper data cleaning had to be done.
## Import and Transform Data :scroll:
After downloading the data which was in CSV file format, I imported the data into Microsoft Power BI being the tool I’ll be using for analysis and visualization.                             pic 1
##
I clicked on “All Files” to be able to load both CSV AND XLSX.  
    pic 2
 ##
 I clicked on “Load” to load the data.  
    pic 3
 ##
Now, you see below, All 3 datasets are loaded.                                                                                                                                 
    pic 4
 ## Data Cleaning :shower:
 I started the cleaning process by editing the airbnb_price.csv dataset in the data view section.
    pic 5
 ##
 Next, I replaced the word "dollar" which is attached to every number value on the price column with blanks so only the numbers are left.      
    pic 6
 ##
 Now, the "price" column has got only numbers on each row.                                                                           
    pic 7
 ##
 I changed the data type for the "price" column from Text to Whole Number. 
    pic 8
 ##
 I changed the format for the "price" column from Whole Number to Currency.                                                                                                             
    pic 9
 ##
 Now, the "price" column has got numbers with the $ currency sign on each row.
    pic 10
 ##
 I checked the airbnb_room_type.xlsx dataset and found that on the room_type column, some rows begin with lowercase letters and others with uppercase letters. 
    pic 11
 ##
 I changed the format for all entries in the room_type column to be all lowercase.
    pic 12

## Analysis Questions Answered :bar_chart:

a) What is the average price per night of an Airbnb listing?

b) How does the average price of an Airbnb listing, per month, compare to the private rental market?

c) How many adverts are for private rooms?

d) How do Airbnb listing prices compare across the five NYC Boroughs?                                         

 ## THE FINAL INTERACTIVE DASHBOARD :art:
 https://app.powerbi.com/view?r=eyJrIjoiOWIyYzc0OWQtZTE1OC00MGNkLTg4ZmMtYmU3YzhiOWY0YWRlIiwidCI6IjE5NmUyMGNhLWY4NDgtNGRiYy1iODEyLTAxMjVjZGE4NjQ5NCJ9
