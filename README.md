# Full Stack Notes App

This full stack notes application is built using React, Node.js, and PostgreSQL. The application includes the following key features:

- **Create/Edit/Delete Notes**: Perform CRUD operations to manage your notes effectively.
- **Validation on the UI and Backend**: Ensure data integrity and validate user inputs on both the frontend and backend.
- **Responsive Design**: Develop a user-friendly interface that adapts seamlessly to various screen sizes, including mobile devices.

## Technologies Used

- **Frontend**: React
- **Backend**: Node.js
- **Database**: PostgreSQL

## Getting Started

To get a local copy up and running, follow these steps.

### Prerequisites

- Node.js installed on your machine
- npm (Node Package Manager) installed
- PostgreSQL installed locally or on a remote server

### Installation

1. Clone the repository

   ```bash
   git clone <repository-url>
   cd <repository-folder>

2. Install dependencies
   ```bash
   # Install server dependencies
   cd server
   npm install

   # Install client dependencies
   cd ../client
   npm install

### Database Setup
1. Create a PostgreSQL database for the application.

2. Update the database connection configuration in `server/config/db.config.js` with your database credentials.

### Running the Application

1. Start the server
   ```bash
   # From the server directory
   npm start

2. Start the client
   ```bash
   # From the client directory
   npm start

3. Open your web browser and navigate to `http://localhost:3000` to view the application.
