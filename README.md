# Todo Application with MERN Stack

This project is a Todo application built with the MERN stack, encompassing MongoDB, Express, React, and Node.js. It's designed to help users manage their tasks with features to add, view, edit, and delete todos. The application stores tasks in MongoDB, using Mongoose for object data modeling. Express handles the backend logic and API routes, React is used for the frontend interface, and Node.js runs the server-side code.

## Technologies Used

- **MongoDB:** The NoSQL database for storing tasks.
- **Mongoose:** An ODM library for MongoDB and Node.js, providing a schema-based solution for modeling application data.
- **Express:** The backend framework for Node.js, managing server logic and API routes.
- **React:** The JavaScript library for building the frontend interface.
- **Node.js:** The runtime environment for executing server-side JavaScript.
- **dotenv:** A module to load environment variables from a .env file, ensuring secure configuration.

## Prerequisites

Before setting up the project, ensure you have installed:

- **Node.js and npm:** Node Package Manager (npm) comes with Node.js and helps in managing project dependencies.
- **MongoDB:** Ensure MongoDB is running on your local machine or provide a connection string for remote access.

## Getting Started

1. Clone the repository to your local machine.
2. Navigate to the project directory and install dependencies with `npm install`.
3. Ensure MongoDB is running locally or set up your MongoDB connection string in the `.env` file.
4. Start the server with `npm start` for the backend and `npm run start` for the frontend.
5. Open your browser and navigate to the application URL, typically `http://localhost:3000`.

Enjoy managing your tasks with this simple yet powerful Todo application built with the MERN stack.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/abhishekpaturkar/React-todo-app.git
   cd React-todo-app
   ```

2. Install dependencies:

   ```bash
   cd server
   npm install
   cd ../client
   npm install
   ```

## Configuration

1. Create a `.env` file in the `server` directory and provide the following variables:

   ```env
   MONGODB_URI=your_mongodb_connection_string
   PORT=3000
   ```

   Replace `your_mongodb_connection_string` with the actual connection string.

## Running the Application

1. Start the server:

   ```bash
   cd server
   npm start
   ```

   The server will run on `http://localhost:3000`.

2. Start the client:

   ```bash
   cd client
   npm start
   ```

   The client will run on `http://localhost:5173`.

3. Open your browser and go to `http://localhost:5173` to access the Todo app.

![image](https://github.com/aaryan182/todo-mern/assets/73265857/7c0459f7-4e0c-4a2f-92db-26a0e3027dd8)

## Usage

- Add a new task by entering the task description and clicking the "Add Task" button.
- Mark tasks as completed by clicking the checkbox next to each task.
- Edit a task by clicking the "Edit" button and update the task description.
- Delete a task by clicking the "Delete" button.

## Contributing

Feel free to contribute to the project. You can create issues, submit pull requests, or suggest new features.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

