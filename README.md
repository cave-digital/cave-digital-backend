# Cave Digital Task Manager - Backend

## Project Setup
This is the backend for the Cave Digital Task Manager, built with Node.js and Express.

### Prerequisites
Ensure you have the following installed:
- **Node.js** (Latest LTS - v18)
- **MongoDB** (For database operations)

### Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo.git
   cd your-repo
   ```
2. Install dependencies:
   ```sh
   npm install
   ```

### Running the Server
Start the server with:
```sh
node server.js
```

### Environment Variables
Create a `.env` file in the root directory with the following variables:
```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

### API Endpoints
| Method | Endpoint        | Description           |
|--------|---------------|-----------------------|
| POST   | `/tasks`       | Create a new task     |
| GET    | `/tasks`       | Get all tasks         |
| GET    | `/tasks/:id`   | Get a task by ID      |
| PUT    | `/tasks/:id`   | Update a task         |
| DELETE | `/tasks/:id`   | Delete a task         |

### License
MIT License

