# TodoList

TodoList is a React + Vite application that allows users to manage their tasks with full CRUD (Create, Read, Update, Delete) functionality. The application is styled using TailwindCSS and uses `useContext` to manage functions. All tasks are stored locally in the browser using `localStorage`.

## Features

- **Create** new tasks.
- **Read** and view your existing tasks.
- **Update** tasks as needed.
- **Delete** tasks when they're no longer needed.
- Persistent data storage using `localStorage`.
- Context management with `useContext` for handling functions.
- Responsive design with TailwindCSS.

## Deployment Link

## Demo

![TodoList Demo](assets/demo.png)

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (version 14.x or later)
- npm (Node Package Manager)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/namanmalhotra26/todoList.git
   cd todoList
   ```

2. Install the dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm run dev
   ```

4. Open your browser and navigate to `http://localhost:3000` to see the application in action.

## Usage

1. Add a new task using the input field and "Add" button.
2. View your list of tasks below.
3. Click on a task to edit its content.
4. Delete a task by clicking the delete button next to it.
5. All tasks are saved in `localStorage`, so they persist even after refreshing the page.

## Technologies Used

- [React](https://reactjs.org/)
- [Vite](https://vitejs.dev/)
- [TailwindCSS](https://tailwindcss.com/)
- JavaScript
- `useContext` for context management

## Project Structure
