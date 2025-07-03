# ☕ Coffee Machine Python Project

This is a simple coffee machine simulation written in Python. It mimics the behavior of a real-world coffee vending machine, allowing the user to choose from various drinks while managing resources and handling payments.

## 📁 File Structure

- `main.py`: The main entry point of the program. It handles user interaction.
- `menu.py`: Contains the menu system (`Menu`, `MenuItem` classes).
- `coffee_maker.py`: Models the coffee-making functionality (`CoffeeMaker` class).
- `money_machine.py`: Manages the payment process (`MoneyMachine` class).

## 🧠 Features

- Available drinks: `latte`, `espresso`, `cappuccino`
- Checks if there are enough ingredients to make the drink
- Accepts coins (quarters, dimes, nickels, pennies)
- Verifies payment amount and gives change
- Displays reports for ingredients and profit (`report` command)
- Allows turning off the machine (`off` command)

## ▶️ How to Use

1. Run the `main.py` file.
2. The console will prompt:  
   `What would you like? (latte/espresso/cappuccino/):`
3. Enter your choice or type:
   - `report`: to see the current status of ingredients and money
   - `off`: to turn off the machine
4. If a drink is selected, the machine will prompt you to insert coins.
5. If enough money is provided, the drink will be made and a message will appear:  
   `"Here is your <drink> ☕️. Enjoy!"`

## 💵 Example Payment

How many quarters?: 4
How many dimes?: 0
How many nickles?: 0
How many pennies?: 0


## 🛠 Possible Future Improvements

- Add a graphical user interface (GUI)
- More drink options
- User account management
- Refill ingredients in admin mode

## 📜 Requirements

- Python 3.x
- No external libraries required

## 📇 Author

Nándor Forgó – *nfori.coding@gmail.com*

