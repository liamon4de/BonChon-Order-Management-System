# BonChon-Order-Management-System
Section: Rubidium

Group Members: Amalia Lapira, Michaela Laqui, Andrey Obial

**Project Description**

The BonChon Order Management System designed to streamline the delivery of orders from BonChon. The application will allow customers to browse the restaurant’s menu, modify their orders, and confirm their purchases. Once an order is confirmed, the application calculates the total cost, records the order, and assigns it a delivery rider. Restaurant staff may then provide real-time updates on food preparation. This reduces long lines in the restaurant and brings convenience to those who are unable to order in person. Through this digital platform, customers can easily access BonChon’s delicious dishes in just a few clicks.

**Classes**

**1) Food**

_Attributes:_

name - name of food item

price - price of food item

quantity - quantity of item selected

status - availability (available/unavailable)

_Methods:_

display() - displays the item's information

upd_qty() - updates the quantity of selected item

upd_status() - changes item's availability

**2) Cart**

_Attributes:_

items - list of food items added to the cart

quantity - total quantity of items in the cart

total_price - total cost of all items in the cart

_Methods:_

add_item() - adds a food item to the cart

remove_item() - removes a food item from the cart

upd_qty() - updates the quantity of a selected item

calc_total() - calculates the total price of all items in the cart

display_cart() - displays all items added to the cart

**3) Customer**

_Attributes:_

name - name of the customer

address - customer's delivery address

cart - cart containing the customer's selected food items

_Methods:_

browse_menu() - displays the available food items

add_to_cart() - adds a selected food item to the cart

place_order() - places an order using the items in the cart

confirm_order() - confirms the customer's purchase

**4) DeliveryRider**

_Attributes:_

name - name of the delivery rider

address - delivery address assigned to the rider

food - food items assigned for delivery

status - availability of the rider (available/unavailable)

_Methods:_

receive_order() - receives an order assigned by the restaurant

receive_address() - receives the customer's delivery address

deliver_order() - delivers the food to the customer

upd_status() - updates the rider's availability or delivery status

**5) RestaurantStaff**

_Attributes:_

name - name of the restaurant staff member

assigned_orders - list of orders assigned to the staff member

status - current status of the food preparation

_Methods:_

receive_order() - receives confirmed customer orders

cook_order() - prepares the customer's food order

package_order() - packages the prepared food

upd_status() - updates the preparation status of an order

**Class Diagram**

<img width="581" height="1003" alt="image" src="https://github.com/user-attachments/assets/53594788-6870-4843-ae81-39048645a07d" />

