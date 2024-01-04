# User Login, Ticket generate, RUST, AXUM, Authentication, Auhtorization, Cookie

This project is a Rust application built using the Axum framework. It provides an API for handling HTTP requests and routing them to the appropriate endpoints. The project aims to showcase the features and capabilities of Axum.

## API Routes

The following are the API routes available in this project:

1. `/api/login` - GET: Login In to use services.
    ```
     {
      "username":"demo1",
      "pwd":"welcome"
    }
   ```
2. `/api/tickets` - GET: Retrieves a lsit all tickets.
3. `/api/tickets` - POST: Creates a new user.
   ```
     {
      "title":"Ticket AA"
    }
   ```
4. `/users/{id}` - DELETE: Deletes a user by ID.

## Getting Started

To start the application, follow these steps:

1. Clone the repository: `git clone https://github.com/your-repo.git`
2. Install Rust and Cargo if not already installed.
3. Navigate to the project directory: `cd repo-name`
4. Run the application:
  ```
  cargo run
  or
  cargo watch -q -c -w src/ -x "run"
  ```
5. Run the test
   ```
  cargo watch -q -c -w tests/ -x "test --quick_dev -- -nocapture"
  ```
6. The server will avaiable at `http://127.0.0.1:1000`

