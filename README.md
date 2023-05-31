# Bike-Purchase_Excel-Analysis

**Bike Purchases Excel Dashboard**

![image](https://github.com/mukunjufelicity/Bike-Purchase_Excel-Analysis/assets/8385040/91a37343-2814-4a64-85af-ac079f19bd08)


**WORK-THROUGH:**

A. Created different worksheets; separated original data (bike_buyers) from what I was going to be working on (working_sheet), added pivot_table and dahboard sheets.

B. working_sheet
- Cleaned dataset; removed duplicates

-Defined letters under Marital Status & Gender columns
       Marital Status: S to Single, M to Married       Gender: F to Female, M to Male

- Changed value of Income column from Number to Currency and reduced number of decimals

-Inserted Age Brackets column to work better with range of ages other than a individual ages
      Formula: =IF(L2>54, "Old", IF(L2>=31, "Middle-Aged", IF(L2<31, "Adolescent", "Invalid")))

C. pivot_table
-Pivot Table 1: Displays the Average Income of those who purchased and didn't purchase bikes

-Pivot Table 2:Shows the Commute Distance of those who purchased and didn't purchase bikes

-Pivot Table 3: Displays the Age of those who purchased and didn't purchase bikes


D. dashboard
-Placed all the pivot tables together and added slicers (Marital Status, Region, Education) to compare the data displayed.
