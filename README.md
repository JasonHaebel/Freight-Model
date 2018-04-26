# Freight Model

Project Outline:  Freight Model


Purpose:
Create a simple tool for users to estimate sales commissions.

High Level:
1.	User can select Customer Name from a drop-down list
a.	If the Customer does not exist, user can create a new one. This must not update the original Customer table, but instead will store it in an intermediate table for approval

2.	User enters a zip code

3.	Program uses multiple factors, formulas, and customer information to calc $/lbs

Specs:
1.	IF “truck weight” > “x” lbs THEN ADD “y” dollars ::  “y” needs to be a variable that operations can set and change

2.	FOR EACH stop/delivery ADD $50 :: this amount needs to be a variable that operations can set and change

3.	Create factor list for Fuel Surcharge.  This must be a variable that operations can set and change. (e.g. variable of 1 means oil is cheap, 3 means expensive)

a.	Higher factor means multiplying whole cost by x dollars

4.	Create factor for if delivery involves any LIFT GATE stops, these take longer and are more expensive

5.	Create factor list {1,2,3} for difficulty of delivery.  1 = normal, 2 = difficult, 3 = very difficult

Comments:
Need to figure out pricing for customers and trucking.  Need to figure out how to calculate distance by zip code.





