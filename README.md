🧾 **Inventory & Store Billing System (C Language)**

📌 Project Description

The Inventory & Store Billing System is a simple console-based application developed using the C programming language. This project helps manage product inventory and generate bills for purchased items.

The system allows users to:

Add new products to the inventory

View available products

Generate bills by purchasing products

Automatically update product quantity after purchase

This project demonstrates the use of structures, arrays, loops, conditional statements, and basic input/output operations in C.

⚙️** Features**

➕ Add new products with ID, name, price, and quantity

📋 Display all available products in inventory

🧾 Generate bill for selected products

📉 Automatic stock update after purchase

❌ Stock validation (prevents purchase if stock is insufficient)

🔁 Menu-driven program for easy interaction

🛠️ **Technologies Used**

Programming Language: C

Concepts Used:

Structures

Arrays

Loops (while, for)

Conditional statements (if-else)

Standard Input/Output functions (scanf, printf)

**📂 Program Structure**

The program uses a structure called Product to store product information.

struct Product {
    int id;
    char name[30];
    float price;
    int quantity;
};

Each product contains:

Product ID

Product Name

Product Price

Available Quantity

**📋 Menu Options**

When the program runs, the following menu is displayed:

--- INVENTORY & STORE BILLING SYSTEM ---
1. Add Product
2. View Products
3. Generate Bill
4. Exit
   
1️⃣ Add Product

Allows the user to add a new product with details such as:

Product ID

Name

Price

Quantity

2️⃣ View Products

Displays the list of all products stored in the inventory in a table format.

3️⃣ Generate Bill

User enters the product ID and quantity to purchase.

The system checks stock availability.

The total bill amount is calculated.

Inventory quantity is automatically updated.

4️⃣ Exit

Terminates the program.

**▶️ How to Run the Program**

Step 1: Clone the repository
git clone https://github.com/your-username/inventory-billing-system.git

Step 2: Navigate to the project folder
cd inventory-billing-system

Step 3: Compile the program
gcc inventory.c -o inventory

Step 4: Run the program
./inventory

**📸 Example Output**
--- INVENTORY & STORE BILLING SYSTEM ---
1. Add Product
2. View Products
3. Generate Bill
4. Exit
Enter your choice:


**🎯 Learning Objectives**

This project helps beginners understand:

How to use structures in C

Managing data using arrays

Creating menu-driven programs

Performing basic inventory management logic

**🚀 Future Improvements**

Possible enhancements for this project:

File handling to save inventory permanently

Search products by ID or name

Delete or update product details

Add GST/discount in billing

Improve user interface

**👨‍💻 Author**

AMAN KUMAR PRASAD

If you like this project, feel free to ⭐ star the repository!
