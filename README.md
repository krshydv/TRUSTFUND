# TrustFund — A Transparent Crowdfunding & Donation System

> A secure, transparent, and structured platform for crowdfunding and donations — built with a fully separated backend and frontend for scalability and clean architecture.

---


## Overview

**TrustFund** is a full-stack web application designed to provide a reliable and transparent environment for managing crowdfunding campaigns and donations. The system enables users to create fundraising campaigns, contribute securely, and monitor transaction history in real time.

The application follows a modular, layered architecture with a clearly separated backend and frontend, ensuring scalability, maintainability, and clean code organization.

Key architectural components include:

- A **Node.js & Express** powered RESTful backend API
- A **responsive frontend** interface for user interaction
- **MongoDB** for persistent data storage
- **PayPal integration** for secure, protected financial transactions
- Middleware layers for validation and structured error handling

---

## Features

-  **Campaign Management** — Create, manage, and track crowdfunding campaigns
-  **Secure Payments** — Online donations powered by PayPal
-  **Real-Time Tracking** — Live transaction monitoring and history
-  **Transparent Records** — Clear and accessible fund management
-  **RESTful API** — Clean, resource-oriented API architecture
-  **MVC Architecture** — Modular controllers, routes, and middleware
-  **End-to-End Workflow** — Fully functional from campaign creation to donation receipt

---

## Technology Stack

| Layer | Technology |
|---|---|
| **Backend** | Node.js, Express.js, JavaScript |
| **Frontend** | HTML, CSS, JavaScript |
| **Database** | MongoDB |
| **Payment Gateway** | PayPal |
| **Version Control** | Git & GitHub |

---

## Project Structure
```
TRUSTFUND/
├── trustfund-backend/
│   ├── controllers/        # Business logic handlers
│   ├── routes/             # API route definitions
│   ├── middleware/         # Validation & error handling
│   ├── models/             # MongoDB schemas
│   ├── .env                # Environment variables (not committed)
│   └── server.js           # Entry point
├── trustfund-frontend/
│   ├── index.html          # Main HTML file
│   ├── style.css           # Stylesheet
│   └── app.js              # Frontend logic
└── README.md
```

---

##  Installation & Setup

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/) (v14 or above)
- [MongoDB](https://www.mongodb.com/) (local or Atlas)
- A [PayPal Developer](https://developer.paypal.com/) account

---

### 1. Clone the Repository
```bash
git clone https://github.com/krshydv/TRUSTFUND.git
cd TRUSTFUND
```

### 2. Install Backend Dependencies
```bash
cd trustfund-backend
npm install
```

### 3. Configure Environment Variables

Create a `.env` file inside the `trustfund-backend` folder and add the following:
```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
PAYPAL_CLIENT_ID=your_paypal_client_id
PAYPAL_CLIENT_SECRET=your_paypal_secret
```

### 4. Start the Backend Server
```bash
npm start
```

The server will run at `http://localhost:5000`.

### 5. Run the Frontend

Navigate to the `trustfund-frontend` folder and open `index.html` in your browser, or use a local development server:
```bash
npx serve trustfund-frontend
```

---

##  Environment Variables

| Variable | Description |
|---|---|
| `PORT` | Port number for the backend server |
| `MONGO_URI` | MongoDB connection string |
| `PAYPAL_CLIENT_ID` | PayPal API Client ID |
| `PAYPAL_CLIENT_SECRET` | PayPal API Client Secret |

---

## Future Enhancements

- [ ] User authentication and role-based access control (RBAC)
- [ ] Admin dashboard for monitoring and managing campaigns
- [ ] Automated financial reporting and statements
- [ ] Cloud deployment (AWS / Render / Railway)
- [ ] Enhanced analytics and data visualization tools

---

## Author

**Krish Yadav**  
B.Tech — Computer Science Engineering

---
