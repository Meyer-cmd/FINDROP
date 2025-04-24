**PROJECT TITTLE**

**FINDROP**
An E-commerce Dropshipping and Financial Management Tool

**OVERVIEW**
Findrop is  simple C language console application designed to combine the convenience of **dropshipping**with efficient **financial management**.
The main aim is to help handle Product inventory,supplier information,customer orders and financial records using a plain text
file for data storage.

**FEATURES**

1. Product Module
   -Add new products with ID,name,price and quantity
   -stored in `products.txt`.
2. Supplier Module
   -Add suppliers with ID,name and contact info.
   -stored in `suppliers.txt`.
3. Order Module
   -Record customer orders with product ID,quantity and date.
   -calculates order total and cost.
   stored in `order.txt`.
4. Finance Module
   -Record income and expenses with amount,date and notes.
   -Calculates total sales,expenses,profit and profit margin.
   -stored in `finance.txt`.


**TECHNOLOGiES USED**

- *Programming Language*: C
- *Platform*: Console-based (Linux/Ubuntu recommended)
- *Data Storage*: File handling using `.txt` files

 **PROJECT STRUCTURE**

Findrop/

-main.c               # Entry point of the program

-product.c/.h         # Handles product-related logic

-finance.c/.h         # Tracks income, expenses, and profits

-supplier.c           # Manage suppliers details

-orders.c/.h          # Manages customer orders

-data/                # Folder where product/order data is stored

-README.md            # Project documentation

Makefile             # (optional) for compiling the project


**HOW TO RUN**

1. Clone the repository:
bash
git clone https://github.com/Meyer-cmd/findrop.git
cd findrop


2. Compile the program:
bash
gcc main.c product.c finance.c  supplier.c orders.c -o findrop


3. Run it:
bash
./findrop

 **SAMPLE OUTPUT**

bash
Welcome to Findrop Management System
1. Add Product
2. Add Supplier
3. Add Order
4. Add Finance Recordoption
Select option

**AUTHORS**

- Project Lead–[Lencer Meyer](http://github.com/Meyer-cmd)
- Product module – [Naomi Wambui](http://github.com/NaomiWambuiN)
- Supplier module –[Mercy Kemunto](http://github.com/Kemmy703)
- Order Module– [Zachariah Iteba](http://github.com/Cs-son)
- finance Module-[Ellen Surleaf](http://github.com/Surleaf)

**LICENSE**

This project is licensed under the MIT License.

**CONTACT**

For questions or suggestions:
- GitHub: [Meyer-cmd](https://github.com/Meyer-cmd)
- Email: meyerlencer@gmail.com
