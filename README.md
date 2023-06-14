# E-Commerce Back-End [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


This is the back-end component of an e-commerce application. It provides the server-side functionality for managing products, categories, and tags. The API is built using Node.js, Express.js, and Sequelize ORM.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [API Routes](#api-routes)
- [License](#license)
- [Demo](#demo)

## Installation

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Install the dependencies
4. Set up the database.
- Create a `.env` file in the root directory and provide your database credentials. 
5. Seed the database with sample data.


## Usage

1. Start the server.

2. Once the server is running, you can access the API at `http://localhost:3001`.

## API Routes

The following routes are available in the API:

- `GET /api/categories`: Get all categories.
- `GET /api/categories/:id`: Get a category by ID.
- `POST /api/categories`: Create a new category.
- `PUT /api/categories/:id`: Update a category by ID.
- `DELETE /api/categories/:id`: Delete a category by ID.

- `GET /api/products`: Get all products.
- `GET /api/products/:id`: Get a product by ID.
- `POST /api/products`: Create a new product.
- `PUT /api/products/:id`: Update a product by ID.
- `DELETE /api/products/:id`: Delete a product by ID.

- `GET /api/tags`: Get all tags.
- `GET /api/tags/:id`: Get a tag by ID.
- `POST /api/tags`: Create a new tag.
- `PUT /api/tags/:id`: Update a tag by ID.
- `DELETE /api/tags/:id`: Delete a tag by ID.

Please refer to the API documentation for detailed information about each route, including request and response formats.


## License

This project is licensed under the [MIT License](LICENSE).

## Demo







