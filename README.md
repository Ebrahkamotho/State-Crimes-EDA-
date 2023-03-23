# Crimes Dataset EDA
This dataset contains information about crimes reported in the city of Los Angeles from 2020 to present. 
The dataset includes various attributes such as crime category, date and time of occurrence, location, and status of the case.

# Dataset source
 https://catalog.data.gov/dataset/crime-data-from-2020-to-present
  
  
# Data Cleaning
The following cleaning steps were performed on the dataset:

1. Dropping unnecessary columns such as 'DR_NO', 'Rpt Dist No', 'Crm Cd 2', 'Crm Cd 3', 'Crm Cd 4', 'Cross Street', and 'Mocodes'
2. Filling null values in 'Weapon Used Cd' and 'Weapon Desc' columns with 'not recorded'
3. Dropping rows with null values
4. Filling null values in 'Vict Sex' and 'Vict Descent' columns with 'not recorded'
5.Converting 'Date Rptd' and 'DATE OCC' columns to datetime format
6. Extracting the month column from 'DATE OCC' column

# Exploratory Data Analysis
The following visualizations were created to gain insights from the dataset:

- Bar plot showing the count of crimes reported by area
- Donut chart showing the distribution of crimes by Part 1-2 categories
- Line plot showing the trend of crimes reported by month
- Bar plot showing the count of crimes reported by weapon type
- Pie chart showing the distribution of crimes by status
- Stacked bar plot showing the distribution of crimes by status and area
- Map visualization showing the location of crimes reported in the city of Los Angeles

# Conclusion
The dataset provides valuable information about the crimes reported in the city of Los Angeles from 2020 to present. 
The EDA provides insights into the distribution of crimes by area, category, and status. 
It also shows the trend of crimes reported by month and the location of crimes on a map. 
The dataset can be further analyzed to identify patterns and trends that can help in preventing crimes and improving the safety of the city.
