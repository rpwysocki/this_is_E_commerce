# Title: this_is_E_commerce
## Description: E_Commerce backend database MySQL
## Installation

1. Clone the repository to your local machine.
2. Navigate to the project directory in your terminal.
3. Run `npm i` to install the required dependencies.
## Usage

1. Create a `.env` file in the root directory and provide the following environment variables:
   - `DB_NAME` - Is provided in the .env.example file.
   - `DB_USER` - Your MySQL username.
   - `DB_PW` - Your MySQL password.
2. Run SOURCE db/schema.sql in the MySQL shell to create the database.
3. Run the seed data with 'npm run seed' to populate the database with test data.
4. Start the server by running `node start` or 'nodemon start'.
5. Use an API testing tool like Insomnia Core to interact with the API endpoints.
6. The API routes can be accessed at `localhost:3001/api`.
## API Routes

-  Get all categories: `GET localhost:3001/api/categories`
-  Get a category by ID: `GET localhost:3001/api/categories/(enter id number here)`
-  Create a new category: `POST localhost:3001/api/categories` 
-  Update a category: `PUT localhost:3001/api/categories/(enter id number here)`
-  Delete a category: `DELETE localhost:3001/api/categories/(enter id number here)` 

-  Get all products: `GET localhost:3001/api/products`
-  Get a product by ID: `GET localhost:3001/api/products/(enter id number here)` 
-  Create a new product: `POST localhost:3001/api/products`
-  Update a product: `PUT localhost:3001/api/products/(enter id number here)`
-  Delete a product: `DELETE localhost:3001/api/products/(enter id number here)` 

-  Get all tags: `GET localhost:3001/api/tags`
-  Get a tag by ID: `GET localhost:3001/api/tags/(enter id number here)`
-  Create a new tag: `POST localhost:3001/api/tags` 
-  Update a tag: `PUT localhost:3001/api/tags/(enter id number here)`
-  Delete a tag: `DELETE localhost:3001/api/tags/(enter id number here)` 
## Links

Walkthrough video link: https://drive.google.com/file/d/1Q2RBY1Dy5z7GZ4Y7aNgu5e93l28G4wXX/view

Github repo link: https://github.com/rpwysocki/this_is_E_commerce