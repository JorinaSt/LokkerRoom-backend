# LokkerRoom-Back-End

## What
This is the back-end for a chat application built with Express.js. It handles user authentication, chat room management, and message storage using PostgreSQL as the database. The back-end is designed to be the communication layer for the front-end, providing RESTful API endpoints for various operations.

## Why
This project was developed to create a real-time chat application. It serves as the back-end infrastructure, allowing users to register, log in, send messages, and interact with each other through chat rooms.

## When
The project was developed as part of a challenge to create a complete full-stack chat application. The back-end was built and deployed on [Heroku](https://www.heroku.com/).

## How
The back-end is built with the following technologies:
- **Express.js** for the web framework
- **pg** for PostgreSQL integration
- **bcrypt** for password encryption
- **jsonwebtoken** for JWT-based authentication
- **dotenv** for environment variables
- **cors** to allow cross-origin requests

To run the back-end locally, follow these steps:
1. Clone the repository.
2. Install the dependencies with `npm install`.
3. Create a `.env` file with the necessary environment variables (e.g., `DATABASE_URL`, `JWT_SECRET`).
4. Start the server with `npm start`.
5. Test the API endpoints using a tool like Postman or Insomnia.


## Roadmap
Here are some pending tasks and future improvements for the back-end:
- Fixing API integration issues and connection problems with Heroku.
- Implementing additional security measures.
- Enhancing error handling and logging.

## Links
- [GitHub Repository]
- [Live Version on Heroku]
