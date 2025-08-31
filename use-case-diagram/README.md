# Airbnb Clone – Use Case Diagram

This directory contains the use case diagram for the Airbnb Clone backend system. The diagram visualizes how different users interact with the system across key functionalities such as user registration, property booking, and payments.

---

## 📁 Contents

- `use-case.png`: Exported PNG diagram showing system interactions
- *(Optional)* `use-case.drawio`: Editable source file for future updates

---

## 🎭 System Actors

- **Guest**: Registers, searches for properties, books stays, makes payments, and leaves reviews.
- **Host**: Lists and manages properties, views bookings, and responds to reviews.
- **Admin**: Moderates listings and users, oversees platform operations.
- **System**: Handles notifications, validations, and automated processes.

---

## 🧩 Key Use Cases

### For Guests
- Register and log in
- Search for properties
- Book a property
- Make a payment
- Leave a review

### For Hosts
- Register and log in
- Create and manage property listings
- View booking requests
- Respond to reviews

### For Admins
- Manage users and listings
- View system metrics
- Moderate reviews and content

### For System
- Send booking confirmations
- Validate payment status
- Trigger notifications

---

## 🛠️ How to Update the Diagram

1. Open `use-case.drawio` in [Draw.io](https://app.diagrams.net/)
2. Add or modify actors and use cases as needed
3. Export as PNG:
   - File → Export → PNG
   - Use transparent background and 2x scale for clarity
4. Replace `use-case.png` in this directory
5. Commit and push changes:
   ```bash
   git add use-case-diagram/use-case.png
   git commit -m "Update use case diagram for Airbnb Clone backend"
   git push origin main
