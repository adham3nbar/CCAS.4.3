# eLearn System

## Project Overview
The eLearn System is a web-based e-learning application that provides authentication, course viewing, and administrative management functionalities. The system is built using a static frontend (HTML, CSS, JavaScript) and a backend API that handles authentication, authorization, and data operations. The project demonstrates full-stack integration, role-based access control, and structured testing and validation.

---

## System Architecture
The project follows a client–server architecture:

- **Frontend:** Static HTML and JavaScript files responsible for user interaction and UI rendering.
- **Backend:** RESTful API responsible for authentication, authorization, and data processing.
- **Database:** Stores users, roles (admin/student), and courses.

The frontend communicates with the backend using HTTP requests (Fetch API).

---

## Technologies Used

### Frontend
- HTML
- CSS
- JavaScript (Vanilla JS)
- Browser Fetch API

### Backend
- Node.js
- Express.js (or equivalent backend framework)
- CORS middleware for cross-origin requests

### Tools
- Git & GitHub (source code management)
- Python (for serving frontend locally)
- Browser Developer Tools (testing and debugging)

---

## Repository Structure



---

## Setup and Run Instructions

### 1. Prerequisites
- Node.js installed
- Python 3 installed
- Web browser (Chrome / Edge / Safari)

---

### 2. Run the Backend
Open a terminal and run:

```bash
cd elearn-frontend/elearn-backend
npm install
npm start


The backend will start on:
http://localhost:3000

Open a new terminal tab and run:
cd elearn-frontend
python3 -m http.server 5500

Open the application in the browser:
http://localhost:5500
