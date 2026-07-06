<div align="center">

# 🚗 Campus Ride Connect

### Smart Campus Mobility & Ride Sharing Platform

*A secure Android-based ride-sharing platform designed exclusively for university students, enabling cost-effective, sustainable, and real-time transportation within and around campus.*

![Platform](https://img.shields.io/badge/Platform-Android-green)
![Language](https://img.shields.io/badge/Language-Java-orange)
![Firebase](https://img.shields.io/badge/Backend-Firebase-yellow)
![Google Maps](https://img.shields.io/badge/Maps-Google%20Maps-blue)
![Status](https://img.shields.io/badge/Status-Completed-success)
![License](https://img.shields.io/badge/License-MIT-blue)

</div>

---

# 📖 Overview

Campus Ride Connect is a **smart campus transportation platform** that enables students to securely share rides with fellow students. The application connects drivers who have available seats with passengers looking for affordable transportation within and around the university.

The platform combines **OTP-based authentication, Firebase Realtime Database, Google Maps APIs, and real-time ride synchronization** to deliver a seamless ride-sharing experience while ensuring security, trust, and convenience.

---

# ✨ Features

## 🔐 Secure Authentication

- OTP-based Email Verification
- Passwordless Login Experience
- Firebase Authentication
- Secure Session Management
- College Student Verification
- User Profile Completion

---

## 🚘 Ride Management

### Driver Features

- Create Ride
- Manage Ride Requests
- Accept / Reject Requests
- Ride Completion
- Ride History
- Driver Dashboard

### Passenger Features

- Browse Available Rides
- Search by Destination
- Filter by Time
- Send Ride Requests
- View Ride Status
- Ride History

---

## 🗺 Smart Maps Integration

- Google Maps SDK
- Google Places API
- Current Location Detection
- Interactive Map Picker
- Route Visualization
- Turn-by-Turn Navigation
- Geocoding & Reverse Geocoding

---

## ⚡ Real-Time Synchronization

Using Firebase Realtime Database

- Live Ride Updates
- Instant Request Status
- Real-Time Driver Availability
- Automatic Data Synchronization

---

## 📱 Modern User Interface

- Material Design Components
- Responsive Layout
- Role-Based Navigation
- Interactive Dashboard
- Clean User Experience

---

# 🏗 System Architecture

```
                  Student
                     │
                     ▼
            Android Application
                     │
      ┌──────────────┼──────────────┐
      ▼              ▼              ▼
Authentication   Ride Services   Google Maps
      │              │              │
      └──────────────┼──────────────┘
                     ▼
         Firebase Realtime Database
                     │
                     ▼
          Real-Time Data Synchronization
```

---

# 🚀 Technology Stack

| Category | Technology |
|-----------|------------|
| Language | Java |
| IDE | Android Studio |
| Backend | Firebase |
| Authentication | Firebase Authentication |
| Database | Firebase Realtime Database |
| Maps | Google Maps SDK |
| Places | Google Places API |
| Networking | Retrofit |
| HTTP Client | OkHttp |
| JSON | Gson |
| Email Service | EmailJS API |
| UI | Material Design |
| Architecture | MVC |

---

# 📂 Project Structure

```
Campus-Ride/
│
├── activities/
├── adapters/
├── models/
├── services/
├── utils/
├── firebase/
├── layouts/
├── drawable/
├── navigation/
├── AndroidManifest.xml
├── build.gradle
└── README.md
```

---

# 🔄 Application Workflow

```
User Registration
        │
        ▼
Email OTP Verification
        │
        ▼
Profile Completion
        │
        ▼
Dashboard
   ┌───────────────┐
   │               │
Driver          Passenger
   │               │
Create Ride    Search Ride
   │               │
Accept Request Request Ride
   │               │
Ride Complete  Track Status
        │
        ▼
Ride History
```

---

# 🔒 Security Features

- OTP-based Authentication
- Firebase Authentication
- Email Verification
- Session Management
- Secure HTTPS Communication
- Firebase Security Rules
- Input Validation
- Single-use OTP
- 5-Minute OTP Expiration

---

# 📊 Firebase Database Structure

```
campus-ride
│
├── users
├── rides
├── ride_requests
├── passenger_ride_requests
└── otp_codes
```

---

# 📍 Core Functionalities

### Authentication

- Login
- Registration
- OTP Verification
- Session Handling

### Ride Management

- Create Ride
- Browse Ride
- Ride Requests
- Accept / Reject Requests
- Ride Tracking

### Maps

- Location Picker
- Live Navigation
- Current Location
- Route Display

### User Profile

- Student Details
- Ride Statistics
- Ride History

---

# 📸 Application Screens

- Login Screen
- OTP Verification
- Dashboard
- Post Ride
- Browse Rides
- Driver Dashboard
- Passenger Dashboard
- Ride Details
- Google Maps Navigation
- Ride History

---

# ⚙ Installation

Clone the repository

```bash
git clone https://github.com/somesh2411/Campus-Ride-Smart-Campus-Mobility-Transportation-Management-Platform.git
```

Open using Android Studio

```
Android Studio
→ Open Existing Project
```

Configure Firebase

- Add your `google-services.json`
- Enable Authentication
- Enable Realtime Database

Sync Gradle

```
Build → Sync Project
```

Run the application

```
Run ▶
```

---

# 📈 Future Enhancements

- Digital Payments
- Push Notifications
- Live GPS Tracking
- Driver Ratings
- Passenger Ratings
- AI Route Optimization
- Group Ride Sharing
- Emergency SOS
- Dark Mode
- Biometric Authentication
- Multi-language Support

---

# 👨‍💻 Authors

### Somesh S
Integrated M.Tech Software Engineering  
Vellore Institute of Technology

📧 Email  
someshhemanth2018@gmail.com

🔗 LinkedIn  
https://www.linkedin.com/in/somesh2411/

💻 GitHub  
https://github.com/somesh2411

---

# 🤝 Contributors

- Somesh S
---

# 📄 License

This project is developed for educational and research purposes.

---

<div align="center">

### ⭐ If you found this project useful, consider giving it a Star!

Made with ❤️ using Java, Firebase & Google Maps

</div>
