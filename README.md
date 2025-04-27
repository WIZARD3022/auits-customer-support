# 🌞 AUITS Customer Engagement & Support Application

A web application for AUITS Pvt Ltd to streamline customer support, ticket management, payments, and user interactions.

---

## 🚀 Project Overview

This platform allows AUITS customers to:
- Raise and track service tickets
- Access their service history and invoices
- Make secure payments
- Chat with support (optional future feature)
- Manage profiles

It also features an **Admin Dashboard** to manage customer tickets and monitor system performance.

---

## 🛠 Tech Stack

- **Frontend:** React.js (Vite)
- **Backend/Database:** Firebase (Authentication + Firestore)
- **Payments:** Razorpay
- **Hosting:** Vercel (or Firebase Hosting)

---

## 🧩 Core Features

- User Authentication (Login/Registration)
- Dashboard with service history
- Ticket Management (Raise/View tickets)
- Secure Payment Integration (Razorpay)
- Admin Panel for managing tickets
- Mobile Responsive Design

---

## 🔥 Bonus Features (Planned)

- Live Chat Support
- Solar panel performance analytics
- PWA support (offline ready)

---

## 📂 Project Structure

src/ pages/ Home.jsx 
# Landing page with About AUITS and login/register links Login.jsx 
# Login form (Firebase Auth) Register.jsx 
# New user registration form Dashboard.jsx
# User dashboard after login Profile.jsx 
# User profile information and documents Tickets.jsx
# Create and view service tickets Payments.jsx
# Payment integration page AdminDashboard.jsx
# Admin-only panel to manage all tickets components/ Navbar.jsx 
# Navigation bar for the application TicketForm.jsx 
# Form component to create a new ticket TicketList.jsx
# Display list of existing tickets InvoiceList.jsx
# Display list of invoices/payments firebase.js
# Firebase configuration (Auth + Firestore) App.jsx 
# Main app routing and layout main.jsx
# React entry point


---

## 🔑 Setup Instructions

### 1. Clone the Repository
```
git clone https://github.com/your-username/auits-customer-support.git
cd auits-customer-support
```

### 2. Install Dependencies
```
npm install
```

---
## 📜 License
This project is licensed under the MIT License.
