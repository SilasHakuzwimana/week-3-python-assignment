# Calculate Discount Function

## Description
This project contains a Python function named `calculate_discount` that calculates the final price of an item after applying a discount. The function checks if the discount is 20% or higher. If it is, the discount is applied to the price; otherwise, the original price is returned.

## Features
- Calculates the final price after applying a discount.
- Checks if the discount percentage is 20% or higher before applying it.
- Prompts the user to input the original price and discount percentage.

## Usage
1. Clone the repository or copy the code to your local machine.
2. Run the Python script that includes the `calculate_discount` function.
3. Follow the prompts to enter the original price and the discount percentage.
4. The script will output the final price after applying the discount or indicate that no discount was applied.

## Example
```python
# Example usage of the calculate_discount function

price = float(input("Enter the original price of the item: "))
discount_percent = float(input("Enter the discount percentage: "))

final_price = calculate_discount(price, discount_percent)

if final_price == price:
    print(f"No discount applied. The original price is: ${price:.2f}")
else:
    print(f"The final price after applying the discount is: ${final_price:.2f}")
