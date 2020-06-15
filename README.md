SHOPPING CART PROJECT INSTRUCTIONS:

To run the Shopping Cart Project:

NB: These instrucitons assume you have downloaded this repository from https://github.com/nolin897/shopping-cart

1) Set up a virtual environment called (shopping-env) and run the following command: 

        pip install -r requirements.txt

2) Create a .env file and set your sales tax rate equal to the environment variable     sales_tax

3) Run shopping_cart.py in your virtual environment.

4) To print a receipt enter a product id from 1 to 20 and then enter DONE or done when finished.

<!-- To set up and run the Shopping Cart Project:

1) Create and clone shopping-cart repo with 
    
    1) a Readme.md file
    2) a Python .gitignore file
    3) a .env file with your store's sales tax
    4) a requirements.txt file with the python-dotenv package

2) Create shopping_cart.py file in repo including the following code:

        # shopping_cart.py

        products = [
            {"id":1, "name": "Chocolate Sandwich Cookies", "department": "snacks", "aisle": "cookies cakes", "price": 3.50},
            {"id":2, "name": "All-Seasons Salt", "department": "pantry", "aisle": "spices seasonings", "price": 4.99},
            {"id":3, "name": "Robust Golden Unsweetened Oolong Tea", "department": "beverages", "aisle": "tea", "price": 2.49},
            {"id":4, "name": "Smart Ones Classic Favorites Mini Rigatoni With Vodka Cream Sauce", "department": "frozen", "aisle": "frozen meals", "price": 6.99},
            {"id":5, "name": "Green Chile Anytime Sauce", "department": "pantry", "aisle": "marinades meat preparation", "price": 7.99},
            {"id":6, "name": "Dry Nose Oil", "department": "personal care", "aisle": "cold flu allergy", "price": 21.99},
            {"id":7, "name": "Pure Coconut Water With Orange", "department": "beverages", "aisle": "juice nectars", "price": 3.50},
            {"id":8, "name": "Cut Russet Potatoes Steam N' Mash", "department": "frozen", "aisle": "frozen produce", "price": 4.25},
            {"id":9, "name": "Light Strawberry Blueberry Yogurt", "department": "dairy eggs", "aisle": "yogurt", "price": 6.50},
            {"id":10, "name": "Sparkling Orange Juice & Prickly Pear Beverage", "department": "beverages", "aisle": "water seltzer sparkling water", "price": 2.99},
            {"id":11, "name": "Peach Mango Juice", "department": "beverages", "aisle": "refrigerated", "price": 1.99},
            {"id":12, "name": "Chocolate Fudge Layer Cake", "department": "frozen", "aisle": "frozen dessert", "price": 18.50},
            {"id":13, "name": "Saline Nasal Mist", "department": "personal care", "aisle": "cold flu allergy", "price": 16.00},
            {"id":14, "name": "Fresh Scent Dishwasher Cleaner", "department": "household", "aisle": "dish detergents", "price": 4.99},
            {"id":15, "name": "Overnight Diapers Size 6", "department": "babies", "aisle": "diapers wipes", "price": 25.50},
            {"id":16, "name": "Mint Chocolate Flavored Syrup", "department": "snacks", "aisle": "ice cream toppings", "price": 4.50},
            {"id":17, "name": "Rendered Duck Fat", "department": "meat seafood", "aisle": "poultry counter", "price": 9.99},
            {"id":18, "name": "Pizza for One Suprema Frozen Pizza", "department": "frozen", "aisle": "frozen pizza", "price": 12.50},
            {"id":19, "name": "Gluten Free Quinoa Three Cheese & Mushroom Blend", "department": "dry goods pasta", "aisle": "grains rice dried goods", "price": 3.99},
            {"id":20, "name": "Pomegranate Cranberry & Aloe Vera Enrich Drink", "department": "beverages", "aisle": "juice nectars", "price": 4.25}
        ] # based on data from Instacart: https://www.instacart.com/datasets/grocery-shopping-2017

        def to_usd(my_price):
            """
            Converts a numeric value to usd-formatted string, for printing and display purposes.

            Param: my_price (int or float) like 4000.444444

            Example: to_usd(4000.444444)

            Returns: $4,000.44
            """
            return f"${my_price:,.2f}" #> $12,000.71

        # TODO: write some Python code here to produce the desired output

            print(products)

3) Set up a virtual environment called (shopping-env) and run the following command: pip install -r requirements.txt

4) Run shopping_cart.py in your virtual environment

5) To print a receipt enter a product id from 1 to 20 and the enter DONE when finished.

To create the script shopping_cart.py following the below steps: 

1) Begin by pulling in product Id's using a while loop. The while loop will need
    
    1) an input function
    2) a break when the user enters "DONE" or "done"
    3) a way to append inputs using the .append() method.
    4) A way to validate inputs and provide a message if invalid inputs are entered.

2) Once this is completed, print
    1) The name of the store
    2) The store's url
    3) The checkout date and time in YYYY-MM-DD HH:MM AM/PM format

3) Using a for loop, for each selected id in the empty list of selected ids, pull in the matching product's name and price in USD format.

4) For the totals print
    1) The subtotal pretax
    2) The amount of sales tax owed = 8.75% of the subtotal
    3) The after tax total

5) Print a thank you message at the end of the receipt -->
