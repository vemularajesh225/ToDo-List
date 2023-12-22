# Todo List App

## Project Overview

This project is a simple Todo List application that allows users to fetch, add, update, and delete todo items. The data is retrieved from a JSONPlaceholder API endpoint.

### Features

1. **Fetch Todo Items:**
   - Fetches and displays todo items from [JSONPlaceholder API](https://jsonplaceholder.typicode.com/todos).

2. **Add Todo Item:**
   - Adds a new todo item by making a POST call to the API.
   - The request is a dummy request, as it won't add items to the server, but it's a valid request that returns sample data.

3. **Update Todo Item:**
   - Updates a todo item by making a PUT call to the API.
   - This is a dummy call and won't modify items on the server, but it's a valid request that returns sample data.

4. **Delete Todo Item:**
   - Deletes a todo item by making a DELETE call to the API.
   - Similar to the other operations, this is a dummy call returning sample data.

## Tech Stack

- HTML
- CSS
- JavaScript
- React

## Folder Structure
todo-list-app/
│
├── public/
│ ├── index.html
│ └── ...
│
├── src/
│ ├── components/
│ │ ├── TodoList.js
│ │ └── TodoItem.js
│ ├── App.js
│ ├── index.js
│ └── ...
│
├── .gitignore
├── package.json
├── README.md
└── ...

## Getting Started

To run the Todo List app locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone <repository-url>
Deployment
The Todo List app is deployed on Vercel. You can access it https://todo-list-xi-livid.vercel.app/
