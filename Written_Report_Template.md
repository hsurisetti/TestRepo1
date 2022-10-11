# Kickstarting with Excel

## Overview of Project
   The overview of the project is to create two new analyses 
           1. outcomes based on goals 
           2. Outcomes based on launch date
### Purpose
The main pupose of the project is to help and visualize Louise to know how different campaigns fared in relation to their launch dates and their funding goals.


## Analysis and Challenges
     I analysed the kickstarter challenge spreadsheet by checking how big is the data and what all the fields represent and what format is assigned to each field.
     Then created the new columns for Parent category, sub category , Date created conversion and Years. These columns are the essential ones to create the pictorial representation of the outputs in form pivot table and charts

### Analysis of Outcomes Based on Launch Date
Theater outcomes by launch date mainly depends of the date created conversion column and outcomes.
    Following items involved in analysis
       - created a pivot table with column labels displaying "successful","failed","canceled"
       - represented row lables with the Months of the date conversion field sorted in ascending order.
    
       - created a pivot chart representing months in the x-axis and outcomes in the y-axis.
       -labelled the title as "Theater outcomes based on launch Date"

### Analysis of Outcomes Based on Goals
 Created the spreadsheet for outcomes based on goals with the below details
    - created each columns based for Number of successful, Number of failed and number of Canceled  based out of subcategory plays and
        . different leves of outcomes ranges like 'less than 1000',between 1000 to 4999 and so on until '50,000 or more' which involved writing excel queries based of COUNTIFS.
        . created a pivot chart and labeled it as 'outcomes based on goal'
        . Represented the outcome ranges in x-asis and percentages on the y-axis for percentage successful, percentage failed, Percentage Failed
     

### Challenges and Difficulties Encountered
  Minor challenges faced
   - In Deliverables 1, my line chart was showing differently compared to the one it should show as per deliverables. Upon changing the style of the line chart it showed exactly as the expected one with outcomes showing in exact order Successful, Failed,Cancelled order.
   - In Delierables 2 , i wanted to create a single query which could apply for the subsequent rows. but since each row had differnt criteria with outcomes 'Successful','Failed','Canceled' respectively for each. i created a single query with fixed data range(selecting F4 for data range) and just modified the outcome criteria for each columns in the row.
   
     

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
    * There are more successful outcomes based on Launch date than failed and canceled.
    * The outcomes increased to the peak during the month of May
    * There are very few of them which were cancelled.

- What can you conclude about the Outcomes based on Goals?
   * Percentage canceled were the least in outcomes based on Goals
   * The percentage of outcomes were successful started out good for lesser outcomes , but fell drastically after 40,000 goal amounts
   * The failed outcomes increased drastically after 40,000 goal amount.

- What are some limitations of this dataset?
   * Some of the limitations that i observed is there is no error control . It si very difficult to find errors in Excel. Also didnt notice any debugging tool or testing frame to inspect whether all cells keep working as expected . Some of them very fixable like DIV/0 where i could use iFERROR to check if there are any errors.
   * Since we are dealing with large data set , scalability is often a concern.
   * Sometimes the speed and performs degrades when running operations of big data sets but didnt notice any crashes so far.
   

- What are some other possible tables and/or graphs that we could create?
     We could also created clustered bar charts, stacked barcharts, different 2D and 3D line and bar charts, histograms.
     
