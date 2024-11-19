# Notes App

This is a simple notes-taking application that allows users to create, update, delete, and manage their notes. The project is structured with a backend server and a frontend client.

---

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Setup Instructions](#setup-instructions)
  - [Prerequisites](#prerequisites)
  - [Clone the Repository](#clone-the-repository)
  - [Backend Setup](#backend-setup)
  - [Frontend Setup](#frontend-setup)
- [Usage](#usage)
- [License](#license)

---

## Features

- Create, update, and delete notes
- User authentication and authorization
- Responsive UI
- Secure API endpoints

---

## Tech Stack

### Frontend
- React
- TailwindCSS

### Backend
- Node.js
- Express.js
- MongoDB

---

## Setup Instructions

### Prerequisites

Before you begin, ensure you have the following installed on your system:

- [Node.js](https://nodejs.org/) (v14 or later)
- [Git](https://git-scm.com/)
- [MongoDB](https://www.mongodb.com/docs/manual/installation/)

---

### Clone the Repository

1. Open a terminal and run the following command to clone the repository:

   ```bash
   git clone https://github.com/AkaniX3/Notes-app.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Notes-app
   ```

---

### Backend Setup

1. Navigate to the backend folder:

   ```bash
   cd backend
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Create an `.env` file in the backend folder and add the following environment variables:

   ```env
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   ```

4. Start the backend server:

   ```bash
   npm start
   ```

   The backend server should now be running at `http://localhost:5000`.

---

### Frontend Setup

1. Navigate to the frontend folder:

   ```bash
   cd ../frontend
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the frontend development server:

   ```bash
   npm start
   ```

   The frontend application should now be running at `http://localhost:3000`.

---

## Usage

1. Open your browser and navigate to `http://localhost:3000`.
2. Sign up or log in to your account.
3. Start creating, updating, and managing your notes.

---

ty 🍞✨

