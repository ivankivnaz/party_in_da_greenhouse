## GreenhouseAutomation (core)
- trigger watering for specified period of time
- schedule watering for specified period of time
- notify that the watering has been finished
- collect environment data: temperature, humidity ... (perhaps can be extracted into its own context later)

all those tasks might be configured/triggered via mobile/web ui

### Basic schema
![image](https://drive.google.com/uc?export=view&id=1buCCjQNNeRVUTDENRBze5V1333_2JLoC)

### Basic sequence diagram
![image](https://drive.google.com/uc?export=view&id=1gqwKzHv23vl0-EAk1qVqT3OCGIicOoTR)

## PlantsInventory (things which might done by an owner/worker)
- plant a new plant ;)
- dig up a plant
- add fertilizer to a plant (tracking of this might help to stick to the right schedule)

## FoodstuffInventory
- add new type of foodstuff
- remove type of foodstuff
- add food after collecting of harvest
- set food expiration time (how much time you can keep it fresh)
- based on expiration time, and date of harvest collection - keep track of food freshness (update food state regularly)

## Shop
- add new product
- remove product
- sell/buy product

## Reporting
various reports and diagrams on:
- plants
- supplies
- harvest
- foodstuff
- sales

----------

Bonus part)
If everything goes well owner might wanna to sell not only fresh food but also some homemade product like juice, so there're might be more contexts:

## HomeFactory
- operates on ingredients to create juice
