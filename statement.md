# Smart Restaurant Ordering System

## 1. Project Title
Smart Restaurant Ordering System

## 2. Introduction
The Smart Restaurant Ordering System is a Python-based menu-driven application designed to simplify the process of placing food orders in a restaurant. The system allows customers to view the available food items, choose the products they want, enter the quantity, and receive a final bill with the subtotal, GST, and the total amount payable.

This project demonstrates the use of Python programming concepts such as dictionaries, lists, loops, conditional statements, input validation, and functions. It is a beginner-friendly project that shows how a restaurant ordering system can be implemented in a simple and efficient way.

## 3. Problem Statement
In a restaurant, customers often need to place orders manually by speaking with a waiter or cashier. This process may be slow, error-prone, and time-consuming, especially when customers want to order multiple items with varying quantities. A digital ordering system can make this process more efficient by allowing users to browse the menu and generate their bill automatically.

The main problem addressed by this project is to create a simple system where customers can:
- view the available menu,
- select food items,
- specify the quantity,
- avoid invalid input,
- and receive the final bill automatically.

## 4. Objectives
The main objectives of this project are:
- To create a user-friendly restaurant ordering system.
- To display menu items with their prices.
- To allow the user to add multiple items to the cart.
- To validate invalid menu choices and incorrect quantities.
- To calculate the subtotal and GST automatically.
- To generate the final bill for the customer.
- To provide a simple and interactive command-line interface.

## 5. Scope of the Project
This project includes the following features:
- Displaying a menu with item names and prices.
- Allowing users to choose items by number.
- Adding food items to the order list with quantity.
- Preventing invalid entries and negative or zero quantities.
- Calculating the order total before tax.
- Applying a 5% GST on the subtotal.
- Displaying the final grand total.

The project is designed for a small restaurant and is not connected to a database or online payment system. It is a console-based application focused on order entry and bill generation.

## 6. Features of the System
### Menu Display
The program displays a list of restaurant items and their prices, including:
- Burger - ₹250.00
- Pizza - ₹350.00
- Pasta - ₹180.00
- French Fries - ₹150.00
- Soda - ₹70.00

### Order Selection
The user can choose any item from the menu by entering the corresponding item number. The system checks whether the entered choice is valid and allows the user to continue ordering until they finish.

### Quantity Handling
For each selected item, the user enters the quantity. The application only accepts quantity values greater than zero. If the user enters a zero or negative value, an error message is shown.

### Cart Creation
Each valid order is stored in a cart as an item dictionary containing:
- item name,
- price,
- quantity,
- subtotal.

### Bill Generation
At the end of ordering, the system calculates:
- subtotal of all items,
- GST at 5%,
- grand total.

It then prints the final bill and a thank-you message.

## 7. Technologies Used
- Python
- VS Code or any Python-supported editor
- Command Prompt / PowerShell / Terminal

## 8. System Workflow
The system works in the following sequence:
1. The program starts and displays a welcome message.
2. The menu is shown to the user.
3. The user enters the item number to select an item.
4. The user provides the quantity.
5. The item is added to the cart.
6. The process repeats until the user enters 0 to stop ordering.
7. The program calculates the bill.
8. The subtotal, GST, and grand total are displayed.
9. The program ends with a thank-you message.

## 9. Input and Output
### Input
- Menu item number
- Quantity of each selected item

### Output
- Selected items in the order
- Subtotal
- GST amount
- Grand total
- Final checkout message

## 10. Sample Example
Suppose a customer orders:
- Burger x 2
- Pasta x 1

The program will calculate the total as follows:
- Burger: 2 × ₹250 = ₹500
- Pasta: 1 × ₹180 = ₹180
- Subtotal = ₹680
- GST = 5% of ₹680 = ₹34
- Grand Total = ₹714

The final bill will show all these values clearly.

## 11. Advantages
- Very easy to understand and implement.
- User-friendly command-line interface.
- Quick and simple order processing.
- Helps reduce manual calculation errors.
- Suitable for beginners learning Python.

## 12. Limitations
- The project does not use a database.
- It cannot store order history.
- It does not support online payment or card processing.
- It is not designed for multi-user access.
- It is a console-based application and not a graphical interface.

## 13. Future Scope
The system can be improved in the future by adding:
- a login system,
- customer management,
- database storage,
- discount and coupon support,
- online payment integration,
- admin panel,
- GUI using Tkinter,
- and order tracking features.

## 14. Conclusion
The Smart Restaurant Ordering System is a practical and educational Python project that demonstrates how a restaurant billing system can be built using basic programming concepts. It provides a clean and efficient way to display the menu, take customer orders, validate input, and generate a final bill with GST. The project is simple, effective, and serves as a good starting point for building larger restaurant management systems in the future.
