### PROJECT TITLE: HR DATA ANALYSIS
### PROJECT OVERVIEW
This project provide an analysis of HR Data using Power BI,it includes metrics like monthly income, monthly rate, hourly rate,daily rate
### TOOLS USED
1.   Power BI
  - Power Business Intelligent
  -  Data visualisation
  -  Report
### EXPLORATORY DATA ANALYSIS  
In the initial phase of data cleaning and preparations, I perform the following actions;
  - Data loading and inspection
  - Handling missing variables
  - Data Cleaning and Formatting
  - visualization of key findings

This is where I include some line of code, queries or some of the DAX expressions used during th analysis;   
  1. Connect your data
  . Get the data from the data source
  . Use power query within power BI to clean and transform the data(e.g filter rows,remove duplicates,change data types)
  . Go to view tab to check your column distribution, column quality and column profile before moving on

<img width="609" alt="column quaLITY" src="https://github.com/user-attachments/assets/813e9104-7df5-4fd6-af56-f9dcb3cb9d9c">
   . change data type
   .  promote header by using the first row as header
   .  Add conditional column for attrition count

```power bi
=Table. Add column (#"changed types",Attrition count, each if [Attrition]="Yes"then 1 else 0)
```

  <img width="800" alt="ADD CONDITIONAL COLUMN 1" src="https://github.com/user-attachments/assets/40c871f5-0b07-4d6a-ac1b-330c7ddc4568">
   
2. Build a data model
   . set relationships between tables to allow for more dynamic visualizations
     <img width="527" alt="TEXT BOX 2" src="https://github.com/user-attachments/assets/9e19362f-c360-4b26-a366-97e7da83f6c3">

     
   . use a calculated column, measures,and custom aggregate in DAX to create specific metrics
   <img width="614" alt="RELATIONSHIP " src="https://github.com/user-attachments/assets/fe535950-e61d-44e2-869c-93ba27bf4407">


   5. Create visualizations
   . Bar/column chart
<img width="597" alt="CREATE RELATIONSHIP" src="https://github.com/user-attachments/assets/f8beb7c3-e115-49d9-b0b5-8c148a77506c">

   . Pie/Doughnut chart
   <img width="481" alt="PIECHART AND DOUGHNUT" src="https://github.com/user-attachments/assets/0d395e0d-47ac-4327-9d6d-9b5d3d75556b">

   . Maps
   <img width="353" alt="MAP BASE ON STATE" src="https://github.com/user-attachments/assets/424e7237-fb76-43a2-9f04-ebb49f2a5df1">

7. Interactive Dashboards
   . slicers and filters
   <img width="422" alt="INTRODUCING SLICERS" src="https://github.com/user-attachments/assets/ace2ec22-479a-4091-a41d-7cfecdd40223">

9. Customize and format
  . Theme layout
  . Conditional formatting
   
      <img width="800" alt="ADD CONDITIONAL COLUMN 1" src="https://github.com/user-attachments/assets/d1820e86-e73d-439e-b2b0-8b84c5289b86">

   
