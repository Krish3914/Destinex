# Destinex: Trip Management System

## Project Overview 📚

The **Destinex** is designed to streamline the process of searching, booking, and managing trip packages. This system will allow users to effortlessly browse through multiple trip packages, check available hotels, transport facilities, and other relevant details in a user-friendly manner. The goal of this project is to simplify the process of managing and booking travel packages by integrating various features in one platform, eliminating the time-consuming process of navigating multiple travel websites and dealing with different travel agents.

---

## Features ✨

### Admin Features:
- **Admin Authentication**: Only registered admins with a valid session token can manage the application.
- **Package Management**: Admin can add, update, and delete trip packages, hotels, routes, and customer details.
- **Booking Management**: Admin can view, update, and manage all booking details.
- **Route Management**: Admin can manage and add new routes.
- **Report Management**: Admin can view detailed reports on bookings, packages, and customer feedback.
  
### User Features:
- **User Registration & Authentication**: Users can register, log in, and maintain their session.
- **Trip Package Search**: Users can browse available trip packages, view details about hotels, routes, and transport.
- **Package Booking**: Users can select and book trip packages by providing payment details.
- **Booking Details**: After booking, users can view detailed information about the package, including total cost, ticket details, etc.
- **Booking Cancellation**: Users can cancel their booking if necessary.
- **Feedback System**: Users can provide feedback on their trip experience.

---

## Architecture 🔧

This system is built using the **CRUD** (Create, Read, Update, Delete) operations and follows the **MVC** (Model-View-Controller) architectural pattern.

- **Frontend**: 
  - **ReactJS**: Used to create a dynamic and responsive user interface.
  - **JavaScript**: Main programming language for frontend development.
  
- **Backend**:
  - **NodeJS**: Used for building server-side logic and managing API requests.
  - **ExpressJS**: Framework for routing and handling HTTP requests.
  - **MongoDB**: NoSQL database for storing all user, package, and booking data.

- **Authentication**:
  - Session-based authentication using **UUID** for validation and security.

---

## Database Schema 🗂️

The **MongoDB** database structure includes the following collections:

- **Users**: Stores user information, registration details, and session data.
- **Admins**: Stores admin login credentials and session tokens.
- **Packages**: Stores information about available trip packages (destination, cost, hotel, transport, etc.).
- **Bookings**: Stores booking details (user, package, cost, payment details, etc.).
- **Feedback**: Stores customer feedback for each package.
- **Routes**: Stores information about different travel routes available for trips.
- **Reports**: Stores administrative reports on bookings, feedback, and overall performance.

---

## Modules ⚙️

1. **Login/Logout Module**: User and admin authentication.
2. **User Module**: User registration, login, and trip package browsing.
3. **Admin Module**: Admin dashboard for managing packages, users, and reports.
4. **Booking Management Module**: Manages the booking and cancellation process for users.
5. **Feedback Module**: Collects and manages user feedback on trips.
6. **Report Module**: Generates reports based on bookings, packages, and customer data.
7. **Trip Package Management Module**: Handles the creation and modification of trip packages.
8. **Route Management Module**: Manages and updates travel routes available for booking.

---

## Software Requirements 💻

- **Operating System**: Windows 10, Linux, or Mac
- **Programming Language**: JavaScript
- **IDE Used**: VS Code, STS
- **Database**: MongoDB
- **Frameworks**: ReactJS, NodeJS
- **Architecture**: CRUD, MVC
- **Languages and Tools**: JavaScript, ReactJS, NodeJS, Python, Machine Learning

---

## Getting Started 🚀

### 1. Clone the Repository

```bash
git clone https://github.com/Krish3914/Destinex.git
```
### 2. Install Dependencies
Navigate to the project directory and install dependencies:
```bash
cd destinex
npm install
```


### 3. Set Up the MongoDB Database
Ensure you have MongoDB installed and running locally or use a cloud MongoDB service. Update your connection details in the backend configuration file.

### 4. Run the Application
To start the development server for the frontend:
```bash
cd frontend
npm run start
```


To run the backend server:
```bash
cd backend
npm run start
```
Now, the application should be running locally at http://localhost:5173.



## Contributing 🤝
### We welcome contributions to improve this project! If you'd like to contribute:
```bash
Fork the repository
Create a new branch (git checkout -b feature/your-feature)
Commit your changes (git commit -am 'Add new feature')
Push to the branch (git push origin feature/your-feature)
Create a new Pull Request
```

## License 📄
### This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements 🙏
```bash
ReactJS
NodeJS
MongoDB
ExpressJS
VS Code
```
