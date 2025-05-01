# Laruso-CDP: Car Dealership Platform 🚗

Laruso-CDP is an end-to-end, full-stack Car Dealership Platform built using the MERN stack. It provides a seamless experience for users to browse, buy, sell, and service both new and used cars. The platform integrates a powered recommendation system for personalised car suggestions and features a real-time admin dashboard for efficient inventory and request management.

---

## 🔍 Features

### 🌟 Core Functionalities
- **Buy & Sell Cars**: Users can browse, filter, and purchase new or used cars. Sellers can list vehicles through a secure submission process.
- **DL-Powered Car Recommendations**: The platform uses a deep learning model to suggest cars based on user preferences and historical behaviour.
- **Car Services**: Request maintenance, repair, or check-up services (free, paid, or recurring).
- **Secure Payments**: End-to-end payment integration with secure gateways and transaction tracking.
- **Admin Dashboard**: Real-time interface for managing inventory, approving sell/service requests, and monitoring system activity.

### ⚙️ Admin & Performance Enhancements
- **Role-Based Access Control (RBAC)** for customers and admins.
- **Efficient Inventory Management**: Time-saving tools and automatic error checks in the admin panel.
- **Smooth User Experience**: Minimal-click navigation, responsive UI, and mobile-first design.

---

## 💻 Tech Stack

| Layer          | Technology Used           |
|----------------|---------------------------|
| Frontend       | React.js, Bootstrap, Axios |
| Backend        | Node.js, Express.js        |
| Database       | MongoDB (Mongoose)         |
| Authentication | JWT, Bcrypt.js             |
| Payments       | Razorpay / Stripe API      |

---

## 📊 Performance Metrics (Simulated Estimates)

- **Transaction Flow**: Smooth UX and secure payment flows allow consistent task completion.
- **Admin Panel Efficiency**: Real-time updates reduce request approval time significantly.
- **Inventory Management**: Admin dashboard shows faster processing vs manual workflows.

> *Note: These metrics are derived from pilot testing and expected benchmarks, not from live deployment.*

---

## 📁 Project Structure

```
Laruso-CDP/
├── client/             # React Frontend
│   ├── src/
│   └── public/
├── server/             # Node + Express Backend
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   └── utils/
├── config/
├── .env
├── package.json
└── README.md
```

---

## 🚀 Setup Instructions

### 1. Clone the repository:
```bash
git clone https://github.com/your-username/Laruso-CDP.git
cd Laruso-CDP
```

### 2. Setup Backend
```bash
cd server
npm install
npm start
```

### 3. Setup Frontend
```bash
cd ../client
npm install
npm start
```


---

## 👥 Contributors

- **Siddhant**
