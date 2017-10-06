
##Objective To create an Amazon-like storefront with the MySQL skills learned this week. The app will take in orders from customers and deplete stock from the store's inventory. The assignment is broken down into the following two challenges. A video demonstrating the execution of the application is available in the Video folder.
###Challenge 1: Customer View
####Tasks
1. Create a MySQL Database called Bamazon.
2. Then create a Table inside of that database called Products.
3. The products table should have each of the following columns:
o ItemID (unique id for each product)
o ProductName (Name of product)
o DepartmentName
o Price (cost to customer)
o StockQuantity (how much of the product is available in stores)
4. Populate this database with around 10 different products. (i.e. Insert "mock" data rows into this database and table).
5. Then create a Node application called BamazonCustomer.js. Running this application will first display all of the items available for sale. Include the ids, names, and prices of products for sale.
6. The app should then prompt users with two messages.
o The first should ask them the ID of the product they would like to buy.
o The second message should ask how many units of the product they would like to buy.
7. Once the customer has placed the order, your application should check if your store has enough of the product to meet the customer's request.
o If not, the app should log a phrase like Insufficient quantity!, and then prevent the order from going through.
8. However, if your store does have enough of the product, you should fulfill the customer's order.
o This means updating the SQL database to reflect the remaining quantity.
o Once the update goes through, show the customer the total cost of their purchase.
###Challenge 2: Manager View
####Tasks
* Create a new Node application called BamazonManager.js. Running this application will:
o List a set of menu options:
* View Products for Sale
* View Low Inventory
* Add to Inventory
* Add New Product
o If a manager selects View Products for Sale, the app should list every available item: the item IDs, names, prices, and quantities.
o If a manager selects View Low Inventory, then it should list all items with a inventory count lower than five.
o If a manager selects Add to Inventory, your app should display a prompt that will let the manager "add more" of any item currently in the store.
o If a manager selects Add New Product, it should allow the manager to add a completely new product to the store.


