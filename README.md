# E-Commerce-Back-End

## Description

This is a backend system designed for an E-commerce application built with Express.js, PostgreSQL, and Sequelize. It provides RESTful API endpoints to manage categories, products, and tags within an E-commerce platform. The application enables users to perform CRUD operations and establishes relationships between the different entities, making it easy to organize and manage product data.

## Installation

1. Clone the Repository:

```sh
git clone https://github.com/A-MOHAMED14/e-commerce-backend.git
```

2. Navigate to the Project Directory:

```sh
cd e-commerce-backend
```

3. Install dependencies:

```sh
npm install
```

4. Set up enviroment variables:

- Create a .env file in the root directory and add your PostgreSQL database credentials:

```sh
DB_NAME=your_database_name
DB_USER=your_postgresql_username
DB_PASSWORD=your_postgresql_password
```

5. Create the database and seed data:

```sh
psql -U <your_postgresql_username> -d <your_database_name> -f db/schema.sql

npm run seed
```

## Usage

To start the application, run the following command:

```sh
npm run start
```

This will sync the Sequelize models to your PostgreSQL database, and will then start the server. The server will be running on http://localhost:3001

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these guidelines:

1. Fork the repository.
2. Create a new branch for your feature or bugfix:

```sh
git checkout -b feature/your-feature-name
```

3. Make your changes and commit them with descriptive messages:

```sh
git commit -m "Add new feature: your feature description"
```

4. Push your changes to your forked repository:

```sh
git push origin feature/your-feature-name
```

5. Open a pull request to the main repository, describing your changes in detail.
