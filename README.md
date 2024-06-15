# Education Backend

This repository contains the backend code for an educational platform, built using Node.js and MongoDB. The application handles various functionalities including user management, course management, and more, leveraging a robust and scalable architecture.

## Getting Started

To get the application up and running on your local machine, follow these instructions.

### Prerequisites

Ensure you have the following installed:

- Node.js
- MongoDB
- Nodemon (for development purposes)

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/education-backend.git
    cd education-backend
    ```

2. Install the dependencies:
    ```bash
    npm install
    ```

3. Start the application:
    ```bash
    nodemon index.js
    ```

## File Structure

The project follows a modular structure to maintain scalability and manageability.

```
education-backend/
├── config/                # Configuration files (database, Cloudinary, etc.)
│   ├── database.js
│   ├── cloudinary.js
│   └── ...
├── controllers/           # Request handlers and business logic
│   ├── authController.js
│   ├── courseController.js
│   └── ...
├── models/                # Mongoose models (schemas)
│   ├── User.js
│   ├── Course.js
│   └── ...
├── routes/                # Route definitions
│   ├── authRoutes.js
│   ├── courseRoutes.js
│   └── ...
├── middlewares/           # Custom middleware functions
│   ├── authMiddleware.js
│   └── ...
├── mail/                  # Email-related utilities and templates
│   ├── mailService.js
│   └── ...
├── utils/                 # Utility functions
│   ├── helpers.js
│   └── ...
├── index.js               # Entry point of the application
└── package.json           # Project metadata and dependencies
```

### Config

- **database.js**: MongoDB connection setup.
- **cloudinary.js**: Cloudinary configuration for handling image uploads.

### Controllers

- **authController.js**: Handles authentication (login, registration).
- **courseController.js**: Manages course-related operations.

### Models

- **User.js**: User schema and model.
- **Course.js**: Course schema and model.

### Routes

- **authRoutes.js**: Routes for authentication endpoints.
- **courseRoutes.js**: Routes for course management endpoints.

### Middlewares

- **authMiddleware.js**: Middleware for authentication checks.

### Mail

- **mailService.js**: Utility for sending emails (e.g., registration confirmation).

### Utils

- **helpers.js**: General utility functions used across the application.

## Contributing

We welcome contributions! Please fork this repository and submit pull requests with detailed descriptions of your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries, please contact Robin Poonia at robinpooniadeveloper@gmail.com.
