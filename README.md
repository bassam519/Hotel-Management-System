# 🏨 Hotel Management System

A desktop-based Hotel Management System developed using **Python** and **Tkinter GUI** 🖥️.  
This project is built using **Object-Oriented Programming (OOP)** concepts and uses **file handling** for data storage.

It helps manage hotel operations such as room management, guest registration, and reservations.

---

## ✨ Features

- 🛏️ Add, update, and manage rooms  
- 👤 Register and manage guests  
- 📅 Create and manage reservations  
- 🔍 Check room availability  
- 💾 Store data using text files  
- 🪟 Simple and user-friendly GUI using Tkinter  
- 🧱 Fully implemented using OOP principles  

---

## 🛠️ Tech Stack

- Python 🐍  
- Tkinter 🪟  
- Object-Oriented Programming (OOP) 🧱  
- File Handling 📁  

---

## 📂 Project Structure

Hotel Management System  
│  
├── Rooms.txt  
├── Guests.txt  
├── Reservations.txt  
└── main.py  

---

## 🧩 System Design (Classes)

### 🛏️ Room Class
Handles room-related data:
- Room ID 🆔  
- Room type (Single, Double, Suite, etc.) 🏷️  
- Price per night 💰  
- Availability status ✅  

---

### 👤 Person Class
Base class for all people in the system:
- ID 🆔  
- Name 📝  

---

### 🧍 Guest Class
Inherits from Person:
- Phone number 📱  
- Email address 📧  

---

### 📅 Reservation Class
Handles booking operations:
- Guest details 👤  
- Room details 🛏️  
- Check-in date 🕒  
- Check-out date 🕒  

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/bassam519/Hotel-Management-System.git
