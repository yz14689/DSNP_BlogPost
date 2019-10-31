# Project Name: Blog Post
Udacity Data Scientist Nanodegree - Create a Blog Post

## Data source
Bostone_AirBnB data (https://www.kaggle.com/airbnb/boston)

## Python libraries used:
   python3
   python packages in the requirements.txt file: datetime, pandas, numpy, seaborn, matplotlib   

## Purpose:
This analysis is to find the most imp ortant features of Boston's AirBnB market upon the given period. It could help either the visitor or the potential host to make correct decision. Basically, it will look into the data and answer where, when and what are the best target if any vacation or investment is in plan.

## Questions to be answered:
1. Where to stay: Does location really drive your first choice or think more? Does the room impact decion as well? Does location in line with ratings? 
2. When to visit:  Timing: Does season or event really matter? Does the price echo the demanding?
3. What to expect: Is the cost of stay associated with rating/room/etc?  

## Analysis Steps:
1. Load and clean the data
2. Merge all three datasets and dig with questions
3. Visualize for 
   location (strat by average rating, demanding, room type) 
   Availability (strat by time, weekday, location, min nights) 
   Plot price (strat by location, demanding, room type, discount)    
3. Conclusion from results: For different needs, suggest the best place to stay/invest.
4. Write the blog following: Introduction, 3 questions (with hgihlighted title), conclusion/echo/action.

## Findings:
1. Location does matter regarding the availablity and there are top 5 neighborhood leading the inventory
2. Holiday season apprently has much more availability, and dropped right after and again in March. But the availability through the week does not shift much while weenend is slightly higher than weekdays.
3. On pricing, weekend definitely dominates the pricing. Allston and Brington give lower price than the other 3 neighborhoods at top 5. Staying more than 7 nights would basically save a lot. 

##  Next Challenge:
1. Compared to other popular cities (such as New York City, Orlando, etc.) to see if any common features
2. For investment, estimate the return in each neighborhood/property type and find the best option
 
## Final post on Medium link:
https://medium.com/@yanzhang14689/boston-airbnb-a3f042f8abf1
