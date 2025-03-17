
# Inventory Management System

## Description
This is a simple **Inventory Management System** implemented in C++ that allows users to add items to an inventory and generate a bill for purchased items. The system interacts with a file (`Bill.txt`) to store and retrieve item details.

## Features
- **Add Items**: Users can add new items to the inventory with item name, rate, and quantity.
- **Generate Bill**: Users can input items they wish to purchase, and the system calculates the total bill based on the available stock.
- **File Storage**: The inventory data is stored in a text file (`Bill.txt`) for persistence.
- **Automatic Stock Update**: When an item is purchased, its quantity is updated in the file.

## File Handling
- Inventory data is stored in `D:/Bill.txt`.
- A temporary file (`Bill Temp.txt`) is used while updating stock information.

## How to Use
1. Run the program.
2. Choose an option from the main menu:
   - `1. Add Item`: Add items to the inventory.
   - `2. Print Bill`: Purchase items and generate a bill.
   - `3. Exit`: Close the program.
3. When adding an item, provide its name, rate, and quantity.
4. When printing a bill, enter the item name and quantity to generate a purchase bill.
5. The program calculates the total bill and displays a thank-you message.

## Requirements
- C++ compiler (e.g., g++ for GCC, MSVC for Windows)
- Windows OS (uses `windows.h` for `Sleep()` function)

## Improvements Needed
- **File Path**: The file path is hardcoded (`D:/Bill.txt`), which may not work on all systems.
- **Better Input Handling**: Currently, input validation is minimal.
- **UI Enhancements**: A more user-friendly interface can be implemented.
- **Cross-Platform Compatibility**: Remove `windows.h` dependency for broader OS support.

## How to Compile and Run
1. Compile using g++ (for GCC):
   ```bash
   g++ inventory.cpp -o inventory
   ```
2. Run the executable:
   ```bash
   ./inventory
   ```

## Author
Developed by Utkarsh.

