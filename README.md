# Airbnb-New-York-City-Market-Analysis :chart_with_downwards_trend:
## Scope :page_with_curl:
This report is focused on analysing Airbnb's New York City Market, which is made up of 3 datasets, airbnb_last_review.csv, airbnb_price.csv and airbnb_room_type.xlsx. 
Useful insights were obtained and key questions were answered.
## Data Design :bar_chart:
The raw data provided were downloaded in CSV and Xlsx file formats from kaggle.com and it came with some of its contents being improperly formatted hence, a proper data cleaning had to be done.
## Import and Transform Data :scroll:
After downloading the data which was in CSV file format, I imported the data into Microsoft Power BI being the tool I’ll be using for analysis and visualization.                 

<img width="347" alt="Airbnb 1" src="https://github.com/Marvykeys/Airbnb-New-York-City-Market-Analysis/assets/130637591/57c3ef84-88a1-40b5-bbb3-5482642f265a">

##
I clicked on “All Files” to be able to load both CSV AND XLSX.  

<img width="455" alt="Airbnb 2" src="https://github.com/Marvykeys/Airbnb-New-York-City-Market-Analysis/assets/130637591/30f4dca1-b6e4-41c9-8556-1b6deba9ed86">

##
I clicked on “Load” to load the data.  

<img width="714" alt="Airbnb 3" src="https://github.com/Marvykeys/Airbnb-New-York-City-Market-Analysis/assets/130637591/8cc7986a-b584-4181-a7e2-3623c189ec0a">

##
Now, you see below, All 3 datasets are loaded.                                                                                                                                 

<img width="338" alt="Airbnb 4" src="https://github.com/Marvykeys/Airbnb-New-York-City-Market-Analysis/assets/130637591/74efae57-f1e4-4e07-86e3-0a470cf4edf7">

## Data Cleaning :shower:
I started the cleaning process by editing the airbnb_price.csv dataset in the data view section.

<img width="306" alt="Airbnb 5" src="https://github.com/Marvykeys/Airbnb-New-York-City-Market-Analysis/assets/130637591/f22dc935-4265-460d-ad9f-16995e3a35ef">

##
Next, I replaced the word "dollar" which is attached to every number value on the price column with blanks so only the numbers are left.      

<img width="543" alt="Airbnb 6" src="https://github.com/Marvykeys/Airbnb-New-York-City-Market-Analysis/assets/130637591/39c9767a-f99b-4175-a7c2-ef67b2d9eb1d">

##
Now, the "price" column has got only numbers on each row.                                                                           

<img width="194" alt="Airbnb 7" src="https://github.com/Marvykeys/Airbnb-New-York-City-Market-Analysis/assets/130637591/d2eb05d1-8cc0-4a51-b3d2-085447000508">

##
I changed the data type for the "price" column from Text to Whole Number. 

<img width="392" alt="Airbnb 8" src="https://github.com/Marvykeys/Airbnb-New-York-City-Market-Analysis/assets/130637591/c54fff7d-b418-4bec-9c51-b1726630bdaf">

##
I changed the format for the "price" column from Whole Number to Currency.                                                                                                             
<img width="337" alt="Airbnb 9" src="https://github.com/Marvykeys/Airbnb-New-York-City-Market-Analysis/assets/130637591/534baf7b-2ca8-481f-8916-d3555ff59d8f">

##
Now, the "price" column has got numbers with the $ currency sign on each row.

<img width="297" alt="Airbnb 10" src="https://github.com/Marvykeys/Airbnb-New-York-City-Market-Analysis/assets/130637591/2db82a3c-5c0f-4ca1-b8be-8745bf4854f7">

##
I checked the airbnb_room_type.xlsx dataset and found that on the room_type column, some rows begin with lowercase letters and others with uppercase letters. 

<img width="129" alt="Airbnb 11" src="https://github.com/Marvykeys/Airbnb-New-York-City-Market-Analysis/assets/130637591/b152c5f5-eda7-446d-89f4-f2d4dd0945eb">

##
I changed the format for all entries in the room_type column to be all lowercase.

<img width="399" alt="Airbnb 12" src="https://github.com/Marvykeys/Airbnb-New-York-City-Market-Analysis/assets/130637591/b890d9fd-2a2b-4fcc-ba0e-5010b4424d9d">

## Analysis Questions Answered :bar_chart:

a) What is the average price per night of an Airbnb listing?

b) How does the average price of an Airbnb listing, per month, compare to the private rental market?

c) How many adverts are for private rooms?

d) How do Airbnb listing prices compare across the five NYC Boroughs?                                         

## The Dashboard Before Design

<img width="579" alt="AIRBNB SCREENSHOT" src="https://github.com/Marvykeys/Airbnb-New-York-City-Market-Analysis/assets/130637591/7f9a0168-5945-4cc2-b160-f6b3674d9053">

## THE FINAL INTERACTIVE DASHBOARD :art:
https://app.powerbi.com/view?r=eyJrIjoiOWIyYzc0OWQtZTE1OC00MGNkLTg4ZmMtYmU3YzhiOWY0YWRlIiwidCI6IjE5NmUyMGNhLWY4NDgtNGRiYy1iODEyLTAxMjVjZGE4NjQ5NCJ9
