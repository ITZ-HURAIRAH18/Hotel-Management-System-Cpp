# 🏨 Hotel Management System in C++

A fully-featured console-based hotel management system built using C++. This project allows managing room bookings, customer check-ins/check-outs, billing (with food menu), and persistent storage using file I/O. It provides a robust solution for small to medium-sized hotels to automate their daily operations.

---

## 🚀 Features

This system offers a wide array of functionalities designed to streamline hotel operations:

* **Login System:** Secure access with masked password input for administrative users.
* **Room Management:**
    * Add new rooms with details like room number, type, and price.
    * Search for available rooms based on various criteria.
    * Track the status of all rooms (occupied, available, reserved).
* **Customer Management:**
    * **Check-in:** Seamless process for new customers, assigning rooms, and capturing guest details.
    * **Check-out:** Efficient check-out procedure, including final bill generation.
* **Billing System:**
    * Automatically calculates room rent based on stay duration.
    * Integrates a comprehensive food ordering system with menu items and prices.
    * Generates a consolidated bill for both room rent and food orders.
* **Guest Summary & Reports:**
    * Provides detailed reports on guest stays.
    * Generates a summary of all guests currently checked into the hotel.
* **Data Persistence:** Utilizes file-based data storage (`fstream`) to ensure all data (rooms, customers, transactions) is saved and loaded across program executions.
* **User Interface Enhancements:**
    * Custom console styling for a more engaging user experience.
    * Text animation effects for a dynamic console interface.

---

## 📂 Sections of the Hotel Managed

The system effectively manages various core aspects of a hotel:

* **Room Management:** Handling the allocation, status, and details of all rooms.
* **Customer Check-in & Check-out:** Streamlining the guest arrival and departure processes.
* **Billing (Room Rent + Food Orders):** Comprehensive financial tracking for services rendered.
* **Guest Summary & Reports:** Providing insights into guest occupancy and activities.
* **File-based Persistent Storage:** Ensuring data integrity and availability.

---

## 🛠️ Technologies Used

This project is developed using the following technologies:

* **C++:** The core programming language used for the entire system logic.
* **File Handling (`fstream`):** For reading from and writing to files, enabling data persistence.
* **Windows API (`windows.h`):** Utilized for console-specific enhancements, such as changing text colors and cursor positioning, to improve the user interface (Note: This makes the console styling Windows-specific).
* **`_getch()` (from `conio.h` on Windows):** Employed for secure input, particularly for masking password entry during login.
* **Text-based UI:** The entire system operates within the console, providing a direct and efficient text-based user interface.

---

## 💡 How to Run

Follow these steps to get the Hotel Management System up and running on your local machine:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YOUR_USERNAME/Hotel-Management-System-Cpp.git](https://github.com/YOUR_USERNAME/Hotel-Management-System-Cpp.git)
    ```
    * **Note:** Replace `YOUR_USERNAME` with your actual GitHub username and `Hotel-Management-System-Cpp` with the correct repository name if it differs.

2.  **Navigate to the project directory:**
    ```bash
    cd Hotel-Management-System-Cpp
    ```

3.  **Compile the source code:**
    Use a C++ compiler like g++ to compile the project. If you have multiple source files, you'll need to compile them all.
    ```bash
    g++ -o hotel_management main.cpp other_file1.cpp other_file2.cpp 
    ```
    * **Note:** Adjust `main.cpp` and `other_fileX.cpp` to match your actual source file names. If all your code is in one file, just `g++ -o hotel_management main.cpp` will suffice.

4.  **Run the executable:**
    ```bash
    ./hotel_management
    ```
    * **On Windows:** You might simply type `hotel_management.exe` or `hotel_management` in the command prompt.

---


1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

---

## 📄 License (Optional)

Distributed under the MIT License. See `LICENSE` for more information.

---

## 📧 Contact (Optional)

Your Name - muhammadabuhurairah558@gmail.com

Project Link: [https://github.com/YOUR_USERNAME/Hotel-Management-System-Cpp](https://github.com/YOUR_USERNAME/Hotel-Management-System-Cpp)
