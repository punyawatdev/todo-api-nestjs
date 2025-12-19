# Todo API (NestJS + MongoDB)

A simple Todo application built with [NestJS](https://nestjs.com/) and [MongoDB](https://www.mongodb.com/).

## Features

- Create, read, update, and delete todos
- RESTful API endpoints
- MongoDB integration using Mongoose

## Installation

```bash
git clone https://github.com/your-username/todo-api-nestjs.git
cd todo-api-nestjs
npm install
# OR
yarn install
```
`

## Configuration

Copy `.env.example` to `.env` and update the MongoDB URI:

```env
MONGODB_URI=mongodb://localhost:27017/todo_db
```

## Running the App

```bash
npm run start:dev
```

The API will be available at `http://localhost:3000`.

## API Endpoints

| Method | Endpoint        | Description         |
|--------|----------------|--------------------|
| GET    | `/todos`       | List all todos     |
| POST   | `/todos`       | Create a new todo  |
| GET    | `/todos/:id`   | Get a todo by ID   |
| PATCH  | `/todos/:id`   | Update a todo      |
| DELETE | `/todos/:id`   | Delete a todo      |

## License

MIT