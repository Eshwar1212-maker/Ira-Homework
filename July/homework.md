## Problem 1

## Problem 9E: Build a Filtered List

You have a list of numbers:

~~~python
numbers = [3, 7, 12, 5, 18, 2, 9, 14]
~~~

Loop through `numbers` and build a **brand new list** called `big_number_messages` that only includes numbers **greater than 6**. Each item in the new list should be the sentence `"I found a big number: 12!"` (using the actual number).

Print the new list at the end.

**Expected output:**
~~~
['I found a big number: 7!', 'I found a big number: 12!', 'I found a big number: 18!', 'I found a big number: 9!', 'I found a big number: 14!']
~~~

*(Hint: You'll need `.append()` AND an `if` statement inside your loop!)*