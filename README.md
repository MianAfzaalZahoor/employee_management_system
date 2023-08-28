# Employee Management System Backend

This is the backend component of an Employee Management System built with Node.js, Express, TypeScript, and PostgreSQL.

### Contents

- [Technology stack](#technology-stack)
- [Installation](#installation)
- [Testing](#testing)

## Technology stack

- Node.js: Compatible version (recommended: Node.js 14+)
- Express: ^4.18.2
- PostgreSQL: ^11.5.4
- TypeScript: ^4.4.4

## Installation

### Setting up the development environment

1.  Get the code. Clone this git repository and check out the latest release:

    ```bash
    git clone https://github.com/MianAfzaalZahoor/ems.git
    ```

2.  Install the required packages by running the following command in the project root directory:

    ```bash
    cd ems
    npm install
    ```

3.  Create an `.env.production` file for configuration:

    ```bash
    touch .env.production
    ```

4.  Add your database configuration details and other environment variables to `.env.production`. You will probably only need to fill in the password for the database(s).

5.  Create and populate the database with seeds using:

    ```bash
    npm run seed
    ```

6.  Run the server:

    ```bash
    npm start
    ```

7. Access the API at:

    ```
    http://localhost:5000
    ```

## Testing

To run tests for the application, follow these steps:

1. Make sure you have completed the installation steps above.

2. Run the following command in the project root directory:

    ```bash
    npm test
    ```

   This will execute the tests and provide you with information about the test results.

