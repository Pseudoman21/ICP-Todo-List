# Simple Todo List App
This app is created for the Internet Computer: TypeScript Smart Contract 101 Challenge course

## How Does It Work?
The todo list application allows users to perform the following operations:

### Create Todo: Users can create new todos by sending a POST request to the /todos endpoint with the required todo data.

### Read Todos: Users can retrieve a list of all todos by sending a GET request to the /todos endpoint.

### Read Todo by ID: Users can retrieve a specific todo by its ID by sending a GET request to the /todos/:id endpoint, where :id is the unique identifier of the todo.

### Update Todo: Users can update an existing todo by sending a PUT request to the /todos/:id endpoint with the updated todo data.

### Delete Todo: Users can delete a todo by sending a DELETE request to the /todos/:id endpoint, where :id is the unique identifier of the todo to be deleted.

## Installation
To set up the todo list application locally, follow these instructions:

#### Clone the GitHub Repository: Begin by cloning the repository to your local machine using the following command:

```
Copy code
git clone https://github.com/your-username/todo-list
cd todo-list
```
#### Install Dependencies: Install the required dependencies by running:

```
Copy code
npm install
```

#### Start the Server: Start the server by running:

```
Copy code
npm start
```

#### Sending Requests
You can send requests to the todo list application using a client such as Postman. Postman provides a user-friendly interface for interacting with APIs and web services. To get started with Postman, download and install it from the official website. Once installed, you can use Postman to send HTTP requests to the todo list endpoints and perform various operations.

#### Usage with Postman
Open Postman and create a new request.
Set the request method (POST, GET, PUT, DELETE) and specify the request URL based on the desired endpoint (/todos, /todos/:id).
Add any required headers or request body parameters.
Send the request and view the response to see the results of the operation.

#### Contributing
If you would like to contribute to the todo list application, feel free to fork the repository, make changes, and submit a pull request. Contributions are welcome and appreciated!
