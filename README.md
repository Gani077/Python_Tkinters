# Railway Reservation System using Python Tkinter

## 🚆 Overview
The Railway Reservation System is a Python-based project designed to simplify railway ticket booking. It features a user-friendly GUI built with Tkinter and utilizes an SQLite database for efficient data management. This system streamlines the ticket booking process, eliminating the need for long queues at railway counters.

## 🔹 Key Features
- **User Authentication** – Secure login with predefined credentials.
- **Train Search & Booking** – Select source, destination, date, and travel class (1A, 2A, 3A).
- **Automated PNR Generation** – Each booking is assigned a unique PNR number.
- **Instant Ticket Receipt** – View and store booking details.
- **Easy Cancellation** – Cancel a ticket using the PNR number.

## 🔧 Tech Stack
- **Python 3** – Core programming language.
- **SQLite3** – Lightweight database for managing ticket and user data.
- **Tkinter** – GUI framework for building an interactive interface.
- **Random & Time Libraries** – Used for PNR generation and timestamp management.

## 📂 Project Structure
```
Railway-Reservation-System/
│-- log.py                # Main script to run the application
│-- railway.db            # SQLite database 
│-- Train.gif             # Moving train Gif
│-- train.docx            # Documentation of project
└-- README.md             # Project description
```

## 🚀 Installation & Setup
1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd railway_reservation_system
   ```
2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the application**
   ```bash
   python log.py
   ```

## 📝 Usage
1. **Login** using predefined credentials.
2. **Search for trains** based on source, destination, and date.
3. **Book tickets** and receive an automated PNR number.
4. **View and save ticket details** after booking.
5. **Cancel tickets** by entering the PNR number.

## 📜 License
This project is open-source and available under the **MIT License**.

## 🤝 Contributing
Feel free to fork this repository, create a branch, and submit pull requests for improvements!

## 📩 Contact
For any questions or suggestions, feel free to reach out or open an issue!
