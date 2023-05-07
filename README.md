Download Link: https://assignmentchef.com/product/solved-pattern-maker-with-methods
<br>
<p class="ui header product-top-header" title="Pattern Maker With Methods Solution">1.    Write a complete Java program called “PatternMakerWithMethods” (without the quotation marks) according to the following guidelines.

Note:  Your program must use methods to accept the user input and to generate the program output. Your main method should consist mostly of just a few method calls and any needed variable declarations or assignments.

The program prompts the user for five input values:

1.    an integer value between 1 and 10 (inclusive) for the number of rows to be printed

2.    a second integer value between 1 and 10 (inclusive) for the number of columns to be printed

3.    a String value for the starting string of the pattern

4.    a String value for the second string of the pattern, and

5.    a String value that separates the first two strings.

The program must use nested for loops to print a rectangular array of alternating first and second strings of the pattern, separated by the separator string and such that the first string in the first row uses the “first string” provided by the user, but each subsequent row alternates the starting string between the “second string” the user provided and the “first string” the user provided.

So, for instance, if the user enters 5 for the number of rows, 7 for the number of columns, and “XX” for the first string, “OO” for the second string, and “***” for the separator, your program should print the following rectangular pattern.

2.    Write a complete Java program called ECommerceApp whose main method follows the pseudocode below, and whose other methods are as specified below.

Print the banner message

Get the products catalog String

Get the product order from the user and check it exists in the products catalog String

If the product exists

Get the product price

Compute the product tax

Compute the total sale

Output the total sale

Else

Output “The product not found.”

Your program must include the following methods:

1.    A method called bannerPrinter that takes no parameter and has no return value. bannerPrinter outputs a greeting to the command line as shown below.

2.  ******************************************

3.  ====== Welcome to my eCommerce app! ======

4.  ******************************************

5.  (print a blank line after the banner)

6.    A method called productsBuilder that takes no parameters and returns a String. In the method body construct a String (name it productsCatalog) and populate it with items, each of which must be 10 characters long. For any product less than 10 characters, pad the remainder with spaces. You don’t need to get the values from the user, just populate the String with 3 product names. For example, product 1 might be “Desk “, product 2 might be “Table “, and product 3 might be “Pen “. All 3 of these products are within the productsCatalog String.

7.    A method called getOrder that takes a String as a parameter (the productsCatalog String) and returns a boolean. In the method body, prompt the user to enter a product name (a String), then check whether the product name exists in productsCatalog. If it exists, return true, otherwise return false.

8.    A method called getPrice that returns a double. In the method body generate a random number between 1 and 100 (Hint: Use Math.random() multiplied by a scaling factor.) and return this value as the price.

9.    A method called getTax that takes a double as a parameter (the price) and returns a double. Compute the return value as 10% of the parameter value (i.e. 10% of the price). This is the tax.

10.  A method called getTotal that takes two doubles as parameters (the price and the tax) and returns a double. The return value is computed as the sum of the two parameters (the return value is the sale total).

11.  A method called printTotal that takes a double as a parameter (the sale total) and has no return value. This method outputs the following to the command line: “Your sale total is: $X” where X is the sale total parameter value.

All currency amounts that your program outputs should show a leading “$” followed by the whole number, a decimal, and two decimal positions.