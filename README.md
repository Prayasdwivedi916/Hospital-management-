
# Hospital Management System

## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Technologies Used](#technologies-used)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Contributing](#contributing)
7. [License](#license)

## Introduction
The Hospital Management System is a comprehensive web application built using the MERN stack (MongoDB, Express.js, React.js, and Node.js). It aims to streamline the management of hospital operations by providing features for patient management, appointment scheduling, and staff management.

## Features
- **User Authentication**: Secure login and registration for staff and patients.
- **Patient Management**: Add, edit, and view patient details.
- **Appointment Scheduling**: Schedule and manage appointments between doctors and patients.
- **Staff Management**: Manage doctor and staff details, including roles and responsibilities.
- **Dashboard**: An intuitive dashboard providing an overview of key metrics and information.
- **Search Functionality**: Easily search for patients, doctors, and appointments.
- **Responsive Design**: Accessible on both desktop and mobile devices.

## Technologies Used
- **Frontend**: React.js, Redux, Bootstrap
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Token)
- **Other Tools**: Mongoose, Axios, Bcrypt.js

## Installation
Follow these steps to install and set up the project locally:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Prayasdwivedi916/Hospital-management-.git
   cd Hospital-management-
   ```

2. **Install server dependencies:**
   ```bash
   cd server
   npm install
   ```

3. **Install client dependencies:**
   ```bash
   cd ../client
   npm install
   ```

4. **Set up environment variables:**
   Create a `.env` file in the `server` directory and add the following:
   ```plaintext
   MONGO_URI=your_mongo_database_uri
   JWT_SECRET=your_jwt_secret
   ```

5. **Start the server and client:**
   ```bash
   # In the server directory
   npm start

   # In the client directory
   npm start
   ```

6. **Access the application:**
   Open your browser and navigate to `http://localhost:3000`.

## Usage
- **Admin Panel**: Accessible to administrators for managing hospital operations.
- **Doctor Panel**: Accessible to doctors for managing patient appointments and records.
- **Patient Portal**: Accessible to patients for viewing their records and scheduling appointments.

## Contributing
Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature-name`).
5. Open a pull request.

