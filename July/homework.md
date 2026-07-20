## Homework Set 2: Dictionaries, Error Handling & Real Programs 🔥
### (Level Up — you've earned this)

---

### Problem 1: Default Parameters
Write a function called `greet` that takes a name **and** a greeting, but the greeting defaults to `"Hello"` if none is given.
~~~
greet("Alice") → prints "Hello, Alice!"
greet("Alice", "Welcome back") → prints "Welcome back, Alice!"
~~~

---

### Problem 2: Find the Max (No Cheating!)
Write a function called `find_biggest` that takes a **list of numbers** and returns the biggest one — **without** using Python's built-in `max()`. Use a loop.
~~~
find_biggest([3, 41, 12, 9]) → returns 41
~~~

---

### Problem 3: Your First Dictionary
Create a dictionary called `phone_book` with 3 names as keys and phone numbers as values. Then ask the user for a name and print that person's number.
~~~
phone_book = {"Alice": "123-4567", "Bob": "555-0199", "Cara": "888-2222"}
Input: "Bob" → Output: "Bob's number is 555-0199"
~~~

---

### Problem 4: Handling Missing Keys
Improve Problem 3: if the user types a name that's **not** in the dictionary, print `"Sorry, no contact found."` instead of crashing. (Hint: `in` keyword or `.get()`)

---

### Problem 5: try / except — Crash-Proof Input
Ask the user for their age. If they type something that isn't a number, don't crash — catch the error with `try` / `except` and print `"That's not a number!"`. Keep asking in a while loop until they enter a valid number.
~~~
Input: "banana" → "That's not a number!"
Input: "15" → "Got it, you are 15."
~~~

---

### Problem 6: Word Counter
Write a function called `count_words` that takes a sentence and returns a **dictionary** where each word is a key and the value is how many times it appears.
~~~
count_words("the cat and the dog") → {"the": 2, "cat": 1, "and": 1, "dog": 1}
~~~

---

### Problem 7: List Comprehension
You know loops — now the shortcut. Given this list:
~~~python
numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
~~~
Use a **list comprehension** (one line!) to make a new list of only the even numbers, each multiplied by 10.
~~~
Result: [20, 40, 60, 80, 100]
~~~

---

### Problem 8: Parse a File Line by Line
Remember `contacts.txt` from last homework (`Alice - 123-4567` format)? Write a function called `load_contacts` that reads the file line by line, splits each line on `" - "`, and returns a **dictionary** of name → phone number.
~~~
load_contacts() → {"Alice": "123-4567", "Bob": "555-0199", ...}
~~~

---

### Problem 9: To-Do List App (Menu + Functions + Files)
Build a small program with a while loop menu:
~~~
1. Add a task
2. Show all tasks
3. Quit
~~~
- "Add" appends the task to `todo.txt`
- "Show" reads the file and prints each task with a number in front (`1. Buy milk`)
- Use a **separate function** for each menu option
- If the user picks an invalid option, print `"Invalid choice"` and show the menu again

---

### Problem 10: Final Boss — Grade Tracker 🏆
Build a program that combines **everything**:
- A function `add_student(name, grade)` that saves `name,grade` to `grades.txt` — but only if the grade is a valid number between 0 and 100 (use try/except!)
- A function `show_report()` that reads the file into a dictionary, prints every student's grade, and then prints the **class average** and the **top student**
- A while loop menu to run it all: Add Student / Show Report / Quit

~~~
Sample report:
Alice: 92
Bob: 78
Cara: 85
Class average: 85.0
Top student: Alice 🏆
~~~