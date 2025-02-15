﻿# Project Setup Instructions
 ### Demo Test User Credentials

Here are demo test user credentials you can use to test the application:

- **User Account:**
  - **Email:** `user@user.com`
  - **Password:** `S~}DRbq?aGY"/9W)`

- **Admin Account:**
  - **Email:** `admin@admin.com`
  - **Password:** `S~}DRbq?aGY"/9W)`

## Frontend Setup

1. **Create a `.env` File**

   In the `frontend` directory, create a `.env` file if it does not already exist.

2. **Add API Base URL**

   Add the following line to the `.env` file, replacing `PORTNUMBER` with the actual port number where your backend is running:

   ```env
   VITE_API_URL=http://localhost:PORTNUMBER

## Backend Setup

### Create a `.env` File

In the `backend` directory, create a `.env` file if it does not already exist.

### Add Environment Variables

Add the following lines to the `.env` file, replacing the placeholder values with your actual configuration:

```env
PORT=Number
DEV_MODE=development
MONGO_URL=URL
JWT_SECRET=ANY-RANDOM-KEY

