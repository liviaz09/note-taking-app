
# Note-Taking App

## Overview
This Note-Taking App is a full-stack web application designed to demonstrate the integration of a Node.js backend with a front-end interface using HTML, CSS, and server-side JavaScript. The application supports CRUD operations for managing notes, with a focus on RESTful API design and server-side validation.

## Technology Stack
- **Frontend:** HTML, CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB

## Getting Started

### Prerequisites
Before running the app locally, you need to have the following installed:
- **Node.js**
- **MongoDB**.
- **npm** or **yarn**

### Installation and Setup

1. **Clone the repository**:
   Open a terminal and run the following command to clone the repository to your local machine:
   ```bash
   git clone https://github.com/liviaz09/note-taking-app.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd backend
   ```

3. **Install project dependencies**:
   Run the following command to install the necessary Node.js dependencies:
   ```bash
   npm install
   ```

4. **Set up MongoDB**:
   - Ensure that **MongoDB** is running locally on your machine.
   - The default URI for a local MongoDB instance is `mongodb://localhost:27017/todolist`. If you've set a different URI, adjust it in the `.env` file.

5. **Set up environment variables**:
   - Edit the `.env` file and set the following variables:
     ```
     MONGO_URI=mongodb://localhost:27017/todolist
     PORT=3000
     ```

6. **Start the server**:
   After setting up the database and environment variables, run the following command to start the backend server:
   ```bash
   npm start
   ```
   This will start the server on `http://localhost:3000`.

7. **Access the frontend**:
   Open your browser and go to `http://localhost:3000` to view the application. You should see the Note-Taking App interface.
