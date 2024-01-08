Description:

This Node.js Express application manages users and products, allowing user registration, login, and product manipulation. The app utilizes Express.js, PostgreSQL for database management, and various npm packages for session handling, form validation, and data storage.

Prerequisites:

Before running the application, ensure you have the following dependencies installed:

- Node.js
- PostgreSQL

Installation:

- Clone the repository to your local machine.
  
Install project dependencies:

npm install express body-parser pg express-validator express-session cookie-parser connect-pg-simple randomatic crypto uuidv4

Configuration:

- Set up your PostgreSQL database.
- Modify the pool configuration in app.js to match your database credentials:

const pool = new Pool({
    user: "your_username",
    password: "your_password",
    host: 'localhost',
    port: 5432,
    database: "your_database_name"
});

Usage

Start the server:

- node app.js
- Access the application at http://localhost:3000 in your web browser.

Usage Example:

- Access http://localhost:3000 to view the login page.
- Use the login and signup functionalities to interact with the app.
Structure

- app.js: Main application file containing route handling and server setup.
- views/: Contains .pug files for rendering HTML views.
- public/: Contains static files (e.g., CSS).

Dependencies:

Express: Web application framework for Node.js.
Body-parser: Middleware to handle HTTP POST requests.
pg: PostgreSQL client for Node.js.
express-validator: Middleware for input validation.
express-session: Session middleware for Express.
cookie-parser: Middleware for parsing cookies.
connect-pg-simple: Session store for Express and PostgreSQL.
randomatic: Generates random strings.
crypto: Cryptographic functionalities.
uuidv4: Generates UUIDs.


Contribution: 

Kusai Elmusraty

