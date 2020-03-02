# Algoritma Talent Search

This is a part of Algoritma Talent Search assessment process. Please download the repository by clicking the `Download` button on top of the page to retrieve the dataset we will be using for the assessment process. The dataset is owned by a retail company by  storing the orders information.

You can get the CSV file stored within the folder under `retail.csv` file. The data has 9994 observations with 14 variables. Here is the list of the column description:  
`Order.ID` : Id of order.
`Order.Date` : Order of Date.
`Ship.Date` : Date of shipping.
`Ship.Mode` : type of shipment.
`Customer.ID` : Id of Customer.
`Segment` : Customers segment.
`Product.ID` : Id of Product.
`Category` : has 3 levels "Furniture","Office Supplies","Technology"
`sub.category` : more spesific categories
`Product.Name` : Name of product that were sold.
`Sales` : How much earning of each sales.
`Quantity` : Quantity item sold.
`Discount` : How much Discount were given for each sales.
`Profit` : How much gain company earn for each sales.

1. Apparently, the company has 4 different modes of shipping; `First Class`, `Second Class`, `Standard Class` and `Same Day`. 
Suppose, they want to perform an efficiency by eliminate one of the shipping mode which has the **least** shipment in the last two years.
Which of the shipment mode do you think would be the most reasonable to eliminate?
    - [ ] First Class
    - [ ] Second Class
    - [ ] Standard Class
    - [ ] Same Day

2. You were asked to analyze the company's **average daily profit** and found that not all transactions were profitable; a negative value on Profit expresses a loss rather than profit. Based on the analysis, on what date did the company suffer their biggest loss?   
*Hint*: Aggregate your data based on `Order.Date` and find the average daily `Profit`!
    - [ ] 2016-11-25
    - [ ] 2015-01-28
    - [ ] 2016-10-02
    - [ ] 2015-01-10

3. In general, the company is selling three different item categories; `Furniture`, `Office Supplies`, and `Technology`. One day, they want to make a `Furniture` catalog and you were asked to put "Best-Selling Item" section on it.  The "Best-Selling Item" is showing a list of ten Furniture product with the highest total quantity sold. Among the four products below, which one is **INCLUDED** on the list?
    - [ ] GBC Premium Transparent Covers with Diagonal Lined Pattern
    - [ ] Global High-Back Leather Tilter, Burgundy
    - [ ] Global Stack Chair without Arms, Black
    - [ ] Bevis 36 x 72 Conference Tables

4. The company wants to initiate a stock clearance sale and the offered products will be the items from `Office Supplies` category which has total quantity sold below 20. Among four products below, which one is **NOT** on the list?
    - [ ] 4009 Highlighters
    - [ ] Easy-staple paper
    - [ ] Staple envelope
    - [ ] Staples

5. `Home Office` has been the least profitable segment for the company in the past years. Say, the company wants to target more `Home Office` customer by giving 
special offers on products from a sub category which has highest **total Sales** from the particular segment. Which sub category do you think would be suitable for the promotion?
    - [ ] Copiers
    - [ ] Phones
    - [ ] Binders
    - [ ] Fasteners

6. The dataset held the company historical transactions from `2014` to `2017`. From all those years, on what year did the company gain their highest `Profit`? *Hint*: Aggregate the data by the year of `Order.Date` and find the yearly **total** Profit!
    - [ ] 2014
    - [ ] 2015
    - [ ] 2016
    - [ ] 2017

7. Throughout 2017, which month appear to be the busiest (has highest number of orders) for the company? *Hint*: Try to count how many unique `Order.ID` made in `2017` (year of `Order.Date`)
    - [ ] September
    - [ ] October
    - [ ] November
    - [ ] December

8. You were asked to perform an analysis on how often a customer makes a purchase from the company historical transactions in the year 2016 and 2017. 
Which customer (`Customer.ID`) are **not** amongst the top five customer with the highest buying frequency? 
*Hint*: Distinct the value of `Customer.ID` and `Order.ID`, then count how many unique order processed by each `Customer.ID`
    - [ ] EP-13915
    - [ ] EH-13765
    - [ ] PK-19075
    - [ ] SH-19975

