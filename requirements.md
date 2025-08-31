# Airbnb Clone Backend – Technical & Functional Requirements

This document outlines the backend requirements for three core features of the Airbnb Clone system: User Authentication, Property Management, and Booking System. Each section includes API endpoints, expected inputs/outputs, validation rules, and performance expectations.

---

## 🔐 1. User Authentication

### ✅ Functional Requirements
- Users can register, log in, and log out.
- Passwords are securely hashed.
- Role-based access control (Guest, Host, Admin).

### 🔧 API Endpoints

#### POST `/api/auth/register`
- **Input**:
  ```json
  {
    "name": "Grace Mukami",
    "email": "grace@example.com",
    "password": "SecurePass123",
    "userType": "Host"
  }
