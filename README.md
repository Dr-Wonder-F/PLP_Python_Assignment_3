# PLP_Python_Assignment_3
# ASSIGNMENT ON FUNCTIONS 

# Define function
def calculate_discounted_price(price, discount):
    if discount > 100:
        return "Invalid input"
    elif discount < 20:
        return price
    amount_to_pay = price - (price * discount / 100)
    return round(amount_to_pay, 2)  # Round result to 2 decimal places

# Accept user input
price = float(input("Enter price of item selected: "))
discount = float(input("Enter the discounted rate in percentages (%): "))

# Call function and print result
print(calculate_discounted_price(price, discount))

PS G:\My Drive\PLP\Python> & C:/Users/LENOVO/AppData/Local/Programs/Python/Python313/python.exe "g:/My Drive/PLP/Python/assignment#.py"
Enter price of item selected: 20
Enter the discounted rate in percentages (%): 12
20.0
