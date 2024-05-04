# CoffeeMachine
This project simulates the functionality of a coffee machine. Users can choose from a selection of drinks, make a payment, and receive their chosen beverage. The machine keeps track of resources such as water, milk, and coffee beans, and calculates profits from drink sales.

# Table of Contents
Project Overview
Usage
Functionality

# Project Overview
The Coffee Machine project is implemented in Python and consists of a script that runs the coffee machine simulation. It utilizes a dictionary (MENU) to store information about available drinks, their ingredients, and costs. Additionally, it keeps track of available resources (resources) and calculates profits (profit) from drink sales.

# Usage
To use the coffee machine:

Run the coffee_machine.py script.
Follow the prompts to select a drink, insert coins for payment, and receive your beverage.
You can also check the available resources by typing report or turn off the machine by typing off.

# Functionality
The project includes the following key functions:

is_resource_sufficient(order_ingredients): Checks if there are enough resources to make the selected drink.
process_coins(): Prompts the user to insert coins and calculates the total amount inserted.
is_transaction_successful(money_received, drink_cost): Checks if the payment is sufficient and returns change if applicable.
make_coffee(drink_name, order_ingredients): Prepares the selected drink by deducting the required ingredients from the available resources.
