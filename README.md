# Ecommerce-API 

API for an ecommerce platform allows admin to manage product inventory.The E-commerce API is built using Node.js, Express.js, and MongoDB, providing functionality for the admin to manage their product inventory. The API allows for viewing the inventory, creating new products, deleting existing products, and updating the quantity of products.

## Tech Stack:

- Node.js: A JavaScript runtime environment that allows running JavaScript on the server-side.
- Express.js: A web application framework for Node.js, used for handling server-side logic and creating RESTful APIs.
- MongoDB Atlas: A cloud-based-NoSQL database used for storing and retrieving product inventory data.
- Postman API.

## Project Usage Instructions:

1. Install nodejs.
2. Inside main directory -> npm install.
3. To start project -> npm start.
4. Project will now be running on port 3000.

## Functionality:

_View Inventory_: The API provides endpoints to retrieve the product inventory, allowing the admin to view all the products currently available.

_Create Products_: The API includes endpoints for creating new products in the inventory. The admin can provide details such as product name, description, price, and quantity.

_Delete Product_: The API provides an endpoint to delete a specific product from the inventory based on its unique identifier.

_Update Product_: The API allows the admin to update the quantity of a product in the inventory. The admin can specify the product ID and the new quantity to update the stock.

## API URL's:

1. Create a product //**POST** http://localhost:3000/products/create

2. Get all products //**GET** http://localhost:3000/products

3. Delete a product //**DELETE** http://localhost:3000/products/3

4. Update a product //**PATCH** http://localhost:3000/products/3/update_quantity/?number=5
