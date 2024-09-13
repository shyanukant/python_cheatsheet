# 🐍 **Shyanukant Rathi's Python Cheat Sheet** 🎯
[![Python](https://img.shields.io/badge/Python-3-blue.svg)](https://www.python.org/) [![Follow Shyanukant](https://img.shields.io/badge/Follow-Me-blue)](https://github.com/shyanukant)

Welcome to your go-to Python cheat sheet, filled with fun, quirky examples, and plenty of emojis to keep you entertained while you code! 🚀

---

## **1. Variables and Strings** 💡  
_Variables give names to data, and strings are like fun messages you store in those names. Use Python's f-strings to insert variables into strings!_

### 👋 Hello, World! 🌍  
```python
print("Hello world!")  # Every coder's first words! 🎉
```

### 🎤 Hello World with a Variable

```python
greeting = "Hello, Python enthusiasts!"
print(greeting)  # A custom shout-out to all you coders out there!
```

### 😎 f-Strings: Bringing Variables to Life

```python
first_name = 'Shyanukant'
last_name = 'Rathi'
full_name = f"{first_name} {last_name}"  
print(f"Welcome {full_name}, ready to code some magic?")  # Self-intro with style!
```
## **2. Lists** 📋
_A list stores multiple items, like your favorite movies or favorite snacks! You can access items by their position (called an index) and loop through them._

### 🎬 A List of Favorite Movies

```python
favorite_movies = ['Inception', 'The Matrix', 'Interstellar']  # Sci-fi binge time! 🎥
```

### 🍿 Getting the First Movie in the List
```python
first_movie = favorite_movies[0]
print(f"My top pick is: {first_movie}")  # Always start strong!
```

### 🎟️ Getting the Last Movie
```python
last_movie = favorite_movies[-1]
print(f"Ending with a masterpiece: {last_movie}")  # Save the best for last!
```

### 🔄 Looping Through the Movies
```python
for movie in favorite_movies:
    print(f"Watching: {movie}")  # Movie marathon, anyone?
```

### ➕ Adding New Movies
```python
favorite_movies.append('Avengers: Endgame')
favorite_movies.append('Shutter Island')
print(f"Updated movie list: {favorite_movies}")  # Added some epic ones!
```

### **Making Numerical Lists** 🔢

_Python makes it easy to generate lists of numbers using loops or special techniques like list comprehensions!_

### 🎯 Making a List of Square Numbers
```python
squares = []
for x in range(1, 6):
    squares.append(x**2)  # Squares are cool! 💪
print(squares)
```
### ⚡ List Comprehensions: Faster, Cooler
```python
squares = [x**2 for x in range(1, 6)]  # Same thing, but quicker!
print(squares)  # Python speed run! 🏃‍♂️
```
### **Slicing a List** ✂️  
_Slicing allows you to grab specific sections of a list, like selecting the first few players in a game._

### 🏅 Slicing to Get the First Two Players  
```python
players = ['Alice', 'Bob', 'Charlie', 'Diana']  # Game night! 🎮
first_two = players[:2]
print(f"The first two players are: {first_two}")  # Who's up first?
```
### **Copying a List** 📝
_Copying lists in Python is easy. Here's how to make a duplicate of your favorite snacks list!_

### 🍩 Copying a List of Favorite Snacks
```python
snacks = ['Chips', 'Cookies', 'Soda']  # Ready for snack time! 🍿
copy_of_snacks = snacks[:]
print(f"Original list: {snacks}")
print(f"Copy of the list: {copy_of_snacks}")  # Backup snacks are important!
```

## **3. Tuples** 🔒
_Tuples are like lists, but they can't be changed once they're made. Perfect for settings that stay constant!_

### 🧳 Packing Dimensions in a Tuple
```python
luggage_dimensions = (22, 14, 9)  # Standard carry-on luggage size 📦
airline_classes = ('Economy', 'Business', 'First Class')
print(f"Luggage dimensions: {luggage_dimensions}")
print(f"Available classes: {airline_classes}")  # No upgrading mid-flight! ✈️
```

## 4. If Statements 🧐

_If statements help your program make decisions by checking conditions._

### 🔢 Conditional Tests: Checking if Numbers are Prime

```python
number = 29
if number % 2 != 0:
    print(f"{number} is a prime number!")  # A quick prime check! 🎯
else:
    print(f"{number} is not prime.")
```

### **Conditional Tests with Lists 📝**

_Check if items are in your list of books or missing from it._

### 📚 Is a Book on Your Reading List?

```python
reading_list = ['1984', 'To Kill a Mockingbird', 'The Hobbit']
print('1984' in reading_list)  # True, George Orwell makes the cut!
print('The Catcher in the Rye' not in reading_list)  # Not on the list yet!
```

### **Boolean Values** 💡

_Booleans represent True or False, perfect for tracking game states or user activity._

### 🎮 Tracking Game Status

```python
game_running = True  # The game is on! 🕹️
level_completed = False  # Still working on that last level 🎯
print(f"Game running: {game_running}, Level completed: {level_completed}")
```

### **Simple If Test** 🧪

_Use if to check a simple condition and run some code if it's true._

### 🏀 Are You Tall Enough for the Ride?

```python
height = 130  # Height in centimeters
if height >= 120:
    print("You're tall enough to ride the roller coaster! 🎢")
```

## 5. If-Elif-Else Statements 🔄

_When you have multiple conditions to check, use if-elif-else to handle each case._

### 🍔 Deciding What to Eat Based on Time

```python
time_of_day = 14  # 14 means 2 PM
if time_of_day < 12:
    meal = "breakfast"
elif time_of_day < 17:
    meal = "lunch"
else:
    meal = "dinner"
print(f"It's time for {meal}!")  # What's on the menu? 🍽️
```
