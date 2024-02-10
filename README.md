# wine_Shop-coffie_machine-project


Certainly! The provided Python code simulates the functionality of a wine shop. Here's an overview of its main components:

Menu:

The program defines a menu (MENU) with various drinks such as "royal," "old monk," "boom91," "vodka," "desi," and "wine." Each drink has associated ingredients and costs.
Resources:

The initial stock of ingredients is represented by the resources dictionary, containing quantities of "water," "soda," and "drink."
Profit Tracking:

The profit variable keeps track of the earnings from the wine shop.
Classes:

Two classes, Report and Order, are defined to organize and structure the code.
The Report class holds information about the menu, resources, and profit.
The Order class inherits from Report and represents a customer's order.
Order Processing:

The program processes customer orders by checking if there are enough resources (ingredients) to fulfill the order.
If sufficient resources are available, the program calculates the cost of the order, deducts it from the customer's payment, and updates the profit.
Transaction Handling:

The program handles transactions by checking if the customer has inserted enough money for their order.
If the payment is sufficient, it completes the transaction and provides change if needed.
Notes Input:

The program includes an option to input notes (50s, 100s, 200s, 500s) for payment.
User Interaction:

The main program runs in a loop, prompting users to enter their drink orders, specifying quantities, and handling payments.
It also provides options for generating reports and viewing profits
