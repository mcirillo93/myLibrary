
# Book Search and Save App

## Description

This is a full-stack MERN (MongoDB, Express.js, React, Node.js) application that allows users to search for books using the Google Books API and save their favorite books to their account. The app uses Apollo Client for GraphQL integration and provides a user-friendly interface for seamless navigation between searching and saving books.

---

## Features

- **Search Books:** Search for books by title or author using the Google Books API.
- **Save Books:** Save books to a personal account for future reference.
- **Authentication:** Secure login system with JSON Web Token (JWT)-based authentication.
- **Responsive Design:** Designed with Bootstrap for mobile and desktop use.
- **GraphQL API:** Efficient data querying and mutation through Apollo Server.

---

## Technologies Used

- **Frontend:**
  - React
  - React Router DOM
  - Bootstrap
  - Apollo Client
- **Backend:**
  - Node.js
  - Express.js
  - Apollo Server
  - MongoDB
- **Other Tools:**
  - JSON Web Token (JWT)
  - dotenv for environment variable management

---

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd book-search-save-app
   ```
3. Install dependencies:
   ```bash
   npm install
   ```

---

## Usage

### Local Development
1. Start the server:
   ```bash
   npm start
   ```
2. Open the application in your browser at `http://localhost:3001`.

### Production
For production environments, ensure the following:
- Environment variables (e.g., `NODE_ENV`, `PORT`) are configured properly in the `.env` file.
- Build the React app:
  ```bash
  npm run build
  ```
- Serve the built application using the Node.js backend.

---

## File Structure

### Key Files
- **App.js:** Entry point for the React frontend, managing routing and Apollo Client setup.
- **index.js:** Renders the React application to the DOM.
- **server.js:** Sets up the Express server with Apollo Server for handling GraphQL requests.

### Backend Schema
- Resolvers and type definitions for GraphQL are defined in the `/schemas` directory.

---

## Contributing

Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch for your feature.
3. Submit a pull request describing your changes.

---

## License

This project is licensed under the MIT License.

---

## Acknowledgments

- Google Books API for book search functionality.
- Bootstrap for responsive design.
- Apollo Client and Apollo Server for seamless GraphQL integration.

---

If you have additional features or sections you'd like to add, let me know!
