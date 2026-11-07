# ⚡ RapiVolt – On-Demand EV Charging Platform

**Making EV Charging Accessible, Convenient, and Connected.**

## 📄 Project Documentation

([View RapiVolt Project Documentation (PDF)](docs/RapiVolt_Project_Documentation.pdf))

## 📌 About the Project

RapiVolt is an On-Demand EV Charging Platform designed to connect Electric Vehicle (EV) drivers with nearby registered homeowners and professional charging providers.

The platform enables drivers to discover nearby charging facilities, check charger compatibility, compare pricing and availability, and request charging bookings.

Charging providers can register their facilities, manage charger information and availability, and accept or reject booking requests.

RapiVolt aims to make EV charging more accessible, convenient, and efficient through a **mobile-first experience** supported by web and Android applications.

## 🎯 Project Objectives

- Simplify the process of finding nearby EV charging facilities.
- Connect EV drivers with verified charging providers.
- Provide transparent charging prices and availability.
- Enable a smooth booking and confirmation process.
- Ensure a convenient and responsive experience across devices.
- Support secure interactions between drivers and providers.

## ✨ Key Features

### 🚗 Driver Module
- Driver registration and profile management.
- EV vehicle registration and management.
- Discover nearby charging providers.
- View charging facility details, prices, and availability.
- Check vehicle and charger compatibility.
- Initiate charging booking requests.

### 🔌 Provider Module
- Provider registration and profile management.
- Charging facility registration.
- Manage charger specifications and connector types.
- Update operating hours, pricing, and availability.
- Manage incoming booking requests.

### 📅 Booking Module
- Select available charging slots.
- Submit booking requests.
- Accept or reject booking requests.
- Booking confirmation and status management.
- Maintain booking status records.

### 🔐 Authentication & User Management
- User registration and login.
- Role-based access for drivers and providers.
- User profile management.
- Secure access to platform resources.

## 🛠️ Technology Stack

| Component | Technology |
|---|---|
| Web Application | React.js |
| Web Language | TypeScript |
| Android Application | React Native |
| Mobile Language | TypeScript |
| Backend | Java Spring Boot |
| Database | MySQL |
| ORM / Data Access | Spring Data JPA |
| API Development | Spring Web |
| Security | Spring Security |
| Validation | Spring Validation |
| Build Tool | Maven |
| IDE | Visual Studio Code |
| Version Control | Git & GitHub |

## 📱 Platform Approach

RapiVolt follows a **Mobile-First Development Approach**.

- Android application developed using React Native and TypeScript.
- Web application developed using React and TypeScript.
- Responsive interfaces designed for different screen sizes.
- A common backend built with Spring Boot to support application functionality.
- MySQL used for centralized data management.

## 🏗️ Project Architecture

The platform follows a modular architecture consisting of:

1. **Frontend:** Web and Android interfaces.
2. **Backend:** Spring Boot application handling business logic and REST APIs.
3. **Database:** MySQL for storing application data.
4. **Integration:** Frontend applications communicate with backend services through APIs.

## ⚙️ How It Works

1. The driver registers and logs into RapiVolt.
2. The driver adds their electric vehicle details.
3. The driver searches for nearby charging providers.
4. Available facilities, charging prices, and compatibility details are displayed.
5. The driver selects a suitable facility and requests a booking.
6. The provider accepts or rejects the request.
7. Once accepted, the booking is confirmed.
8. Relevant booking details become accessible according to the platform's privacy rules.

## 🔮 Future Scope

- Real-time GPS location tracking.
- Google Maps integration.
- Online payment gateway integration.
- Live charging session monitoring.
- Detailed booking and transaction history.
- User ratings and reviews.
- Smart charging recommendations.
- Advanced notifications and alerts.

## 📂 Project Structure

```text
RapiVolt/
│
├── backend/          # Java Spring Boot backend
├── database/         # Database-related resources
├── web/              # React + TypeScript web application
├── mobile/           # React Native + TypeScript application
├── docs/             # Project documentation
├── documentation/    # Additional documentation
│
├── README.md
└── .gitignore
```

## 🚀 Development Status

**Status:** Under Development

RapiVolt is being developed collaboratively with separate modules for authentication, driver management, provider management, and booking functionality.

## 👥 Team Contributions

The project is developed collaboratively, with responsibilities distributed across different modules to support modular development and integration.

---

**RapiVolt – Powering Convenient EV Charging.**