<!-- @format -->

# E-commerce Back End

## Description

The E-commerce Back End is a robust API built using Express.js and Sequelize. It provides a solid foundation for managing products, categories, and tags in an e-commerce application. With this API, you can easily perform CRUD operations on the database, enabling seamless management of your online store's inventory.

## Table of Contents

- [Description](#description)
- [Installation](#installation)
- [Technologies Used](#technologies)
- [Features](#features)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository: `git clone https://github.com/jakepears/ecomm-backend`
2. Navigate to the project directory: `cd ecomm-backend`
3. Install dependencies: `npm install`
4. Create a `.env` file in the project root and add your environment variables (e.g., database credentials).
5. Set up the database:
   - Run the SQL script in `schema.sql` to create the database.
   - Run `npm run seed` to seed the database with sample data.
6. Start the server: `npm start`

## Technologies Used

- Express.js: A fast and minimalist web application framework for Node.js.
- Sequelize: A powerful ORM (Object-Relational Mapping) library for Node.js, supporting multiple database dialects.
- MySQL2: A MySQL client library for Node.js, used in conjunction with Sequelize.
- dotenv: A module for loading environment variables from a `.env` file, used to protect sensitive information like database credentials.

## Features

- RESTful API: The API follows RESTful principles, providing endpoints for products, categories, and tags.
- CRUD Operations: Supports Create, Read, Update, and Delete operations on products, categories, and tags.
- Database Integration: Utilizes Sequelize ORM to interact with a MySQL database, simplifying database management.
- Environment Variables: Sensitive information like database credentials are stored in environment variables using the `dotenv` module, enhancing security.

## Usage

1. Make sure you have completed the installation steps and have the server running.
2. Use a tool like Insomnia or Postman to test the API endpoints.
3. Available endpoints:
   - `/api/products`: Manage products (GET, POST, PUT, DELETE)
   - `/api/categories`: Manage categories (GET, POST, PUT, DELETE)
   - `/api/tags`: Manage tags (GET, POST, PUT, DELETE)
4. Refer to the API documentation or code for specific request and response formats.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License.
