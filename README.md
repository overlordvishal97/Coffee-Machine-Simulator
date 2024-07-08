# Coffee Machine Simulator
This is a coffee machine simulator that allows users to interact with a virtual coffee machine. The machine can make different types of coffee drinks, report its resources, and accept payments.

# Classes
CoffeeMaker
The CoffeeMaker class models the coffee machine. It has the following methods:

__init__: Initializes the coffee machine with resources (water, milk, and coffee).
report: Prints a report of the current resources.
refill: Refills all resources to their maximum capacity.
is_resource_sufficient: Checks if the machine has enough resources to make a specific drink.
make_coffee: Deducts the required ingredients from the resources and prints a success message.

# MenuItem
The MenuItem class models each menu item. It has the following attributes:

name: The name of the drink.
cost: The cost of the drink.
ingredients: A dictionary of ingredients required to make the drink.

# Menu
The Menu class models the menu with drinks. It has the following methods:

__init__: Initializes the menu with a list of menu items.
get_items: Returns a string of all available menu items.
find_drink: Searches the menu for a specific drink by name and returns the item if found.

# MoneyMachine
The MoneyMachine class models the money machine. It has the following methods:

__init__: Initializes the money machine with a profit and money received.
report: Prints the current profit.
process_coins: Calculates the total amount of money inserted.
make_payment: Processes the payment and returns True if the payment is accepted, or False if insufficient.

# Usage
To use the coffee machine simulator, simply run the main.py file. You will be prompted to choose an option from the menu. You can choose to make a drink, report the resources, refill the resources, or turn off the machine.

# Note
This is a basic implementation of a coffee machine simulator and can be extended to include more features and functionality.
