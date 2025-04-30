# Employee Management System (MERN)

## Overview
The **Employee Management System** is a full-stack application built with the MERN stack (MongoDB, Express.js, React, Node.js) and Vite. This system helps organizations efficiently manage employee details, tasks, and deadlines.

### Features:
- **Employee Management**: Store and manage employee details.
- **Task Management**: Employers can assign tasks and deadlines; employees can view their tasks.
- **Authentication**: Secure login system for employees and employers.
- **Real-time Updates**: Track and update task statuses seamlessly.

---

## Installation and Setup

### Prerequisites
- Node.js (v16 or later)
- npm or yarn
- MongoDB (local or hosted database like MongoDB Atlas)

### Steps to Set Up the Project

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/employee-management-system.git
   cd employee-management-system
   ```

2. **Install Dependencies**
   Install dependencies for both the client and server:
   
   - Navigate to the `client` directory and install dependencies:
     ```bash
     cd client
     npm install
     ```
     
   - Navigate to the `server` directory and install dependencies:
     ```bash
     cd ../server
     npm install
     ```

3. **Configure Environment Variables**
   - Create an `.env` file in the `server` directory:
     ```
     PORT=5000
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret_key
     ```
   - Replace placeholders with your actual values.

4. **Run the Application**
   - Start the server:
     ```bash
     cd server
     npm run dev
     ```
   - Start the client:
     ```bash
     cd ../client
     npm run dev
     ```
   - Open your browser and navigate to the development server URL (e.g., `http://localhost:5173`).

---



### Backend
- Express.js
- MongoDB (mongoose)

### Frontend
- React.js
- Tailwind CSS (or other CSS framework, if used)
