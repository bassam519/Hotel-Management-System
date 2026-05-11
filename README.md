# Hotel Management System

A desktop-based Hotel Management System developed using Python and Tkinter GUI.  
The project helps manage hotel rooms, guests, and reservations using Object-Oriented Programming concepts.

---

## Features

- Add and manage rooms
- Register guests
- Create reservations
- Check room availability
- Store data using text files
- Simple GUI using Tkinter
- OOP implementation

---

## Tech Stack

- Python
- Tkinter
- OOP
- File Handling

---

## Project Structure

```text
Hotel Management System
│
├── Rooms.txt
├── Guests.txt
├── Reservations.txt
└── main.py
```

---

## Classes

### Room
Handles:
- Room ID
- Room type
- Price
- Availability

### Person
Base class containing:
- ID
- Name

### Guest
Inherits from Person:
- Phone number
- Email address

### Reservation
Handles:
- Reservation details
- Check-in / Check-out
- Guest booking

---

## Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/Hotel-Management-System-Python.git
```

Go to the project folder:

```bash
cd Hotel-Management-System-Python
```

Run the project:

```bash
python main.py
```

---

## Future Improvements

- Database integration
- Admin login system
- Better UI design
- Search and filter options
- Online reservation support

---

## Author

Bassam
