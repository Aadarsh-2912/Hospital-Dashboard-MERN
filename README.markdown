# MERN Stack Hospital Management System

A full-featured Hospital Management Web Application built using the **MERN Stack** (MongoDB, Express.js, React.js, Node.js). This system is designed for hospital administrators, doctors, and patients to manage appointments, records, and communication efficiently.

---

## 🚀 Live Demo

- **Admin Dashboard:** https://hospital-dashboard-mern-p2nazntaa-aadarsh-2912s-projects.vercel.app
- **User Dashboard:** https://hospital-dashboard-mern-p2nazntaa-aadarsh-2912s-projects.vercel.app

> **Note:** Login with the following credentials to access dashboard features.

### Login Credentials

- **Admin Login**:
  - **Email:** `admin1@example.com`
  - **Password:** `AdminPass123`

- **User Login**:
  - **Email:** `ali.khan@example.com`
  - **Password:** `StrongPass123`

---

## ✅ Features

### Patient Panel

- Secure signup & login
- Book department-based appointments
- View appointment history
- Contact hospital via message form

### Admin Panel

- Secure login
- Add/edit/delete doctors and patients
- View and manage all appointments
- View and respond to contact messages

---

## 🛠 Tech Stack

| Technology | Description |
| --- | --- |
| **MongoDB** | NoSQL Database |
| **Express.js** | Backend framework for Node.js |
| **React.js** | Frontend library |
| **Node.js** | JavaScript runtime environment |
| **JWT** | Authentication |
| **TailwindCSS** | UI Styling |
| **Axios** | HTTP client for API calls |
| **Mongoose** | MongoDB ODM |

---

## 📁 Folder Structure

```
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
│   ├── src/
│   │   ├── components/     # Reusable UI components
│   │   ├── pages/          # Route-based pages
│   │   ├── App.js          # React routing
│   │   └── index.js        # Entry point
│
├── README.md               # Project documentation
└── package.json            # Project dependencies and scripts
```

---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/Aadarsh-2912/MERN-Stack-Hospital-Management-System.git
cd MERN-Stack-Hospital-Management-System
```

### 2. Set Environment Variables

Create a `.env` file in the `backend/` directory and add the following:

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

### 3. Install Backend Dependencies

```bash
cd backend
npm install
```

### 4. Install Frontend Dependencies

```bash
cd ../frontend
npm install
```

### 5. Run Locally

Start the backend server:

```bash
cd backend
npm start
```

Start the frontend app:

```bash
cd ../frontend
npm start
```

- The backend will run on `http://localhost:5000`.
- The frontend will run on `http://localhost:3000`.

---

## 📡 API Overview

### User Routes

- `POST /api/v1/user/register` - Register new patient
- `POST /api/v1/user/login` - Login for user/admin
- `POST /api/v1/user/addnew` - Add doctor/patient (Admin only)

### Appointment Routes

- `POST /api/v1/appointment/post` - Book an appointment
- `GET /api/v1/appointment/getall` - View all appointments (Admin only)
- `PUT /api/v1/appointment/update/:id` - Update an appointment
- `DELETE /api/v1/appointment/delete/:id` - Delete an appointment

### Message Routes

- `POST /api/v1/message/send` - Send a contact message
- `GET /api/v1/message/getall` - View all messages (Admin only)

---

## 📄 License

This project is licensed under the MIT License.

---

## 📬 Contact

- **GitHub:** Aadarsh-2912
- **Email:** aadarshanand2912@gmail.com
