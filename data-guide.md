# Bookstore Data Guide

We gathered some preliminary data from the bookstore to start analyzing sales. The data is compiled in two CSV files: `sales.csv` and `register.csv`

## Sales

This data provides sales figures (in thousands of dollars) per month, across the different products we sell, including: food, drinks, textbooks, supplies, apparel, accessories, computers and electronics, and finally health, beauty, and fitness products.

## Register

This data provides raw data collected by our new Point Of Sale system that processes purchases made in the store. It includes the following columns:

* **purchase** - a unique number for each check-out, listed chronologically
* **item** - the bar code or product id number for an item being purchased
* **charge** - identifies whether the receipt item is the cost of the item or if it is the affiliated tax on that item
* **price** - associated cost to the customer for the charge
* **is the customer a student/faculty/staff (0) or unaffiliated (1)** - identifies when the customer uses the system with their customer id, which is only available for students, faculty, and staff at the university. Everyone else is treated as unaffiliated
* **customer id** - the ID number of the customer when they enter it at purchase
* **receipt** - records whether or not the customer requests a receipt for their purchase
* **contact preference** - stores the customer's preferred means of contact, including options for: email, mail, fax, and phone
* **newsletter** - stores the customer's preference about whether or not they want to receive the bookstore newsletter
* **sales** - keeps track of whether or not the customer wants notifications about special sales
* **preferred customer discount** - identifies if the customer has qualified for special discounts
