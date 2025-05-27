# Express EJS App

This is a simple Express.js application that uses EJS as the templating engine to render a "Hello World" message.

## Project Structure

```
express-ejs-app
├── src
│   ├── app.js          # Entry point of the application
│   ├── views
│   │   └── index.ejs   # EJS template for rendering the message
│   └── routes
│       └── index.js    # Route definitions
├── package.json        # NPM configuration file
└── README.md           # Project documentation
```

## Getting Started

1. Clone the repository:
   ```
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```
   cd express-ejs-app
   ```

3. Install the dependencies:
   ```
   npm install
   ```

4. Start the application:
   ```
   npm start
   ```

5. Open your browser and go to `http://localhost:3000` to see the "Hello World" message.

## Dependencies

- express: A minimal and flexible Node.js web application framework.
- ejs: A simple templating language that lets you generate HTML markup with plain JavaScript.