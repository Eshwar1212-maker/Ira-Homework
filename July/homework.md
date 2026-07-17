## Homework: Functions, Loops, String Methods & File I/O

---

### Problem 1: Your First Function
Write a function called `greet` that takes a name as a parameter and prints `"Hello, Alice!"` (using the actual name passed in). Call it 3 times with different names.

---

### Problem 2: Function with Return
Write a function called `add_numbers` that takes two numbers as parameters and **returns** their sum. Print the result when you call it.

~~~
add_numbers(3, 5) → should print 8
~~~

---

### Problem 3: Loop Inside a Function
Write a function called `countdown` that takes a number and prints a countdown from that number down to 1.

~~~
countdown(5) → prints 5, 4, 3, 2, 1
~~~

---

### Problem 4: While Loop Menu
Write a simple while loop that keeps asking the user `"Do you want to continue? (yes/no)"` and only stops when they type `no`.

---

### Problem 5: String Methods - Cleanup
Ask the user to type their name. Use `.strip()` to remove extra spaces and `.lower()` to make it all lowercase. Print the cleaned version.

~~~
Input: "  ALicE  " → Output: "alice"
~~~

---

### Problem 6: String Methods - Split
You have this string:
~~~python
sentence = "apples,bananas,mangos,grapes"
~~~
Use `.split(",")` to turn it into a list and print each fruit on its own line.

---

### Problem 7: Function + String Methods Together
Write a function called `make_username` that takes a first name and last name, strips both, lowercases both, and returns them combined with an underscore.

~~~
make_username("  Alice ", " SMITH ") → returns "alice_smith"
~~~

---

### Problem 8: Write to a File
Write a program that asks the user for their favorite food and saves it to a file called `favorites.txt`. Print `"Saved!"` when done.

---

### Problem 9: Read from a File
Write a program that opens `favorites.txt` and prints whatever is inside it.

~~~
Output: "Your favorite food is: pizza"
~~~

---

### Problem 10: Put It All Together
Write a function called `save_contact` that takes a name and phone number, and **appends** them as a line to a file called `contacts.txt` in this format:

~~~
Alice - 123-4567
~~~

Call the function 3 times with different contacts, then open the file and print all the lines.