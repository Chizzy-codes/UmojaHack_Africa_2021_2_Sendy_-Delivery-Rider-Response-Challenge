# UmojaHack_Africa_2021_2_Sendy_-Delivery-Rider-Response-Challenge

[Competition Link](https://zindi.africa/hackathons/umojahack-africa-2021-2-sendy-challenge-intermediate)

Sendy links customers who have delivery needs with vetted transporters (from bikes to trucks), using a web and mobile application platform as well as an API. 
Customers select their vehicle of choice, get their price quote upfront and pay using various payment options. 

The system optimises the route and dispatches the order to the closest available drivers and riders (called Partners). 
The objective of this challenge is to create a machine learning model that will predict whether a rider will accept, decline or ignore an order sent to them. 

Picking the best rider to service the order will improve the experience of the customer and potentially save on time since the rider won’t cancel, creating a more efficient service overall.

The datasets provided by Sendy includes dispatch details and rider metrics based on orders made via the Sendy platform. 

The challenge is to predict whether a Partner will accept, reject or ignore an order that has been dispatched to them. 
A Partner will receive an order through the phone application and has a few seconds to accept the order. Alternatively, the Partner can actively reject the order. 

If the Partner doesn’t take an action we consider the order ignored. After a few seconds, Sendy will dispatch the order to the next available Partner.

The training dataset provided here is a subset of over 200 000 order dispatches and only includes direct orders (i.e. Sendy “express” orders) placed with bikes in Nairobi. 

All data in this subset have been fully anonymised while preserving the distribution.
