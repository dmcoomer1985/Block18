<!-- /*

# Directions:

For each prompt below: 

Read the prompt.
Identify the expectations.
Write specifications for all the tests that would be useful for that prompt.
Try to take any "edge cases," or unexpected circumstances, into account, and write test specs for them.
Try not to write extraneous tests!


## UNIT TESTS

1. A function called "multiplication" that returns the product of the two input numbers.
* Expect multiplication(5, 6) to be a number.
* Expect multiplication(5, 6) to be equal to 30. 
* Expect multiplication("5", 6) to be an error.
* Expect multiplication(5, "6") to be an error. 
* Expect multiplication(6, 5) to be equal to 30. 
* Expect multiplication("m", 6) to be an error. 
* Expect multiplication () to be a zero or error.

2. A function called "concatOdds" takes two arrays of integers as arguments. It should return a single array that only contains the odd numbers, in ascending order, from both of the arrays.
* concatOdds([3, 6, 7, 15, 20], [9, 1, 3, 5, 11])
should result in [1, 3, 5, 7, 9, 11, 15].
* Duplicates in the array could result in throwing an error.
* The array being in descending order could result in an error being thrown.
* The array returning [] could result in an error being thrown due to the array expecting odd numbers.
* Adding a string into the array could result in an error being thrown. 




## FUNCTIONAL TEST

1. A shopping cart checkout feature that allows a user to check out as a guest (without an account), or as a logged-in user. They should be allowed to do either, but should be asked if they want to create an account or log in if they check out as a guest.

* When a user clicks on the shopping cart icon it will result in giving the user a choice to check out as a guest or create an account.
* When a user clicks on their shopping cart it should display whether the shopping cart has items in it or if it's empty.
* If the shopping cart is empty it should display a message that says Your shopping cart is empty.
* If the user decides to create an account, the information such as mailing address, and credit card information should be stored securely. 
* If the user tries to create an account without filling in any information, they should be thrown an error.
* When a user clicks create account with an invalid email address or password they should be shown an error.
* When a user attempts to sign into their account there should be either  a success prompt or error due to not putting in a correct email or the right password.
* When a user clicks log-in and password correctly, they should be taken to their dashboard or their shopping cart so they can check out.  -->
