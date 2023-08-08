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
6. The API routes can be accessed at `http://localhost:3001/api`.
## API Routes

- `GET /api/categories` - Get all categories.
- `GET /api/categories/:id` - Get a category by ID.
- `POST /api/categories` - Create a new category.
- `PUT /api/categories/:id` - Update a category.
- `DELETE /api/categories/:id` - Delete a category.

- `GET /api/products` - Get all products.
- `GET /api/products/:id` - Get a product by ID.
- `POST /api/products` - Create a new product.
- `PUT /api/products/:id` - Update a product.
- `DELETE /api/products/:id` - Delete a product.

- `GET /api/tags` - Get all tags.
- `GET /api/tags/:id` - Get a tag by ID.
- `POST /api/tags` - Create a new tag.
- `PUT /api/tags/:id` - Update a tag.
- `DELETE /api/tags/:id` - Delete a tag.