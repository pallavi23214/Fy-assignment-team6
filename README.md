Shop Management System
Feature Set III
The Shop Management System is a simple college project designed to manage customer details, product details, sales, discounts, and final bills.
Features
Customer details
Product details
Sale management
Discount calculation
Final bill generation
Main Functions
1. Customer Details
The system stores customer information such as: - Customer ID - Name - Phone Number - Address
2. Product Details
The system manages product information such as: - Product ID - Product Name - Price - Stock
3. Sale
The user enters the product quantity and the system calculates the sale amount.
Sale Amount = Price × Quantity
4. Discount
The system applies the discount and calculates the discount amount.
Discount Amount = Sale Amount × Discount % ÷ 100
5. Final Bill
The system calculates and displays the final bill.
Final Bill = Sale Amount − Discount Amount
Algorithm
Start
↓
Enter Customer Details
↓
Enter Product Details
↓
Enter Quantity
↓
Calculate Sale Amount
↓
Apply Discount
↓
Calculate Discount Amount
↓
Calculate Final Bill Amount
↓
Display Final Bill
↓
End
Requirements
Hardware Requirements
Computer or laptop
Minimum 4 GB RAM
Minimum 20 GB free storage
Keyboard and mouse
Monitor/display
Printer (optional)
Software Requirements
Windows or Linux operating system
Suitable programming language such as C, C++, Java, or Python
MySQL or SQLite, if a database is used
Code editor or IDE
ER Diagram Entities
Customer
Customer_ID (PK)
Name
Phone
Address
Product
Product_ID (PK)
Product_Name
Price
Stock
Sale
Sale_ID (PK)
Customer_ID (FK)
Product_ID (FK)
Quantity
Sale_Date
Discount
Discount_ID (PK)
Sale_ID (FK)
Discount_Percentage
Discount_Amount
Bill
Bill_ID (PK)
Sale_ID (FK)
Total_Amount
Final_Amount
Bill_Date
Project Objective
The main objective of this project is to reduce manual work in shop management and make sales, discount calculations, and bill generation simple and accurate.
Author
College Project -- Shop Management System 
