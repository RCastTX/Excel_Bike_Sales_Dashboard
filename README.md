# Excel_Bike_Sales_Dashboard
## Objective of this Excel project 
My objective in this Excel project was to showcase my skill for cleaning a data set in Excel and then using that cleaned data to make a dashboard with critical insights into that data.

## Creating Sheets
-The first sheet would be the working sheet which would be where I cleaned all the data and made any changes to the data. I like to make a working sheet so that I have the original data safe and untouched in case I need it late. 

-The second sheet was used for where I would create all my pivot tables from my dashboard.

-The third Sheet would be where I compile and create my full dashboard.

![Excel_Bike_Sales_starting_point](https://github.com/RCastTX/Excel_Bike_Sales_Dashboard/assets/128720212/95e0811a-5b00-435f-aa55-b45612747ffc)

## Cleaning the dataset
**1st Step**: Use the remove duplicates data tool to eliminate all duplicates in the dataset.

**2nd Step**: Marital Status column was categorized into two letters, M and S. I used the find and replace tool to change M to Married and S to single so that it was clear what each letter represented.

**3rd Step**: The gender column had single-letter abbreviations for Male and Female, so to clarify the abbreviations I used the Find and Replace tool to change them to Male and Female.

**4th Step**: My Age column was separated by age, but not age groups, so I created a new column and used the IF statement to create three different age groups; 30 and Under, 31-55, and 55 and older.

**IF function used**: 
=IF(L2>55,"55 and older",IF(L2>=31,"31-55", IF(L2<31,"30 and Under","Invalid")))

![Cleaned_Data_on_working_sheet](https://github.com/RCastTX/Excel_Bike_Sales_Dashboard/assets/128720212/dc6dcfc0-4782-444f-a78a-54097aec571e)

## Creating Pivot Tables
-The first pivot table I chose to create was to separate the customers into genders based on their average income. This would allow stakeholders to get an understanding of which gender and income levels are purchasing bikes.

-The second pivot table I chose to create was on customers' commuting distance and whether they purchased a bike. This would give insights into whether commuting distance played a role in a bike purchase.

-The third pivot table I chose to create was one based on customer age brackets. This would allow stakeholders to see exactly which age groups purchased the most bikes.

-The last pivot table I created was bike sales by region. This allows the stakeholders to get a good sense of which regions are purchasing the most bikes.

![first_pivot_table_image](https://github.com/RCastTX/Excel_Bike_Sales_Dashboard/assets/128720212/37bb4caa-ef6f-40e3-aca3-e1cda4d7ec0e)

![second_pivot_table_image](https://github.com/RCastTX/Excel_Bike_Sales_Dashboard/assets/128720212/56cb7401-fe3b-4603-a479-ae783f069692)


## Creating the Dashboard
-The last step in this project was to compile all these pivot tables into a clean and organized dashboard. I copied and pasted all pivot tables to the dashboard sheet and put them into a 4X4 format leaving a column on the left where I would add my last piece to the dashboard.

-I entered 4 slicers on the left of the dashboard that could filter all the pivot tables in real-time. I the filters of marital status, region, education, and number of cars.

![excel_dashboard](https://github.com/RCastTX/Excel_Bike_Sales_Dashboard/assets/128720212/b3416c3e-959f-42b7-be5f-125714e95d57)
