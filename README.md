# 1337 Badge Management System

A comprehensive web application for managing student badges at 1337 Coding School. This system allows administrators to track students, manage badge losses, handle payments, and print replacement badges.

## 📋 Overview

The 1337 Badge Management System is designed to streamline the process of handling student badge management. It offers a complete solution for administrators to:

- Track all students and their information
- Record and manage badge losses
- Process payments for replacement badges
- Print new badges
- Manage user accounts with different permission levels

## ✨ Features

### Student Management
- Create, view, edit, and delete student profiles
- Import students from Excel files
- Export student data with badge history
- Search and filter students
- Generate printable replacement badges

### Badge Management
- Declare lost badges with automatic pricing calculation
- Track badge loss history per student
- Update payment status

### User Management
- Role-based access control system
- Custom permission settings for different user roles
- Secure authentication with password recovery
- User invitation system for new administrators

### Dashboard
- Visual analytics of badge loss trends
- Payment status overview
- Student statistics
- Recent activity monitoring

## 🛠️ Technologies Used

### Frontend
- React.js
- Context API for state management
- Recharts for data visualization
- React Icons for UI elements
- CSS3 with custom styling
- Dark/Light mode theming

### Backend
- Node.js
- Express.js
- MongoDB with Mongoose
- JWT Authentication
- Nodemailer for email notifications

## 📦 Installation

### Prerequisites
- Node.js (v14 or higher)
- MongoDB (v4 or higher)
- npm or yarn

### Setup Instructions

1. Clone the repository
```bash
git clone https://github.com/AsmaeMouncif/badge_system.git
cd 1337-badge-system
```

2. Install dependencies
```bash
# Install backend dependencies
cd badgebackend
npm install

# Install frontend dependencies
cd badgefrontend
npm install
cd ..
```

3. Environment setup
Create a `.env` file in the root directory with the following variables:
```
MONGO_URI=mongodb://localhost:27017/badge_sys
JWT_SECRET=your_jwt_secret_key
EMAIL_USER=your_email@gmail.com
EMAIL_PASS=your_email_app_password
FRONTEND_URL=http://localhost:3000
```

4. Initialize the database
```bash
# Create default roles and admin account
npm run create-admin
```

5. Start the application
```bash
# Run backend and frontend
npm start

## 🚀 Usage

### Admin Login
1. Access the application at http://localhost:3000
2. Login with the default administrator credentials:
   - Email: admin@example.com
   - Password: Admin1337!

### Managing Students
- Navigate to the Students page
- Add new students manually or import from Excel
- Search for students by name or login
- Print Badge

### Declaring Lost Badges
- Navigate to the Badges page
- Search for a student
- Click "Add Lost Badge"
- Badge prices are automatically calculated based on loss history

### User Administration
- Navigate to the Accounts page to manage users
- Create new user accounts via email invitation
- Manage roles and permissions on the Roles page

## 👥 Contributors

- Asmae Mouncif - Developer
- Saida Adraoui - Developer
- Hanane Makboul - Developer

## 🙏 Acknowledgements

- [1337 Coding School](https://1337.ma/) for the inspiration and support
- All contributors who helped improve this project

## 📞 Contact

For any questions or suggestions, please contact:
- Email: your.email@example.com
- GitHub: [@yourusername](https://github.com/yourusername)
