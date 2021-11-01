# Kickstarting with Excel

## Overview of Project

### Purpose
   To analyze the relation of campaign with launch date and goals. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
   Created a pivot table with columns based on Months. I used Parent Category as a filter, and after the theater is selected the respective data is displayed. And then I distributed the outcomes into successful, failed and canceled categories. 

   ![1](https://user-images.githubusercontent.com/92698873/139637595-7c64cfe0-a012-4357-9985-7fbc430eb4d2.PNG)
   
   ![2](https://user-images.githubusercontent.com/92698873/139637604-5bed83db-23e6-473b-8ac6-fbb502c7eb79.PNG)   

### Analysis of Outcomes Based on Goals
   I used COUNTIFS() function to calculate Successful, Failed and Canceled project fields. Also, created a Percentage field for each category to judge the differences between them. Finally created a line chart to visualize the success and failure percentages based on the goals. 
   
   ![3](https://user-images.githubusercontent.com/92698873/139638030-2c4b1b98-6e1e-4cde-8557-8b6aba24e301.PNG)

### Challenges and Difficulties Encountered
   I was unable to create a pivot table and I overcame the difficulty by understanding the table, it's fields and connecting the requirement.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
    - From the chart it is evident that April, May, June and July have more successful campaign. 
    - Staring with April the the slope take a positive curve, May being a peak of success, starting from July it depreciates. 
    - During the month of May, out of 166 campaigns, 111 has been successful and in the month of June, out of 153 campaigns, 100 have been successful. 
    - The months of October, November and December shows the most failure rates in the campaign. 

- What can you conclude about the Outcomes based on Goals?
    - From the chart, we can recognise that goals with ranges 1000 to 4999 and less than 1000 has the most successful percentage of 76% and 73% respectively. 
    - The ranges 25000 to 24999, 30000 to 34999, 45000 to 49000 and greater than 50000 has the most failure percentage of 20%, 27%, 0% and 13% respectively. 

- What are some limitations of this dataset?
    - In Theater Outcomes dataset, the data is missing the percentages of success and failure. The success and failure percentage can help in analysing the decisions and data outcomes. 
    - In Outcomes Based on Goals dataset there is inconsistency in the distribution of data accross the goals. For example, in the range 45000 to 49999 there is only one data recorded and in the range 1000 to 4999 there are total 534 projects recorded. Therefore we need more project data for the goals which have less number of Total Projects. 

- What are some other possible tables and/or graphs that we could create?
    - In the Theater Outcomes Dataset, a table based on year can be created to show the distribution of data based on each year. 
    - In the Outcome Based on Goals, a Stacked Column chart can be created to help in analysing the data. 
    
