# Fullstack JWT Authentication and Role-Based Authorization Admin Panel Dashboard

## Overview

This project is a **Fullstack Application** that demonstrates **JWT Authentication** and **Role-Based Authorization** 
with an **Admin Panel Dashboard**. The backend is built using **ASP.NET Core Web API**, and the frontend is built 
using **React.js**. The application allows users to register, log in, and access different parts of the system based 
on their roles (e.g., Admin, User). Admins can manage users and perform CRUD operations through the dashboard.

---

## Key Features

### 1. **JWT Authentication**
   - Users can register and log in securely using JSON Web Tokens (JWT).
   - Tokens are used for session management and secure access to protected routes.

### 2. **Role-Based Authorization**
   - Different roles (e.g., Admin, User) have access to different parts of the application.
   - Admins can manage users and perform CRUD operations, while regular users have limited access.

### 3. **Admin Panel Dashboard**
   - Admins can view, add, update, and delete users through a user-friendly dashboard.
   - The dashboard provides a clean and responsive interface for managing users.

### 4. **Fullstack Architecture**
   - **Backend**: Built with **ASP.NET Core Web API** for handling authentication, authorization, and CRUD operations.
   - **Frontend**: Built with **React.js** for a dynamic and responsive user interface.

---

## Technologies Used

### Backend
- **ASP.NET Core Web API**: For building RESTful APIs.
- **Entity Framework Core**: For database operations and management.
- **JWT (JSON Web Tokens)**: For secure authentication and authorization.
- **SQL Server**: For storing user data and roles.

### Frontend
- **React.js**: For building the user interface.
- **React Router**: For client-side routing.
- **Axios**: For making HTTP requests to the backend.
- **Tailwind CSS** or **Material-UI**: For styling and responsive design.

---

## How It Works

1. **User Registration and Login**:
   - Users can register by providing their details (e.g., name, email, password).
   - After registration, users can log in using their credentials and receive a JWT for authentication.

2. **Role-Based Access**:
   - Admins have access to the admin panel dashboard, where they can manage users.
   - Regular users have limited access and can only view their profile.

3. **Admin Panel Dashboard**:
   - Admins can view a list of all users, add new users, update existing users, and delete users.
   - The dashboard is designed to be intuitive and easy to use.

4. **Protected Routes**:
   - Certain routes are protected and can only be accessed by authenticated users with the appropriate role.

---

## Setup and Installation

### Backend (ASP.NET Core Web API)

1. Clone the repository:
   ```bash
   git clone https://github.com/ZillaChaudhry/Users-Management-dotnet-react.git
   ```

2. Open the backend project in **Visual Studio** or your preferred IDE.

3. Update the database connection string in `appsettings.json` to point to your SQL Server instance.

4. Run the following commands to apply migrations and create the database:
   ```bash
   dotnet ef database update
   ```

5. Run the backend project:
   ```bash
   dotnet run
   ```

### Frontend (React.js)

1. Navigate to the `client` directory:
   ```bash
   cd Users-Management-dotnet-react/client
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm start
   ```

4. Open your browser and navigate to `http://localhost:3000` to access the application.

---

## Future Enhancements

- Add **password reset functionality** for users.
- Implement **email verification** during registration.
- Add **pagination and filtering** to the admin panel for better user management.
- Enhance the UI with more advanced components and animations.

---
Thank you for checking out this project! 🚀
