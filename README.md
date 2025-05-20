# CoreTasks CRUD APIs

A RESTful API for task management built with Node.js, Express, and PostgreSQL.

## Features

- Create, read, update, and delete tasks
- PostgreSQL database integration
- Input validation
- Error handling middleware

## Tech Stack

- Node.js
- Express.js
- PostgreSQL
- Joi (validation)
- CORS support

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/vhcaldas/coretasks-crus-apis.git
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Create a `.env` file with the following variables:
   ```
   PORT=3001
   DB_USER=your_db_user
   DB_PASSWORD=your_db_password
   DB_HOST=localhost
   DB_PORT=5432
   DB_DATABASE=your_database_name
   ```

## Usage

Start the development server:
```
npm run dev
```

The API will be available at `http://localhost:3001`.

## API Endpoints

- `GET /api/tasks` - Get all tasks
- `GET /api/tasks/:id` - Get a specific task
- `POST /api/tasks` - Create a new task
- `PUT /api/tasks/:id` - Update a task
- `DELETE /api/tasks/:id` - Delete a task

## License

ISC