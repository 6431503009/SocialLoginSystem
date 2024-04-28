# SocialLoginSystem

Task Week 6 : Back-End Dev for Dev Init

Authors assignment by @BorntoDev

implementation by @Chuntawat

![image](https://github.com/6431503009/SocialLoginSystem/assets/97873903/1fbfd1e2-8abf-481e-8011-408e5eeb4e6d)


This is an SocialLoginSystem application that includes the following features:

## Dependencies

- [dotenv](https://github.com/motdotla/dotenv) - Loads environment variables from a `.env` file.
- [http-errors](https://github.com/jshttp/http-errors) - Creates HTTP errors for Express.
- [express](https://github.com/expressjs/express) - Web application framework for Node.js.
- [path](https://nodejs.org/api/path.html) - Utilities for working with file and directory paths.
- [cookie-parser](https://github.com/expressjs/cookie-parser) - Parses cookie header and populates `req.cookies`.
- [morgan](https://github.com/expressjs/morgan) - HTTP request logger middleware for Node.js.
- [passport](https://github.com/jaredhanson/passport) - Authentication middleware for Node.js.
- [express-session](https://github.com/expressjs/session) - Simple session middleware for Express.
- [connect-sqlite3](https://github.com/marcuswestin/connect-sqlite3) - SQLite3 session store for Express.

## Features

- Loads environment variables from a `.env` file.
- Sets up EJS as the view engine.
- Configures middleware for logging, parsing request bodies, parsing cookies, and serving static files.
- Sets up session management using `express-session` with a SQLite-based session store.
- Initializes Passport for authentication.
- Defines routes using imported routers (`indexRouter` and `authRouter`).
- Sets up a 404 handler for handling non-existent routes.
- Sets up an error handler for handling errors and rendering an error page.

## Usage

1. Install dependencies: `npm install`
2. Start the application: `npm start`

The application will start running on `http://localhost:3000` by default.

## Configuration

- Set environment variables in a `.env` file (e.g., `PORT`, `SESSION_SECRET`).
- Customize routes by modifying the files in the `routes` directory.
- Customize views by modifying the files in the `views` directory.

## License

This project is licensed under the [MIT License](LICENSE).
