
---

# Supermarket Billing System

A C++ console-based application to streamline and manage billing operations in a supermarket environment. This system allows users to add items to a bill with details like item name, rate, and quantity, and then generates an organized invoice. With file-based inventory updates, the application ensures real-time stock management and efficient customer billing.

## Table of Contents
- [Features](#features)
- [Project Structure](#project-structure)
- [Installation and Setup](#installation-and-setup)
- [Usage](#usage)
- [Technologies Used](#technologies-used)

---

## Features
- **Add Items to Inventory**: Input item details including name, rate, and quantity, stored in a file-based inventory.
- **Generate Bills**: Calculate the total bill based on items and quantities selected.
- **Inventory Management**: Automatically adjusts item quantities in the inventory file to track stock.
- **User-Friendly Console Interface**: Clear prompts guide users through billing, item selection, and inventory updates.
- **Error Handling**: Handles missing files, out-of-stock items, and invalid inputs for a smoother experience.

## Project Structure
- `Bill` class: Manages item properties like name, rate, and quantity.
- `addItem` function: Adds items to the inventory and writes them to a file.
- `printBill` function: Allows item selection, calculates total bill, and adjusts inventory quantities.
- Main program loop: Provides the main menu and handles user navigation between adding items, printing bills, and exiting.

## Installation and Setup
1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/supermarket-billing-system.git
   cd supermarket-billing-system
   ```
2. **Compile the Program**
   - Use a C++ compiler, such as `g++`:
   ```bash
   g++ supermarket_billing_system.cpp -o billing_system
   ```
3. **Run the Application**
   ```bash
   ./billing_system
   ```

> **Note:** This program uses `windows.h` for certain functions (like `Sleep`), which may need modification or alternative methods for cross-platform compatibility.

## Usage
1. **Main Menu**: Choose from options to add items, print a bill, or exit the program.
2. **Adding Items**: Enter item details to add items to the inventory file (`Bill.txt`).
3. **Printing a Bill**: Enter item names and quantities to calculate the total bill, with real-time stock updates in the file.

### Example Interaction
```
Welcome to Supermarket Billing System
**************************************
    1. Add Item
    2. Print Bill
    3. Exit
```

## Technologies Used
- **C++**: Core programming language for implementing classes, functions, and file operations.
- **File Handling**: Inventory management and billing records are handled with basic file I/O operations.

---
