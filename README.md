# Ecom_Challenge13
# Ecom_Challenge13
Project Name: E-Commerce
Aim of this project is to sell the products in online.

Table of Contents
1.Installation
2.Usage
3.Endpoints
4.Models
5.Technologies Used
6.Contributing
7.License

1.Installation

1.Install dependencies
npm install
2.Database Setup
PostgreSQL is installed and running.
npm start
The server will start running at http://localhost:3001 in insomnia

Usage
The usage of the API endpoints

Endpoints
Categories
GET /api/categories: Retrieves all categories with associated products.
GET /api/categories/:id: Retrieves a single category by ID with associated products.
POST /api/categories: Creates a new category.
PUT /api/categories/:id: Updates a category by ID.
DELETE /api/categories/:id: Deletes a category by ID.
Products
GET /api/products: Retrieves all products with associated categories and tags.
GET /api/products/:id: Retrieves a single product by ID with associated category and tags.
POST /api/products: Creates a new product with optional tags.
PUT /api/products/:id: Updates a product by ID with optional tags update.
DELETE /api/products/:id: Deletes a product by ID.
Tags
GET /api/tags: Retrieves all tags with associated products.
GET /api/tags/:id: Retrieves a single tag by ID with associated products.
POST /api/tags: Creates a new tag.
PUT /api/tags/:id: Updates a tag by ID.
DELETE /api/tags/:id: Deletes a tag by ID.

Models
Category: Represents product categories.
Product: Represents products, associated with categories and tags.
Tag: Represents tags associated with products.
ProductTag: Represents associations between products and tags.
Technologies Used
Node.js
Express.js
Sequelize
PostgreSQL

Contributing
Contributions are welcome . you can share your views and sources

License
e.com llc

walkthrough video
