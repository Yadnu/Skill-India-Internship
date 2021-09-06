# Skill-India-Internship
I've made an inventory management system which works on NoSQL based dataset.
I have two JSON files, 'record' and 'sales'.
New Inventories can be added and simultaneously get updated in 'record.json'.
Purchasing items can be done by the customer and simultaneously get updated in 'record.json'and 'sales.json'.
When a customer purchase any item, it is checked whether the item matches the product Id or not.
If the quantity of a product that the customer wants to purchase exceeds the originally available quantity, appropriate message is displayed and the purchase can't be made.
Total Bill amount is generated based on the purchases made.
Each transaction made by the customer is updated accordingly to the 'sales.json' file.
Each transactions display the product Id, quantity purchased and total bill amount.
I've added 5 features per product id
1.Product name
2.Price
3.Quantity
4.Date of Manufacture
5.Date of Expiry
My project can do the following things-
1.Add Items to the Inventory
2.Update the Inventory after adding items
3.Purchaing items by Customers from the Inventory
4.Update Inventory after purchase    
5.Generate the total Bill
6.Display total number of transactions 
