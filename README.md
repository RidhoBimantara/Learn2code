# Phyton Project
In This project i attempted to create a self-service programme for a supermarket

# Background
This project aims to create a self-service application that allows customers to make purchases at a supermarket in an efficient and self-reliant manner. The main goal is to provide a convenient shopping experience and assist customers in managing their transactions.

# Requirements and Objectives
Requirements:

1. Python 3.x
2. PEP8 compliant code
3. Docstring documentation
4. Exception handling
5. Use of Python libraries such as Numpy if needed
  
Objectives:

1. Create a self-service checkout system that allows customers to:
2. Add items to the transaction
3. Update items in the transaction
4. Remove items from the transaction
5. Calculate the total purchase amount
6. Provide discounts based on the total purchase amount
  
# Code Flow Explanation or Flowchart
The code flow is explained as follows:

1. Customers create a transaction by creating an object from the Transaction class.
2. Customers add items to the transaction using the add_item method.
3. Customers can update item names, quantities, or prices using the update_item_name, update_item_qty, and update_item_price methods.
4. If customers want to remove items, they can use the delete_item method.
5. Customers can check the transaction using the check_order method.
6. The total purchase amount is calculated using the calculate_total_price method, and a discount is applied if applicable.
7. Customers can complete the transaction and get the final total.

# Explanation of Functions and Attributes Created

- Transaction: A class for managing transactions.
- add_item(item_name, quantity, price_per_item): Adds an item to the transaction.
- update_item_name(old_name, new_name): Updates the item name in the transaction.
- update_item_qty(item_name, new_quantity): Updates the item quantity in the transaction.
- update_item_price(item_name, new_price): Updates the item price in the transaction.
- delete_item(item_name): Deletes an item from the transaction.
- reset_transaction(): Deletes all items from the transaction.
- check_order(): Checks for input errors in the transaction.
- calculate_total_price(): Calculates the total purchase amount with or without a discount.

# Code Demonstrations with Test Cases

  # Scenario 1:
Customer will add items using add_item()

Item name: Fried Chicken, Qty: 2, Price: 20000
Item name: Toothpaste, Qty: 3, Price: 15000
Output:

Transaksi:
Item: Fried Chicken
Qty: 2
Price: 20000

Item: Toothpaste
Qty: 3
Price: 15000

Total Belanja Sebelum Diskon: 85000
Total Belanja Setelah Diskon: 85000
Anda tidak mendapatkan diskon.

  # Scenario 2:
Customer realizes a mistake and wants to remove the item "Toothpaste" using delete_item().

Output:

Transaksi sebelum penghapusan:
Item: Fried Chicken
Qty: 2
Price: 20000

Item: Toothpaste
Qty: 3
Price: 15000

Transaksi setelah penghapusan:
Item: Fried Chicken
Qty: 2
Price: 20000

  # Scenario 3:
Customer realizes a mistake and wants to remove all items using reset_transaction().

Output:

Transaksi sebelum penghapusan:
Item: Fried Chicken
Qty: 2
Price: 20000

Item: Toothpaste
Qty: 3
Price: 15000

Transaksi setelah penghapusan:

  # Scenario 4:
Customer completes the checkout and wants to know the total purchase amount using calculate_total_price(). The system will also display all items purchased, the total before the discount, the final total, and a message to the customer.

Output:

Transaksi:
Item: Fried Chicken
Qty: 2
Price: 20000

Item: Toothpaste
Qty: 3
Price: 15000

Total Belanja Sebelum Diskon: 85000
Total Belanja Setelah Diskon: 85000
Anda tidak mendapatkan diskon.

# Conclusion
This project has been an educational journey in creating a self-service supermarket checkout system. Throughout the development process, we've learned the importance of designing clean and modular code, adhering to PEP8 guidelines, and documenting code effectively with docstrings.

As we reflect on this project, we recognize that there are opportunities for further optimization and expansion that i would like to try. Some areas to explore include:

- User Interface Enhancement: Consider adding a graphical user interface (GUI) to make the application more user-friendly and visually appealing. This could include features like item    images and a virtual shopping cart.
- Database Integration: Implement a database to store transaction history, item details, and customer information. This would enable better data management and analytics.
- Payment Integration: Integrate payment processing capabilities to allow customers to complete transactions, including payment methods such as credit cards, digital wallets, and cash.
- Inventory Management: Expand the system to manage inventory levels, update stock counts, and provide alerts for low stock items.
- Security Measures: Implement security features to protect customer data and ensure secure transactions, including encryption and authentication.

By continuously improving and expanding this simple codebase, we can create a more comprehensive and efficient self-service supermarket system that meets the evolving needs of both customers and business owners. The journey of learning and enhancing this project is an exciting endeavor that can lead to valuable insights and skills in software development.
