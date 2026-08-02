# 🚀 NovaSpace

NovaSpace is a simple and modern **HTML & CSS** static website that demonstrates a complete user authentication flow with separate **User** and **Admin** portals. The project is designed for beginners to practice multi-page website development using only HTML and CSS.

---

## 📌 Features

- 🏠 Landing Page
- 👤 User Registration
- ✉️ Email OTP Verification UI
- 🔐 User Sign In
- 🛡️ Admin Sign In
- 📊 User Dashboard
- ⚙️ Admin Dashboard
- 📱 Responsive and Clean Layout
- 🎨 Modern UI Design
- 💻 Beginner-Friendly Code Structure

---

## 📂 Project Structure

```
NovaSpace/
│
├── index.html
├── style.css
│
├── account.html
├── account.css
│
├── signup.html
├── signup.css
│
├── verification.html
├── verification.css
│
├── signin.html
├── signin.css
│
├── dashboard.html
├── dashboard.css
│
├── adminSignin.html
├── adminSignin.css
│
├── adminDashboard.html
├── adminDashboard.css
│
└── images/
```

---

##  Flow

```
Landing Page
      │
      ▼
Choose Account
      │
 ┌────┴────┐
 │         │
 ▼         ▼
User     Admin
 │         │
 ▼         ▼
Sign Up   Admin Login
 │         │
 ▼         ▼
OTP        Admin Dashboard
 │
 ▼
User Login
 │
 ▼
Dashboard
```
## 🛠️ Technologies Used

- HTML5
- CSS3
- Tailwind CSS *(used only for the Choose Account page)*
- Flexbox
- CSS Grid
- Box Shadow
- Hover Effects
---

## 👤 User Registration

The Sign Up page collects the following information:

- Full Name
- Email Address
- Phone Number
- Password
- Confirm Password

After successful registration, the user is redirected to the OTP Verification page.

---

## ✉️ OTP Verification

The verification page provides a simple UI for entering a **6-digit OTP**.

After verification, users can continue to the Sign In page.

---

## 🔐 User Login

Users can log in using:

- Email Address
- Password

After signing in successfully, they are redirected to the User Dashboard.

---

## 🛡️ Admin Login

Administrators have a separate login page.

Admin credentials:

- Admin Email
- Password

Successful login redirects to the Admin Dashboard.

---

## 📊 User Dashboard

The dashboard includes:

- Welcome Section
- Project Statistics
- Tasks
- Messages
- Notifications
- Recent Projects Table

---

## ⚙️ Admin Dashboard

The Admin Dashboard includes:

- Dashboard Overview
- Total Users
- Active Users
- Projects
- Reports
- Registered Users Table

---
