# ABC Inventory Anlysis
A pre owned bike dealing startup wants to manage their spare parts data in an organized way. For this they instruct their mechanics to register details of each parts used in each bikes. 
 
After few months company wants to apply ABC inventory analysis technique to their spare parts inventory for this they are going to use the data collected so far. As they start analysing their data they found that the cost of several spare parts are overpriced because of wrong data entry. For e.g a 10 mm bolt whose price range between Rs.1-5 is marked as Rs 100. They asked their data analyst to solve this problem.

The data analyst suggest to remove overpriced and underpriced spare parts by removing outliers. But the problem is their are about 5000 categories of spare parts like nits, bolts, visor, barring etc. and so he have to remove outliers by grouping them seperately one by one.  This project involves removal of those outliers an then classifying each categories into A,B and C category by utilizing Bike_data.csv, whose description is given below 

Data columns (total 13 columns): Description 

BikeNumber =           Registration number of bike 

Company =              Bike company name 

Make  =                Bike sub category 

Model =                Model 

Type  =                Further description of bike model 

Year =                 Make year 

Desciption =           Description of spare parts 

Category =              Category of spare parts

Quantity =             Quantity of spare parts 

Parts Out Date =       Out date

Cost Per Part =        Average cost per spare part

Cost Of Parts Used =   Total cost of spare parts 

Month =                Month 

ABC inventory analysis-

ABC inventory analysis is an inventory management technique that utilizes poareto principle to categorize inventory items into three groups A, B and C. Where category A contains those 20% items which contributes to 80% of cost/revenue, and Category B and C contains those 80% items which contributes to 20 % of the total cost/revenue.

Once categorized we can implement different strategies for different classes. For example we can forest the demand of each category items seperately to avoid inventory stock-out. 
