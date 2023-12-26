# Express.js CRUD API integrated with MongoDB Atlas

This project features an Express.js server implementing CRUD operations on a MongoDB Atlas database, following the MVC (Model-View-Controller) architecture. It offers a robust API structure for managing user data efficiently.

## Features

- **CRUD Operations:** Execute Create, Read, Update, and Delete operations on user data stored in MongoDB Atlas.
  
- **Middleware for URL Decoding:** Integrated middleware ensures proper URL decoding for optimized data handling and secure communication. Stores a log of the requests made from the client.

## Technologies Used

- **Node.js:** Powering the backend server with its event-driven architecture.
  
- **Express.js:** Facilitating the construction of robust APIs and handling HTTP requests.
  
- **MongoDB Atlas:** Leveraging a hosted MongoDB solution for scalable and reliable data storage.

## Getting Started

1. **Clone the Repository:**
   
```bash
   git clone <repository-url>
```
2. **To install the necessary dependencies, run the following command:**

```bash
npm init
```

3. **To  start the server run the following command:**
```bash
npm start
```


## Directory Structure

This project strictly adheres to an MVC (Model-View-Controller) architecture, organized as follows:

- `controllers`: Contains the logic responsible for handling CRUD operations related to user data.

- `middleware`: Houses the implementation of crucial URL decoding middleware, ensuring secure and optimized data transmission between the client and server.

- `routes`: Defines and manages the API endpoints, outlining the routes and functionalities associated with user data operations.





