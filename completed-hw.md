## Reading Problems

- https://realpython.com/python-dicts/
- https://realpython.com/python-for-loop/
- https://www.youtube.com/watch?v=6iF8Xb7Z3wQ

# 🐍 Python Practice Problems — Set 2

**Instructions:** Take your time, read each problem carefully, and do your best! 😊

---

## Problem 1: Your Dream Vacation

Create three variables:
- `destination` — a city you want to visit
- `days` — how many days you want to stay
- `budget` — how much money you want to bring (just a number)

Print a sentence using all three:
`I want to visit Paris for 7 days with $500!`

---

## Problem 2: True or False

Create these four variables and set each one to either `True` or `False` based on yourself:

```python
loves_pizza = 
plays_sports = 
has_a_pet = 
likes_math = 
```

Then print all four.

---

## Problem 3: My Playlist

Create a list called `playlist` with **5 of your favorite songs**.

Then:
1. Print the whole playlist
2. Print the **second** song
3. Print the **fourth** song

---

## Problem 4: Update the List

Start with this list:

```python
school_supplies = ["pencil", "notebook", "eraser", "ruler"]
```

1. Add `"calculator"` to the end
2. Change `"eraser"` to `"highlighter"`
3. Print the updated list
4. Print how many items are in the list using `len()`

---

## Problem 5: Your First Dictionary

A dictionary stores information using **keys and values** — like a label and what it contains.

Create a dictionary called `about_me` with these keys:
- `"name"`
- `"age"`
- `"city"`
- `"favorite_color"`

Then print the whole dictionary.

---

## Problem 6: Grabbing from a Dictionary

Using your `about_me` dictionary from Problem 5:

1. Print just your **name** using the key
2. Print just your **city** using the key

*(Hint: `about_me["name"]` gives you the name value!)*

---

## Problem 7: Movie Dictionary

Create a dictionary called `favorite_movie` with these keys:
- `"title"`
- `"year"`
- `"genre"`

Fill it in with a real movie you like, then print a sentence like:
`My favorite movie is Moana, released in 2016. It is an animation film.`

---

## Problem 8: Your First For Loop

Start with this list:

```python
fruits = ["apple", "banana", "mango", "grape", "strawberry"]
```

Write a for loop that prints each fruit on its own line like:
```
apple
banana
mango
grape
strawberry
```

---

## Problem 9A: Numbered List
Using the same `fruits` list, print each fruit with its index number:

```
1. I love apples!
2. I love bananas!
3. I love mangos!
4. I love grapes!
5. I love strawberrys!
```

*(Hint: you'll need `enumerate()` — look it up on google!

---

## Problem 9B: Uppercase Shouting
Same list, but print every fruit in ALL CAPS:

```
I LOVE APPLES!
I LOVE BANANAS!
I LOVE MANGOS!
I LOVE GRAPES!
I LOVE STRAWBERRYS!
```

*(Hint: strings have a method that makes them shout…)*

---

## Problem 9C: Length Check
Loop through the fruits list and print the fruit **only if its name is longer than 5 characters**:

```
bananas
mangos
grapes
strawberrys
```

*(Hint: `len()` and an `if` statement inside your loop!)*

---

## Problem 9D: Build a New List
Instead of printing, loop through `fruits` and build a **brand new list** called `love_messages` where each item is the full sentence (e.g. `"I love apples!"`). Then print the new list at the end.

Expected output:

```
['I love apples!', 'I love bananas!', 'I love mangos!', 'I love grapes!', 'I love strawberrys!']
```

*(Hint: `.append()` is your friend!)*

---

## Problem 10A: Keys AND Values
Same `pet` dictionary — now print **both** the key and value on each line:

```
name : Buddy
animal : Dog
age : 3
```

*(Hint: there's a dictionary method that gives you both at once…)*