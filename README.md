A brief overview of the system design.
Frontend: A React application that serves as the user interface for interacting with tasks. Users can add, edit, delete, and mark tasks as completed.
Backend: A JSON file (db.json) served as a REST API using json-server. This mock server handles CRUD operations (Create, Read, Update, Delete) and serves as the data repository.

An explanation of the implementation.
1. React Application:
State Management: Utilizes React’s useState to manage tasks, input values, and other states.
Data Fetching: Uses fetch to interact with the json-server API .
Task Operations:
Add/Update Task: Adds new tasks or updates existing ones by sending requests to the API.
Toggle Completion: Toggles the completion status of a task.
Delete Task: Removes a task from the list and the server.
Search and Expand: Implements search and an expand feature for task details.

Instructions to Set Up and Run the Application
1.Install json-server:
Open a terminal and install json-server globally:
npm install -g json-server
2.Run json-server to serve db.json:
json-server --watch db.json --port 5000
3.Start the React Application:
npm start
