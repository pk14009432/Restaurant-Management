# Restaurant Management System

A Node.js and Express web application prototype for managing restaurant operations such as bookings, tables, menu items, staff records and billing.

## Features represented in the source structure

- Customer and user account flows
- Table and booking management
- Food and drink menu management
- Chef and waiter management
- Billing and dashboard routes
- Server-rendered pages using EJS
- MongoDB data models using Mongoose
- Local authentication integration using Passport

## Technology stack

- Node.js
- Express
- MongoDB and Mongoose
- EJS
- Passport and Passport Local
- Bootstrap and jQuery

## Project structure

- `app.js` — Express application entry point and route registration
- `config/` — database and Passport configuration
- `controllers/` — request/business logic
- `models/` — Mongoose data models
- `routes/` — application routes
- `views/` — EJS templates (where present)
- `public/` and `uploads/` — static assets (where present)

## Run locally

### Prerequisites

- Node.js and npm
- MongoDB running locally

### Steps

1. Clone this repository.
2. Open a terminal in the project directory.
3. Install dependencies:

   ```bash
   npm install
   ```

4. Ensure MongoDB is running and the database connection in `config/database.js` points to your local instance.
5. Start the application:

   ```bash
   npm start
   ```

6. Open `http://localhost:3000` in your browser.

## Security and maintenance notes

This is an older educational project and should be treated as a prototype, not a production-ready service. Before deployment, move the session secret and database configuration into environment variables, rotate any secret that has ever been committed, use maintained dependency versions, review authentication/session settings, and validate uploads and user input.

## Project status

Educational project. Installation and feature descriptions should be verified against a fresh local setup before production use.

## Author

Pintu Kumar
