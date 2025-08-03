# Project-week-4
# Leave Management System (Frontend + Backend)

## Folder Structure Overview

- `client/`  
  Contains the frontend source code (React).  
  **Note:** The `node_modules/` folder inside `client` has been excluded to reduce file size.  
  You will need to install dependencies after extracting.

- `models/`  
  Backend data models (e.g., Mongoose schemas).

- `routes/`  
  Backend API routes (leave request submission, admin approval, etc.).

- `public/`  
  Static assets (images, favicon, etc.) served by the frontend or backend.

- `server.js`  
  Entry point for the backend server (Express app starter).

- `package.json` & `package-lock.json`  
  Defines the project dependencies and locks their versions.  
  The backend has its own `package.json`, and the frontend has one inside the `client/` folder.

- `.gitignore`  
  Specifies files and folders to ignore (e.g., `node_modules/`).

- `README.md`  
  This documentation file.

## Setup Instructions

> **Step 1:** Extract both zip parts (folders & meta files) into the same root folder.

### Backend Setup:
```bash
# From the root directory (where server.js is located)
# Backend
npm install
node server.js

# Frontend (only if using any Node-based dependencies/tools)
cd client
npm install
# then run build/start if applicable

npm install        # installs backend dependencies
node server.js     # runs the backend server (or use your start script)
