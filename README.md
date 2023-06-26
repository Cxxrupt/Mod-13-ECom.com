# Ecom.com 

This repository contains the backend for an e-commerce application. It provides API endpoints for managing products, categories, and tags. The backend is built using Node.js, Express.js, MySQL, and the Sequelize ORM.

## Technologies

The application is built with the following technologies:

- Node.js
- Express.js
- MySQL

## Installation

To install and run the application, please follow these steps:

1. Clone the repository to your local machine.
2. Install the required dependencies by running the command `npm install`.
3. Create a `.env` file in the root directory of the project and provide your MySQL credentials in the following format:

DB_HOST=your_mysql_host

DB_USER=your_mysql_username

DB_PASSWORD=your_mysql_password

DB_DATABASE=your_mysql_database_name

Replace `your_mysql_host`, `your_mysql_username`, `your_mysql_password`, and `your_mysql_database_name` with your actual MySQL configuration.

4. Create the necessary database tables by executing the SQL script `db/schema.sql` in your MySQL database.
5. Seed the database with sample data by running the command `npm run seeds`.

## Usage

Start the server with `npm start` and use a tool such as Postman or Insomnia to make requests to the API endpoints.

## API Endpoints

The following API endpoints are available:

- GET `/api/products`: Get all products.
- GET `/api/products/:id`: Get a single product by its id.
- POST `/api/products`: Create a new product.
- PUT `/api/products/:id`: Update a product.
- DELETE `/api/products/:id`: Delete a product.
- GET `/api/categories`: Get all categories.
- GET `/api/categories/:id`: Get a single category by its id.
- POST `/api/categories`: Create a new category.
- PUT `/api/categories/:id`: Update a category.
- DELETE `/api/categories/:id`: Delete a category.
- GET `/api/tags`: Get all tags.
- GET `/api/tags/:id`: Get a single tag by its id.
- POST `/api/tags`: Create a new tag.
- PUT `/api/tags/:id`: Update a tag.
- DELETE `/api/tags/:id`: Delete a tag.

## Contributing
Stackoverflow was a huge help with api endpoints and .env problems

https://stackoverflow.com/questions/2122604/what-is-an-endpoint

https://stackoverflow.com/questions/60522667/storing-as-password-in-env-file

I no longer have all the links I refrenced

Contributions are welcome! If you have any suggestions or find any bugs, please open an issue.

## License

This project is licensed under the MIT License.
