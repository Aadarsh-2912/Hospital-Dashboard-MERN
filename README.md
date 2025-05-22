# MERN Stack Hospital Management System

A full-featured Hospital Management Web Application built using the **MERN Stack** (MongoDB, Express.js, React.js, Node.js). This system is designed for hospital administrators, doctors, and patients to manage appointments, records, and communication efficiently.

---

## Live Demo

- **Admin Dashboard:** [https://hospital-dashboard-mern-p2nazntaa-aadarsh-2912s-projects.vercel.app](https://hospital-dashboard-mern-p2nazntaa-aadarsh-2912s-projects.vercel.app)
- **User Dashboard:** [https://hospital-dashboard-mern-p2nazntaa-aadarsh-2912s-projects.vercel.app](https://hospital-dashboard-mern-p2nazntaa-aadarsh-2912s-projects.vercel.app)

> Login with respective credentials to access dashboard features.

---

## Features

### ✅ Patient Panel
- Secure signup & login
- Book department-based appointments
- View appointment history
- Contact hospital via message form

### ✅ Admin Panel
- Secure login
- Add/edit/delete doctors and patients
- View and manage all appointments
- View and respond to contact messages

---

## Tech Stack

| Tech            | Description                       |
|-----------------|-----------------------------------|
| **MongoDB**     | NoSQL Database                    |
| **Express.js**  | Backend framework for Node.js     |
| **React.js**    | Frontend library                  |
| **Node.js**     | JavaScript runtime environment    |
| **JWT**         | Authentication                    |
| **TailwindCSS** | UI Styling                        |
| **Axios**       | HTTP client for API calls         |
| **Mongoose**    | MongoDB ODM                       |

---

## Folder Structure

```bash
MERN-Stack-Hospital-Management-System/
│
├── backend/                # Express backend with MongoDB
│   ├── controllers/        # Request handling logic
│   ├── models/             # Mongoose models
│   ├── middlewares/        # Auth & error handling
│   ├── routes/             # API endpoints
│   └── app.js              # Main server entry point
│
├── frontend/               # React app
│   ├── src/components/     # Reusable UI components
│   ├── src/pages/          # Route-based pages
│   ├── src/App.js          # React routing
│   └── src/index.js        # Entry point
