# Airbnb Clone Backend – Features and Functionalities

This directory contains a visual overview of the key backend features and functionalities required for the Airbnb Clone project. The diagram was created using Draw.io and outlines the major components of the system, including user authentication, property management, booking workflows, and payment integration.

---

## 📁 Contents

- `features-overview.png`: Exported PNG diagram of backend features
- *(Optional)* `features-overview.drawio`: Editable source file for future updates

---

## 🧩 Core Backend Features

### 1. User Authentication
- User registration and login
- Password encryption and reset
- Role-based access (Guest, Host, Admin)

### 2. Property Management
- Create, update, and delete property listings
- Upload property images
- Set availability and pricing
- Host dashboard for managing listings

### 3. Booking System
- Search available properties by date and location
- Create, modify, and cancel bookings
- Calculate total price based on duration and nightly rate
- Track booking status (Pending, Confirmed, Cancelled)

### 4. Payment Integration
- Initiate and confirm payments
- Support for multiple payment methods (e.g., M-Pesa, Credit Card)
- Track payment status (Paid, Pending, Failed)
- Link payments to bookings

### 5. Review System
- Submit ratings and comments for completed stays
- View aggregated property ratings
- Enforce review eligibility based on booking history

### 6. Admin Controls
- Moderate listings and user accounts
- View system metrics and audit logs
- Enforce platform policies

---

## 🛠️ How to Update the Diagram

1. Open `features-overview.drawio` in [Draw.io](https://app.diagrams.net/)
2. Make edits to reflect new features or changes
3. Export as PNG:
   - File → Export → PNG
   - Use transparent background and 2x scale for clarity
4. Replace `features-overview.png` in this directory
5. Commit and push changes:
   ```bash
   git add features-and-functionalities/features-overview.png
   git commit -m "Update backend features diagram"
   git push origin main
