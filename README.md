Discount Calculator

This Python script calculates the final price of an item after applying a discount. It prompts the user to input the original price and the discount percentage.

Functionality

The script defines a function calculate_discount(price, discount_percent) that:

Takes two arguments: `price`(the original price of the item) and discount_percent (the discount percentage).
Calculates the discounted price only if the discount percentage is 20% or more.
Returns the final price or the original price if the discount is less than 20%.

The script then:

* Prompts the user to enter the original price and discount percentage using input().
* Calls the `calculate_discount()` function to calculate the final price.
* Displays the result to the user, indicating whether a discount was applied.
* Handles potential `ValueError` exceptions if the user enters non-numeric input.

Usage

1.  Run the script:Execute the Python script in your terminal or Python environment.
2.  Enter price:When prompted, enter the original price of the item as a number.
3.  Enter discount:Enter the discount percentage as a number.
4.  View results:The script will display the final price after the discount (if applicable) or the original price.
