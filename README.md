# Groupe 8

## Gabriel CHANGRENIER

## Valeriya SHIN

## William YANG

# Getting Started with Node.js Backend

This project is built using [Node.js](https://nodejs.org/).

## Available Scripts

In the project directory, you can run:

### `node server.js`

Runs the server in development mode.  
The server will be accessible at [http://localhost:3000](http://localhost:3000) by default (or another port specified in the `.env` file).

### `npm run dev`

Starts the server with **nodemon** for live-reloading during development.

### `npm test`

Launches the test suite using your configured testing framework.  
Refer to the documentation for more details on [running tests](https://jestjs.io/docs/getting-started) or your chosen framework.

### `npm run build`

Compiles the project for production into a `dist` folder (if applicable).  
Ensure the build is optimized and ready for deployment.

## Learn More

- Learn more about Node.js [here](https://nodejs.org/en/docs/).
- For Express-related documentation, check [Express.js Docs](https://expressjs.com/).
- For testing frameworks like Jest, refer to [Jest Documentation](https://jestjs.io/).

## Environment Variables

Make sure to configure your `.env` file with the following keys:

- `PORT` : Port on which the server runs.
- `DB_URI` : MongoDB connection string (if applicable).
- `JWT_SECRET` : Secret key for JWT authentication.

## Deployment

- Follow the guide for deploying Node.js apps [here](https://nodejs.org/en/docs/guides/getting-started-guide/).
- If using Docker, include a `Dockerfile` and `.dockerignore`.

### Additional Notes

This backend supports scalable and modular development, ensuring a clean and maintainable codebase.
