# CAR-WASH-BACKEND

This project is an Express application that uses TypeScript and Mongoose to integrate MongoDB and handle data efficiently. Through the use of Zod for validation, data integrity is ensured.

## Features

- Express server with TypeScript.
- MongoDB integration using Mongoose.
- Modules for Product and Order with appropriate data types and validations.
- Data integrity validation using Zod.
- RESTful API endpoints for managing products and orders.

## Prerequisites

- Node.js (v20.12.12 recommended)
- MongoDB (running instance or MongoDB Atlas)
- npm
- Git

# Installation

## Clone the repository

```sh
 git clone  https://github.com/AkashAkter/car-wash
 cd e-commerce
```

## Install dependencies

Open the project file in the terminal and run `npm install`

```sh
npm install
```

## Set up environment variables

Create a `.env` file in the root directory and add the following:

```
NODE_ENV= development
MONGO_URI=your_mongo_db_connection_string
BCRYPT_SALT_ROUNDS= enter any rounds (ex- 8,12)
JWT_ACCESS_SECRET= create your own secret token
PORT=5000
```

## Start the server

```
npm run start:dev
```
