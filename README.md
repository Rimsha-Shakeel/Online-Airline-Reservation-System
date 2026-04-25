# ✈️ Online Airline Reservation System (C Project)

## 📌 Introduction
The **Online Airline Reservation System** is a simple C-based application designed to streamline the process of booking airline tickets. It helps improve customer experience by enabling efficient reservation handling and reducing manual effort.

The system allows users to:
- View available flights  
- Check seat availability  
- Make reservations  
- Handle basic booking errors  

---

## 🎯 Goals
The project aims to:

- Reduce the time and effort required for making reservations  
- Automate manual booking processes  
- Standardize reservation handling  
- Ensure basic data security through structured input handling  

---

## 🛠️ Technologies Used
- **Programming Language:** C  
- **Concepts:** File Handling, Structures, Basic Input/Output Operations  

---

## 💻 System Requirements

### Hardware Requirements
- Processor: Any modern processor (e.g., Intel i3 or equivalent)  
- Memory: Minimum 1 GB RAM  
- Storage: At least 100 MB free disk space  

### Software Requirements
- Operating System: Windows / Linux / macOS  
- Compiler: GCC (GNU Compiler Collection) or any standard C compiler  
- Text Editor: Visual Studio Code, Notepad++, or any preferred editor  

---

## ⚙️ Methodology
The system follows a **menu-driven approach**, allowing users to interact via numeric input.

### Key Features
- **Display Flights:** Shows available flights along with seat availability  
- **Make Reservations:** Allows users to book seats if available  
- **Error Handling:** Prevents overbooking and invalid flight selection  

---

## 🧩 System Design

### Data Structure
The system uses an **array of structures**, where each structure represents a flight with:
- Flight Number (unique identifier)  
- Seats Available  

### Core Operations
- **Display Flights:** Lists all flights with available seats  
- **Book Reservation:** Books seats for a selected flight  
- **Input Validation:** Ensures valid flight numbers and seat limits  

---

## 🚀 Implementation

### Functions Used

- **`displayFlights()`**  
  Displays all flights and their available seats  

- **`makeReservation()`**  
  Handles booking logic and checks seat availability  

- **`main()`**  
  Provides the menu-driven interface for user interaction  

---

## 📈 Conclusion
This project demonstrates a basic yet effective airline reservation system using C. It successfully allows users to:

- View available flights  
- Book seats with validation checks  
- Handle common errors (invalid input, insufficient seats)  

---

## 🔮 Future Enhancements
Potential improvements include:

- Adding user authentication (login system)  
- Developing a graphical user interface (GUI)  
- Integrating a database for persistent data storage  
- Implementing online payment functionality  

## Author

Rimsha Shakeel