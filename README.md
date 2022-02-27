[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
# Dashboard Exercise 1: Retail Dashboard

## License
This code is hosted in a private repository to regulate access. 
You can share your work under MIT license.
After completing the module host the end product in an open repository.  

## Branch
 Make sure you know your branch of this module.  
 The modules are evolving. 
 Therefore, we create a branch for you when we assign the module.  
 Read `README.md` of your branch.
 
 ARE YOU READING THE RIGHT BRANCH?
 
 If there is any doubt contact DataDisca.
 
 ## 
 
 ## Application
 Note: The following is the basic guid line, you need to make the dashboard user friendly and easy to follow.
1. Download [Online Retail II Data Set](https://archive.ics.uci.edu/ml/datasets/Online+Retail+II). URL:https://archive.ics.uci.edu/ml/datasets/Online+Retail+II
1. Read the data descriptions given on the download website 
1. Create a dashboard with the following features:  
      
    * Selections at the top:
        Year 2009, 2010, 2011, 2012 or all. All is the default  
        Top N: N = 10 default, 10, 20,50 and 100 are the possible values        
    * Left Top:  
        Top N products based on the quantity barchart  
        Below the plot:   Show what percentage of the total quantity covered by the top N  
        Tool tip: Number, percentage from the total quantity,percentage from the total price         
    * Right Top:  
        Top N products based on the total revenue barchart  
        Below the plot: Show what percentage of the total price (revenue of the item) covered by the top N
        Tool tip: Number, percentage from the total quantity,percentage from the total price
    * Left Bottom:  
        Top N Customers based on number of invoices: Bubble chart   
        Below the plot: Show what percentage of the total covered by the top N  
        Tool tip: Number, percentage from the total quantity,percentage from the total price, Customers country for the most purchases
    * Right Bottom:     
        Top N Customers based on total price : Bubble chart   
        Below the plot: Show what percentage of the total covered by the top N  
        Tool tip: Number, percentage from the total quantity,percentage from the total price, Customers country for the most purchases

2.  Create a dashboard with the following features:
    * Selections at the top:
        Year 2009, 2010, 2011, 2012 or all. All is the default
    * Left Top:  
        A table with Stock codes, descriptions, total quantities and total prices based on the revenue order by default, 
        but sortable by the other fields         
        A row can be selected at a time, then the remaining graphs should change for the selection. If not selected the total will show. 
    * Middle Top:  
        A pie chard for quantities in each year
        Tool tip: Number, percentage from the total quantity,percentage from the total price
    * Right Top:  
        A pie chard for revenues in each year
        Tool tip: Number, percentage from the total quantity,percentage from the total price    
    * Middle Left:
        Time series quantity plot with 1 year forecast, with weekly granularity. Different colour for the forecast
        Tool tip: Number, revenue
    * Middle right:     
        Time series Total price plot with 1 year forecast, with weekly granularity. Different colour for the forecast
        Tool tip: Number, revenue
    * Bottom Full Width:  
        Radio button pair to select the quantity or total price, 
        and below that a world map with colours based on the values for the countries.
        Tooltips should show quantity, total price, average price, number of invoices, number of customers 
         
## Sponsor
DataDisca Pty Ltd, Melbourne, Australia

[https://www.datadisca.com](https://www.datadisca.com)

        
          
        
    
 
