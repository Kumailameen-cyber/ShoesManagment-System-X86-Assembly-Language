# ShoesManagment-System-X86-Assembly-Language
A simple shoe Management store in x86 Assembly Language
Shoe Store Management System (x86 Assembly)
Overview
This program simulates a simple shoe store management system, written in x86 Assembly language. It allows a user to manage the stock of various types of shoes, track sales, and calculate the total amount due. The program features a password-protected menu where the user can purchase shoes, view statistics on shoe sales, and check the current stock levels.

Features
Password Protection: Users must enter the correct password to access the main menu.
Shoe Purchase: Allows users to buy different types of shoes by specifying the quantity.
Sales Tracking: The program tracks the quantity of shoes sold and updates the stock accordingly.
Stock Management: Displays the current stock of each type of shoe.
Statistics: Displays statistics on the number of shoes sold and the remaining stock.
Total Amount Calculation: Displays the total amount due for all the shoes purchased.
Exit Option: Allows the user to exit the program.
Shoe Types and Prices
Sneakers: Rs. 40
Boots: Rs. 30
Football Shoes: Rs. 20
Cricket Shoes: Rs. 20
Boxing Shoes: Rs. 10
Volleyball Shoes: Rs. 50
Table Tennis Shoes: Rs. 40
Baseball Shoes: Rs. 20
Golf Shoes: Rs. 80
Program Flow
Start Screen: The program begins by prompting the user to enter a password. The default password is abcd.
Main Menu: After logging in, the user can select from the following options:
Press 1 to buy shoes.
Press 2 to view shoe sales and stock statistics.
Press 3 to view the total amount due for all purchases.
Press 4 to exit the program.
Shoe Purchase: Upon selecting to buy shoes, the program displays a list of shoe types with their prices. The user then enters the quantity for the selected shoe type.
Statistics: Displays the number of shoes sold and the remaining stock for each shoe type.
Total Calculation: Displays the total amount due based on the user's purchases.
Exit: Exits the program when the user presses 4.
Instructions for Use
Run the Program: Compile the assembly code using an assembler like TASM (Turbo Assembler) or MASM (Microsoft Macro Assembler).
Enter Password: When prompted, enter the password abcd (or any other set password).
Use the Menu: Choose from the menu options to either buy shoes, view statistics, check the total amount due, or exit.
Track Sales: The program will automatically update the stock and sales based on your choices.
Requirements
Assembler: TASM or MASM (any x86 assembler).
Operating System: DOS or DOS Emulator (e.g., DOSBox for running on modern systems).
Limitations
Static Password: The program uses a static password (abcd). It may be more secure to implement a dynamic password system.
No Error Handling for Insufficient Stock: If the user attempts to purchase more shoes than available in stock, there is no explicit error handling for stock limits.
Limited User Interface: The program uses basic text output and may not be as user-friendly as modern applications.
Known Issues
Incorrect Password: If an incorrect password is entered, the program will exit immediately.
No Validation for Stock Quantity: If more shoes are purchased than available, the program allows the purchase, but it should ideally prevent this and notify the user of insufficient stock.
Future Improvements
Add Stock Validation: Ensure users cannot buy more shoes than are in stock.
Enhanced User Interface: Provide better feedback and navigation for users, especially for invalid inputs.
Dynamic Password Management: Allow users to change or reset the password dynamically.
Persistent Data: Save sales and stock information to a file so that the data can persist between runs.
License
This software is provided for educational purposes only. Feel free to modify and use the code as needed.
