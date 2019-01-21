# bamazon

Bamazon is an Amazon-like command line application using Node.js and MySQL. The current application allows customers to order specific items using the item id and the number of quantities to purchase. Managers can use the application to view products for sale, view items with low inventory (stock quantity less than 5), increase quantity of items in the inventory and add new items to the inventory.

### Create SQL database
- open SQL script, bamazon.sql and run script in MySQL Workbench to create database, bamazonDB.

## Walkthroughs
### 1) Customer View:
![Customer View GIF]

### 2) Manager View: 

* If a manager selects `View Products for Sale`, the app lists every available item: the item IDs, names, prices, and quantities.
![View Products for Sale GIF]

* If a manager selects `View Low Inventory`, the app lists all items with an inventory count lower than five.
![View Low Inventory GIF]

* If a manager selects `Add to Inventory`, the app displays a prompt that will let the manager "add more" of any item currently in the store.
![Add to Inventory GIF]

* If a manager selects `Add New Product`, the app will allow the manager to add a completely new product to the store.
![Add New Product GIF]

## Programming Languages / Databases

- JavaScript (Node.js, v8.11.2)
- HeidiSQL 
- npm (v6.4.0) packages (inquirer, mysql, console.table, chalk-pipe)

## Licensing

The code in this project is licensed under MIT license.
