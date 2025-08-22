# # Discount Calculator

This is a simple Python program that calculates the final price of an item after applying a discount.  
The discount is only applied if it is **20% or higher**; otherwise, the original price is returned.

## Features
- Function `calculate_discount(price, discount_percent)` handles the discount logic.
- Prompts the user to enter the original price and discount percentage.
- Applies discount only if it is 20% or more.
- Displays either the discounted price or the original price.

## Example
```bash
Enter the original price of the item: 1000
Enter the discount percentage: 25
The final price after 25.0% discount is: 750.00

Enter the original price of the item: 500
Enter the discount percentage: 10
No discount applied. The price remains: 500.00
