# DNN-to-classify-SKUs  
  
  This code to build an DNN to classify SKUs in a warehouse into categories, using the multi-dimension classification approach.  
  
  ## Table of contents ##  
  
    
  ## 1. Dataset ##
  This project used the dataset [Historical Sales and Active Inventory](https://www.kaggle.com/datasets/flenderson/sales-analysis "Historical Sales and Active Inventory")  
  
  ## 2. Inpiration ##  
  This project used the multi-dimension classification approach, based on the Pareto Law, combining ABC analysis on the values of SKUs and FMR analysis on the demands of SKUs.  
  ### 2.1. ABC analysis ###  
  Using ABC analysis, this project grouped SKUs into categories based on their values and amounts of SKUs inside the warehouse   
  Group A: highest-values and lowest-amounts SKUs  
  Group B: medium-values and medium-amounts SKUs  
  Group C: lowest-values and lowest-amounts SKUs  
  ### 2.2. FMR analysis ###  
  Based on the same approach, SKUs were categorized based on their demands
  Group FF: highly frequently order  
  Group F: freuqently order  
  Group M: medium order 
  Group R: rarely order  
  ### 2.3. ABC/ FMR analysis ###  
  Combining ABC analysis and FMR analysis, this project used the multi-dimension classification approach.   
  ![image](https://user-images.githubusercontent.com/110728751/183285395-e5d53d73-c57f-4819-9d9b-1baf728c4722.png)  
    
  ## 3. Preprocessing data ##  
  For ABC analysis, reference to [ABC Analysis of Active Inventories](https://www.kaggle.com/code/danavg/abc-analysis-of-active-inventory/notebook "ABC Analysis of Active Inventories"), I used this code to label SKUs.  
  For FMR analysis, I added columns of demands to the dataset then classify and label SKUs.  
  All null data were deleted.  
  
  ## 4. Liscence ##
  
  

  
