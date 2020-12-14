# Rating Project Development Documentation

## Required Languages/Runtimes
- Node.js (backend/frontend)
- TypeScript (backend/frontend)
- Yarn (frontend)
### Recommended (Required) IDE
- Any IDE that can compile and run TypeScript.
- Our Preference: Webstorm (frontend/backend)
### Software Needed to Clone and Run the Programs
- Git
    - Used to clone repositories onto your system.
- Postgres (v. 13.1).
  - Ensure that Postgres is configured to the default settings during installation.
    
## Replicating the Development Environment
### Replicating the Backend/Database
- Run the command `git clone https://github.com/Eli017/rating-project-backend` to clone the repository.
- Ensure that Postgres is currently running on your local machine.
- Navigate into the recently cloned application where it is on your local machine via the terminal.
- Run the command `npm install` to install the dependencies for the backend.
- Create the database `rating-project` along with a schema of the same name.
- Replicate the sample `.env` files into their `.env` files for your local machine. This is how the application connects to the database.
  - Ensure that it is pointing to the correct database and schema.
- Run the command `npx prisma migrate up --experimental`.
  - This pulls the latest migration database snapshot and creates the necessary tables for the database.
- To seed the database with dummy data, run the command `npm run seed`.
- Finally, run the command, `npm run start` to start the server in development mode.
- To ensure that it is running, navigate to http://localhost:3000/graphql to see the graphql playground running.

### Replicating the Frontend
- Run the command `git clone https://github.com/Eli017/rating-project-frontend` to clone the repository.
- Navigate into the recently cloned application where it is on your local machine via the terminal.
- Run the command `yarn` to install the necessary dependencies for the frontend.
- Create an `.env` file in the root of the application that contains this line:
`API_URL=http://localhost:3000/graphql` where API_URL is equal to the backend's application graphql server.
- Ensure that the backend is currently running.
- Run the command `yarn start` to start the application.
  - If the command line asks you to run the application on another port, type "Yes" and press enter.

## Tests
### Frontend
- Navigate to the project root via the terminal.
- Run the command, `yarn test` to run any tests.
### Backend
- Navigate to the project root via the terminal.
- Run the command, `jest` to run any tests.
