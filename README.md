# 🏨 Hotel Reservation System

Welcome to the **Hotel Reservation System** – a Java-based console application designed to streamline the process of managing hotel bookings. Whether you're running a small inn or a boutique hotel, this system simplifies reservation handling, improves guest management, and keeps operations organized.

---

## 🌟 Features

- **Reserve a Room:** Easily make new reservations by entering guest details, room number, and contact information.
- **View Reservations:** Quickly review all active bookings, including guest names, room numbers, contact info, and dates.
- **Edit Reservations:** Modify existing reservations to update guest name, contact, or room assignment.
- **Delete Reservations:** Cancel bookings that are no longer required.

---

## 🚀 Getting Started

### ✅ Prerequisites

- Java Development Kit (JDK)
- MySQL Database
- MySQL Connector/J (JDBC driver)

### ⚙️ Setup

1. **Clone the repository:**

   ```bash
   git clone https://github.com/SriHarsha1405/Hotel-Reservation-System.git
   cd Hotel-Reservation-System

2. **Configure your MySQL credentials in HotelReservationSystem.java:**

- private static final String DB_URL = "jdbc:mysql://localhost:3306/hotel_db";
- private static final String DB_USER = "your_username";
- private static final String DB_PASSWORD = "your_password";

3. **Compile and run the application:**

- javac HotelReservationSystem.java
- java HotelReservationSystem
- Follow the menu-driven interface to navigate through reservation features.

## 📋 Usage
Once the application is running, a menu will appear allowing you to:

Add a new reservation

View all reservations

Edit a reservation

Delete a reservation

Exit the program

Each option guides you through the required inputs step-by-step.
