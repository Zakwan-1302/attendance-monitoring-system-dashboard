# Attendance Monitoring System Dashboard

A full-stack web application designed to streamline student attendance management for educational institutions. The system enables administrators and faculty members to manage students, departments, attendance records, and generate reports while providing SMS notifications through Twilio integration.

---

## Features

### Student Management

* Add, update, and manage student records
* Department-wise student organization
* Student attendance history tracking

### Attendance Tracking

* Mark and update attendance records
* Real-time attendance monitoring
* Attendance report generation

### Faculty Dashboard

* Dedicated dashboard for faculty members
* Attendance management interface
* Student performance monitoring

### SMS Notifications

* Automated SMS alerts using Twilio
* Attendance-related notifications
* Communication with students and parents

### Authentication & Security

* User registration and login
* JWT-based authentication
* Protected routes and role-based access

---

## Tech Stack

### Frontend

* React.js
* Vite
* Axios
* React Router

### Backend

* Node.js
* Express.js
* MongoDB
* JWT Authentication
* Twilio SMS API

### Deployment

* GitHub
* Vercel (Frontend)
* Render/Vercel (Backend)

---

## Project Structure

```
Attendance-Monitoring-System/
│
├── Backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middlewares/
│   └── config/
│
├── Frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── context/
│   └── public/
│
└── README.md
```

---

## Installation

### Clone Repository

```bash
git clone https://github.com/Zakwan-1302/attendance-monitoring-system-dashboard.git
cd attendance-monitoring-system-dashboard
```

### Backend Setup

```bash
cd Backend
npm install
npm start
```

### Frontend Setup

```bash
cd Frontend
npm install
npm run dev
```

---

## Environment Variables

Create a `.env` file inside the Backend folder:

```env
TWILIO_ACCOUNT_SID=your_account_sid
TWILIO_AUTH_TOKEN=your_auth_token
TWILIO_PHONE_NUMBER=your_phone_number
JWT_SECRET=your_jwt_secret
MONGODB_URI=your_mongodb_connection_string
```

---



## Future Enhancements

* Email notifications
* Attendance analytics dashboard
* QR-code attendance system
* Mobile application support
* Export reports to PDF and Excel

---

## Author

**Mohammed Zakwan**

GitHub: https://github.com/Zakwan-1302

---

## License

This project is developed for educational and portfolio purposes.
