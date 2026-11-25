# Restaurant Order Management System (PS 35)

A Python 3 console application for a restaurant. The waiter selects a table
(1-20), adds items from the menu, views the running order and generates the
final bill with 10% service charge and 5% GST. The bill is saved to a file.

## Menu
Burger Rs.100 | Pizza Rs.200 | Coffee Rs.50

## Concepts used
Lists, Dictionaries, Loops, Functions, Input validation, File handling

## How to run
    python one.py

## Features
- Menu stored in a dictionary; orders per table stored in a list
- Validation of table number, item name and quantity
- Running order display, final bill (Subtotal, Service charge, GST, Total)
- Final bill saved as bill_table_<n>.txt

## Files
- one.py  - main program
- README.md  - this file
- bill_table_<n>.txt  - generated bills
- Test_cases_passed.pdf  - test case results
