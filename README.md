# Airbnb-like Website Project

This repository contains the codebase for an Airbnb-like website built using Node.js, Express.js, and MongoDB. The project
follows the MVC (Model-View-Controller) architecture, incorporates robust error handling, and provides APIs for essential
functionalities such as authentication, property listing, and booking.

## Features

- **API-Driven Development**: The application is API-centric, enabling easy integration with frontend applications
-  or other services.
- **Error Handling**: Comprehensive error handling for better debugging and user feedback.
- **MVC Architecture**: Clear separation of concerns with models, views, and controllers.
- **Validation**: Input validation to ensure data integrity.
- **Express Router**: Modular routing using Express Router for better code organization.
- **Authentication**: Secure user authentication using JWT.
- **Deployment**: Hosted on [Render](https://render.com).

## Technologies Used

- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JSON Web Tokens (JWT)
- **Deployment**: Render

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/arvindjha131/MPROJECT.git
   cd MPROJECT
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables:
   Create a `.env` file in the root directory with the following variables:
   ```env
   PORT=8080
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

## Project Structure

```
.
├── controllers/      # Handles the application logic
├── models/           # Defines the database schemas
├── routes/           # Contains Express routes for different API endpoints
├── middlewares/      # Custom middleware functions (e.g., authentication, error handling)
├── views/            # For rendering static pages (if needed)
├── utils/            # Utility functions
├── public/           # Static assets (if applicable)
├── .env              # Environment variables
├── app.js            # Entry point of the application
├── package.json      # Project metadata and dependencies
```

## Features in Detail

### Error Handling
- Centralized error handling using middleware.
- Custom error classes for different types of errors.

### MVC Architecture
- Models: Define MongoDB schemas and handle data operations.
- Views: Serve static files (optional, as the project is API-driven).
- Controllers: Contain the core logic for handling requests and responses.

### Validation
- Validation of incoming request data using libraries like **Joi** or **Express Validator**.
- Ensures data integrity and prevents invalid data from reaching the database.

### Express Router
- Modular routing for better scalability and organization.
- Each route has its own file under the `routes/` directory.

### Authentication
- Secure authentication using JWT.
- Middleware to protect private routes.
- Token-based user sessions.

### Deployment
- Deployed on [Render](https://render.com) for reliable and scalable hosting.

## Running Tests

1. Run tests using the following command:
   ```bash
   npm test
   ```

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m 'Add some feature'
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

---

### Contact
For any inquiries or suggestions, feel free to contact us at (mailto:arvindjha131@gmail.com).

