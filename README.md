# E_ComPlus


## Description
This project is a back end for an e-commerce website built using Express.js, Sequelize, and PostgreSQL. It provides API endpoints for managing categories, products, and tags, allowing users to perform CRUD operations.

## Technologies Used
- Node.js
- Express.js
- Sequelize
- PostgreSQL

## Installation
1. Clone the repository.
2. Navigate to the project directory.
3. Install dependencies using `npm install`.

## Configuration
1. Create a `.env` file in the root directory.
2. Add the following environment variables:

DB_NAME=your_database_name
DB_USER=your_username
DB_PASSWORD=your_password
DB_HOST=localhost

Replace `your_database_name`, `your_username`, and `your_password` with your actual database credentials.

## Database Setup
1. Run the schema.sql file located in the `db` folder to create the database structure.

## Seeding the Database
1. Run `npm run seed` to populate the database with test data.

## Usage
1. Start the server using `npm start`.
2. Use tools like Insomnia or Postman to test the API endpoints.

## API Routes
- **Categories**
- GET /api/categories: Get all categories.
- POST /api/categories: Add a new category.
- PUT /api/categories/:id: Update a category by ID.
- DELETE /api/categories/:id: Delete a category by ID.

- **Products**
- GET /api/products: Get all products.
- POST /api/products: Add a new product.
- PUT /api/products/:id: Update a product by ID.
- DELETE /api/products/:id: Delete a product by ID.

- **Tags**
- GET /api/tags: Get all tags.
- POST /api/tags: Add a new tag.
- PUT /api/tags/:id: Update a tag by ID.
- DELETE /api/tags/:id: Delete a tag by ID.

## Credits
This project was created by Mirsad.

## License
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).


