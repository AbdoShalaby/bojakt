## Stockholm Hosuing Demand Analysis

This analysis aims to show the average days required to sell a property in Stockholm are changing during the last 18 months. 

### DataSet schema:
id: property id
publsih_date: The date when the property has been published for sale
Sold_Date: The date when the property is sold
days_to_sell : The different between publsih date and sold date
AskingPrice: The asking price of the property
Munacipality_name: The Munacipality of the property
property_type: The type of the property (i.e. villa, Bostadsratt, Radhus)

### Example of the data:
   id publish_date   sold_date  days_to_sell  AskingPrice munaciplity_name  \
0   6   2016-03-27  2016-04-30            34    4700000.0        Stockholm   
1   9   2016-03-27  2016-04-07            11    2395000.0        Stockholm   
2  11   2016-03-27  2016-04-16            20    1650000.0         Botkyrka   
3  15   2016-03-27  2016-04-07            11    1495000.0            Nacka   
4  20   2016-03-27  2016-05-14            48    1750000.0        Stockholm   

  property_type  
0        Radhus  
1   Bostadsratt  
2   Bostadsratt  
3   Bostadsratt  
4   Bostadsratt
