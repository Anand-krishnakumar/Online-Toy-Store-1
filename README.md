# Online-Toy-Store
**Project Description:** 
Online Toy Store web application is used to buy exclusive toys and sporting equipment for kids. Customers can sign up to the application and search from their requirement form our database. Registered users can also add desired items to their shopping cart and save them for future purchases. You can enter any quantity of items as long as the number is within the inventory range. A soft delete is implemented on the deletion of products

**Architecture:**
1. The client sends a service request to the application server through the webpage.
2. Web Server (WAMP/MAMP/XAMPP) accepts the request and processes it.
3. Application logic (PHP) will then access Data Access Layer to connect to Database and perform the desired operation.

**Languages and technologies:**
javascript, PHP, jQuery, HTML/CSS, bootstrap, ajax. Database server: MAMP with MySql, phpMyadmin.

**How To Run:**
Install MAMP/XAMPP. create a database named toy_store. From phpmyadmin import the DB-store.sql file. Place the downloaded contents from Online-Toy-Store folder in C:/MAMP/htdocs/ Run the servers from MAMP window Open any browser and log-on to localhost.

**Services:**
1. ProductSearch: The website provides options to search for products using the product name or category name.
2. Add to Cart: The website allows registered users to add any number of desired items within the stock.
3. Category Search: The customers can search based on the category name or the product name.
4. Product-Catalogue: Product title, Price and Product description is provided for each product and quantity needed.
5. Admin-panel: The website provides an admin panel feature to perform master functions.

**Functionalities:**
1. Create Account: Customers can create their account by providing their details like name, address, etc. Each customer will need to create a unique username and valid state and phone number.
2. Login: Customers can access their account using their respective username and password. The passwords are hashed in the database.
3. Add/Update-Cart: Customer adds or updates their desired items to the shopping cart.
4. Admin: Add items, update inventory, Delete items.
5. History: Customer views his purchase history.
