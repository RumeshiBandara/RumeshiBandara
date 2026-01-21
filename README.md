<div align="center">

<h1>👋 Hi, I'm Rumeshi Bandara</h1>
<h3>Aspiring Software Engineer | Full Stack Developer from Colombo 🇱🇰</h3>

<p>Passionate about crafting scalable backend systems 🚀, intuitive modern web apps ✨, and tackling concurrency challenges in high-traffic environments like event booking. Currently diving deep into Spring Boot microservices, optimistic locking for concurrency, and MySQL/PostgreSQL optimization. Open to internships & junior roles!</p>

[![Profile Views](https://komarev.com/ghpvc/?username=rumeshibandara&label=Profile%20Views&color=0e75b6&style=flat)](https://github.com/rumeshibandara)

</div>

---

### 🏆 Featured Projects Spotlight

#### 🎟️ **TicketMaster** - High-Concurrency Event Booking System
[![GitHub Repo Stars](https://img.shields.io/github/stars/rumeshibandara/TicketMaster?style=social)](https://github.com/rumeshibandara/TicketMaster)
- **Tech Stack**: Spring Boot, JPA/Hibernate, MySQL, Concurrency Controls (Optimistic Locking), REST APIs, Postman Testing
- **Key Features**:
  - Seat holding with 10-min expiry & auto-release
  - Atomic booking: Hold → Book (prevents double-booking)
  - Audit logs for all actions (SEAT_HOLD_SUCCESS, LOCKED, etc.)
  - Error handling: 409 for SeatLockedException, version field for optimistic locking
  - Sample Data: 5 seats/events mix (AVAILABLE/HELD/SOLD), audit_logs table
- **Live Demo**: [Postman Collection](https://documenter.getpostman.com/view/... ) | Hold Seat: `POST /api/seats/{id}/hold` | Book: `POST /api/bookings`
- **Challenges Solved**: Fixed MySQL 'version' field error → Added `version=0` in INSERTs. No 'seat_id' in audit_logs → Use `action_details` JSON.
- **Repo**: [github.com/rumeshibandara/TicketMaster](https://github.com/rumeshibandara/TicketMaster)

#### 🎓 **Student Management System**
- Java Swing GUI + File I/O for CRUD ops
- Features: Search, Export CSV, Role-based access

#### 🛒 **E-Commerce Full Stack Apps**
- React/Next.js Frontend + Node/Express Backend + MongoDB
- Auth (JWT), Payments (Stripe sim), Real-time updates (Socket.io)

> *More in [Repositories](https://github.com/rumeshibandara?tab=repositories)*

---

### 🚀 About Me
