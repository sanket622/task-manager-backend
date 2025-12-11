# Task Manager Backend

RESTful API for Task Management Dashboard built with Node.js and Express.

## Features

- **CRUD Operations**: GET, POST, PUT, DELETE, PATCH endpoints
- **ES6 Syntax**: Modern JavaScript with import/export
- **CORS Enabled**: Cross-origin resource sharing
- **In-memory Storage**: Tasks stored in memory (can be extended to database)

## API Endpoints

- `GET /api/tasks` - Get all tasks
- `POST /api/tasks` - Create new task
- `PUT /api/tasks/:id` - Update task
- `PATCH /api/tasks/:id/move` - Move task between columns
- `DELETE /api/tasks/:id` - Delete task

## Installation

```bash
npm install
npm run dev
```

## Deployment

Deploy to Render, Heroku, or Vercel Serverless Functions.