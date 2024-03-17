# Global super store sales for the year 2023 - Dashboard

### Dashboard Link : https://app.powerbi.com/view?r=eyJrIjoiY2UxMWNkNmMtZDdkOC00ZGJjLWFlMzUtOWVjZmQyMzQ3ZDAxIiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9

## Problem Statement

This dashboard helps the shop owner to understand their customers and their shop better. It helps the owner to know if their customers are satisfied with their product and their pricing. Through different ratings, they get to know their improvement region, & thus they can improve their products by identifying their customers. It also lets them know the salesperson, no.of.items and its cost, thus since by using this dashboard they have identified this problem, they can further sale their products based on their customers and their region.

### Steps followed 

- Step 1 : open Power Bi > within view ribbon tab > check whether the Gridline & snap to grid is enabled.
- Step 2 : Load & import data from excel.
- Step 3 : Analyse the data & add new column,
for creating new column following DAX expression was written;
Revenue = item.cost * no.of.items
- Step 4 : next to that add a new column, 
for creating new column following DAX expression was written;
Margin = revenue * 20% (i.e 0.2)
- Step 5 : Let's start to create a visualizations..
- Step 6 : In the report view, under the view tab, theme was selected.
- Step 7 : Adding a text box for the dashboard.
- Step 8 : Creating a cluster column chart to analyze data according to Sum of Margin by Month .
- Step 9 : Creating four donet chart to analyze the data according to Sum of no.of.items by Customer, Sum of Margin by region, count of region by customers & finally for the count of salesperson  by product 
- Step 10 : Creating a two pie chart to analyze the data according to count of product by region & count of salesperson by region.
- Step 11 : slicer are used to analyze data by specific mentioned below,

  (a) Customers

  (b) salesperson
  
  (c) region
  
  (d) Product 
  
- Step 12 : Card chart was created for representing the field of sum of item.cost & sum of margin.

Snap of Card ,

sum of item.cost 

![sum of cost ](https://github.com/ravicod/Power-BI-Projects/assets/163747594/3b648ccb-c905-4574-b906-0d5dea061f0a)

sum of margin

![Sum of margin](https://github.com/ravicod/Power-BI-Projects/assets/163747594/be0bb850-09fa-4d09-bf04-2908a6fc561c)


- Step 13 : Gauge chart was created for representing the value of sum of revenue & sum of item cost. 

Snap of Gauge,

sum of revenue

![Sum of revenue](https://github.com/ravicod/Power-BI-Projects/assets/163747594/cafee9a1-0544-43a9-bfca-709f08b01cc3)


- Step 14 : Creating a line chart to analyse the sum of margin by year & Month.
- Step 15 : Creating a cluster column chart to analyze the data of sum of margin and sum of item cost by salesperson.

# Snapshot of publish message
         
![Publish_Message](https://github.com/ravicod/Power-BI-Projects/assets/163747594/90846dec-35b5-4299-8e0e-27e808605773)


# Snapshot of Dashboard (Power BI Service)

![dashboard_snapo](https://github.com/ravicod/Power-BI-Projects/assets/163747594/f64f0242-e635-40ec-8851-26e0e73f8a8f)



 
 # Report Snapshot (Power BI DESKTOP)

 
![Dashboard_upload](https://github.com/ravicod/Power-BI-Projects/assets/163747594/22f90d47-4940-433b-95f2-28bef0d85cc1)


# Insights

A single page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;

### [1] sum of revenue = 2.36M

           
### [2] sum of margin = 472.36k


### [3] sum of item cost = 247k

where the items are ,
  
      a) 7 Seater sofa 7 Recliner
      b) Bamboo Foam Coach 
      c) Glass Center Table
      d) Marrble Dining Table
      e) Wodden Coffee Table

 ### [4] Some other insights
 
 ### Region 

       1) North East 
       2) North West 
       3) South East
       4) South West
 
 ### Customers
 
       1) Designer Homes
       2) Elite Designer
       3) Home India 
       4) Metro Emporium 
       5) Style and Spa 
  
### salesperson
   
        1) Arora, Megha
        2) Arya, Gunjan 
        3) Bains, Gaurav
        4) Bajaj, Birbal
        5) Dube, Akanksha
        6) Kale, Shipra 
        7) Malik, Dev 
        8) Puri, Silkey 
        9) Roy, Ajeet 
        10) Saini, Gargi 
        11) Sharma, Varun 
        12) Sinha, Annop
