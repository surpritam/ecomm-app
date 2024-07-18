# E-commerce Back End

## Description
This project is an API of EComm app that uses Sequelize to interact with a PostgreSQL database. It supports CRUD operations for categories, products, and tags. The API can be tested using tools like Insomnia or Postman.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Endpoints](#endpoints)
  - [Categories](#categories)
  - [Tags](#tags)
  - [Products](#products)
- [Demo](#demo)


## Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/surpritam/ecomm-app.git
   cd ecomm-app
   ```
2. **Install dependencies:**
    ```sh
    npm install
    ```
3. **Set up environment variables:**
    Create a `.env` file and copy the contents from `.env.example` file and replace with your database details

4. **Seed the database:**
    ```sh
    npm seed
    ```
5. **Start the server:**
    ```sh
    npm start
    ```

## Usage
You can use Insomnia, Postman, or any other API testing tool to interact with the API.

## Endpoints

#### Categories
    
    * `/api/categories` GET - Retrieves all categories with associated products.
    * `/api/categories/:id` GET - Retrieves a category by its ID with associated products.
    * `/api/categories` POST - Create new category
    * `/api/categories/:id` PUT - Update category by it's id
    * `/api/categories/:id` DELETE - Delete category by id

#### Tags

    * `/api/tags` GET - Retrieves all tags with associated products.
    * `/api/tags/:id` GET - Retrieves a tag by its ID with associated products.
    * `/api/tags` POST - Create new tag
    * `/api/tags/:id` PUT - Update tag by it's id
    * `/api/tags/:id` DELETE - Delete tag by id

#### Products

    * `/api/products` GET - Retrieves all products with associated categories and tags.
    * `/api/products/:id` GET - Retrieves a product by its ID with associated categories and tags.
    * `/api/products` POST - Create new product
    * `/api/products/:id` PUT - Update product by it's id
    * `/api/products/:id` DELETE - Delete product by id

## Demo
Check out the live [demo](https://drive.google.com/file/d/158CkIt_E0SqaEUp_Lb9kTGCOwNVgLcgI/view?usp=share_link) to learn more on the API usage.