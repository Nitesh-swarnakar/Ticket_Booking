# 🚆 Train Ticket Booking System

This is a simple console-based Java application for booking train tickets. It supports user registration, login, train search, booking, and cancellation features.

## 🛠 Features

- User Sign Up and Login (with basic authentication)
- Search for trains by source and destination
- Book seats on available trains
- View your bookings
- Cancel your bookings
- Persistent data storage using `localdb.json`

## 📁 Project Structure

ticket-booking/
├── app/
│ └── ticket.booking.App.java # Main application entry point
├── entities/
│ ├── User.java # User model
│ └── Train.java # Train model
├── services/
│ ├── UserService.java # Handles login, signup
│ └── TrainService.java # Handles train search, booking, cancellation
├── util/
│ └── UserServiceUtil.java # Helper utilities
├── data/
│ └── localdb.json # Local storage file (mock database)



## 🚀 How to Run

### Prerequisites

- Java JDK 17 or higher
- IntelliJ IDEA or any Java IDE
- Gradle (if using external dependencies like Jackson)

### Steps

1. Clone the repo:

   ```bash
   git clone https://github.com/yourusername/ticket-booking.git
   cd ticket-booking
