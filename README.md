# 🚚 FretNow — Freight Transportation Platform

**Connecting Customers, Transport Professionals, and Logistics Operations.**

🌐 **Live Website:** [https://fretnow.com](https://fretnow.com)

## 📌 Project Overview

FretNow is a web-based freight transportation platform designed to simplify logistics operations and facilitate connections between users involved in goods transportation.

The platform aims to digitalize key transportation workflows by bringing user management, shipment-related operations, communication, and tracking capabilities together in one application.

FretNow was developed as a full-stack web application, with a modern frontend, a backend API, database integration, and services supporting real-time communication and location-based features.

The application is hosted online and can be accessed through the live website.

## 🌐 Live Demo

**Explore the platform:** [https://fretnow.com](https://fretnow.com)

Visit the website to discover the application's interface and explore the features available in the deployed version.

## ✨ Main Features

### 👥 User Management and Authentication
- User account management.
- Authentication and access control.
- Password hashing for improved credential security.
- Token-based authentication using JSON Web Tokens (JWT).

### 🚛 Freight and Transportation Management
- A digital interface for transportation-related operations.
- Shipment and transport information management.
- Support for organizing and monitoring freight-related workflows.

### 💬 Real-Time Communication
- Real-time communication capabilities powered by Socket.IO.
- Support for exchanging information during transportation workflows.

### 📍 Location and Mapping
- Integration with mapping services to support location-related functionality.
- Location visualization and transportation-related geographic information.

### 📦 File and Media Management
- Cloud-based media storage integration using Cloudinary.
- Support for managing application media and uploaded assets.

### 🖥️ Web Application
- Modern, component-based frontend.
- Backend API for application logic and data operations.
- Database-backed data management.
- Deployment for online access.

*The availability of each feature depends on the current deployed version of the platform.*

## ⚙️ Technical Architecture

FretNow follows a full-stack architecture that separates the user interface, server-side application logic, data persistence, and external services.

```text
                         USERS
                           |
                           v
                  FretNow Web Platform
                     fretnow.com
                           |
                           v
                 Frontend Application
                    React + Vite
                           |
                           v
                    Backend API
                   Node.js + Express
                           |
             +-------------+-------------+
             |             |             |
             v             v             v
          MySQL         Socket.IO     JWT / bcrypt
        Database      Real-Time       Authentication
                      Communication
             |
             v
       Persistent Data

          External Services
             |         |
             v         v
        Cloudinary   Mapping Services
        Media Storage  Location Features
```

This diagram represents the main architectural components and their relationships. Exact deployment details and individual integrations may vary with the production configuration.

## 🛠️ Technology Stack

| Component | Technologies |
|---|---|
| Frontend | React.js, Vite |
| Backend | Node.js, Express.js |
| Database | MySQL |
| Real-time communication | Socket.IO |
| Authentication | JWT, bcrypt |
| Media storage | Cloudinary |
| Mapping | Mapping services and APIs |
| Development and version control | Git, GitHub |
| Hosting | Live deployment at fretnow.com |

## 🔄 How It Works

The application's general architecture follows this workflow:

1. **Access the platform:** Users visit the FretNow website through their browser.
2. **Interact with the interface:** The React frontend displays the available pages and user-facing functionality.
3. **Send application requests:** The frontend communicates with the backend through API requests.
4. **Process business logic:** The Express backend handles requests and coordinates application operations.
5. **Manage data:** The backend interacts with MySQL to store and retrieve application information.
6. **Support real-time interactions:** Socket.IO enables real-time communication where integrated.
7. **Use external services:** Cloudinary and mapping services provide media storage and location-related capabilities.

## 🔐 Security Considerations

Security is an important part of the application's architecture.

The technology stack includes:

- Password hashing with bcrypt.
- JWT-based authentication.
- Server-side request processing.
- Database-backed application data.
- External service integrations.

Production security also depends on secure environment configuration, appropriate authorization checks, input validation, HTTPS, and protection of API credentials.

No passwords, API keys, database credentials, or other private configuration values are published in this project presentation.

## ☁️ Deployment

FretNow is deployed and accessible online.

**Production URL:** [https://fretnow.com](https://fretnow.com)

This repository is intended to document and showcase the project rather than distribute its source code. The production application is accessible through the website, while private implementation details and configuration are kept separate.

## 🎯 Project Objectives

FretNow explores how modern web technologies can support digital freight transportation workflows.

The main objectives are to:

- Simplify transportation-related operations.
- Provide a centralized web interface.
- Structure application data through a backend and database.
- Support communication between users.
- Integrate location and mapping capabilities.
- Build a maintainable full-stack application.
- Deploy a web platform that users can access online.

## 👨‍💻 Developer

**Abdelilah Lagribi**

Engineering student specializing in Artificial Intelligence and Data Science at ENSAM Rabat, Morocco.

My interests include full-stack development, software engineering, data-driven applications, and integrating modern technologies into practical projects.

📧 **Contact:** [lagribiabdelilah@gmail.com](mailto:lagribiabdelilah@gmail.com)

🌐 **Live Project:** [https://fretnow.com](https://fretnow.com)

For more information about the platform, its architecture, or potential collaboration opportunities, please contact me by email.

## 📄 License

This repository serves as a project presentation. No license for source-code reuse or redistribution is granted by this README. Please contact the author for permissions or collaboration inquiries.

---

**FretNow — Digitalizing Freight Transportation Through Technology.**
