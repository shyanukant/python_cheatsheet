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
## 5. 🧠 **Dictionaries**

> Dictionaries store connections between pieces of information. Each item in a dictionary is a key-value pair. 

#### 🔑 **A simple dictionary**

```python
alien = {'color': 'green', 'points': 5}
```

### 🎨 Accessing a value
```python
print(f"The alien's color is {alien['color']}. 👽")
```

### ➕ Adding a new key-value pair
```python
alien['x_position'] = 0
```

### 🔄 Looping through all key-value pairs
```python
fav_numbers = {'shyanukant': 7, 'elon': 42, 'alice': 101}
for name, number in fav_numbers.items():
    print(f"{name.capitalize()} loves {number}. 💙")
```

### 🔑 Looping through all keys
```python
fav_numbers = {'shyanukant': 7, 'elon': 42, 'alice': 101}
for name in fav_numbers.keys():
    print(f"{name.capitalize()} loves a number. 🔢")
```

### 💯 Looping through all the values
```python
fav_numbers = {'shyanukant': 7, 'elon': 42, 'alice': 101}
for number in fav_numbers.values():
    print(f"{number} is a favorite number! 🎯")
```

### 🔥 User Input
_Your programs can prompt the user for input. All input is stored as a string. 📝_

### 👋 Prompting for a value
```python
name = input("What's your name? ")
print(f"Hello, {name}! 👋")
```

### 🧮 Prompting for numerical input
```python
age = input("How old are you? ")
age = int(age)  # Don't forget to convert it into an integer!

pi = input("What's the value of pi? ")
pi = float(pi)  # Convert to float for precise calculations!
```
## 6. 🔁 **While Loops**

_A `while` loop repeats a block of code as long as a certain condition is true. It's perfect when you can't know ahead of time how many times a loop should run!_ 🤔

#### ▶️ **A simple while loop**
```python
current_value = 1
while current_value <= 5:
    print(current_value)  # Prints 1, 2, 3, 4, 5 🎉
    current_value += 1
```

### 🛑 Letting the user choose when to quit

```python
msg = ''
while msg != 'quit':
    msg = input("What's your message? (type 'quit' to exit) ")
    if msg != 'quit':
        print(f"You said: {msg} 💬")
```

## 7. 🔧 **Functions**

_Functions are named blocks of code, designed to perform one specific job. The data passed to a function is called an argument, and the information received by a function is called a parameter._ 📦

### 👋 **A simple function**
```python
def greet_user():
    """Display a simple greeting."""
    print("Hello! 👋")
```

```python 
greet_user()`  # Output: Hello! 👋
```

### 🧑‍🤝‍🧑 **Passing an argument**
```python
def greet_user(username):
    """Display a personalized greeting."""
    print(f"Hello, {username}! 🌟")
```
```python
greet_user('Shyanukant')  # Output: Hello, Shyanukant! 🌟
```

### 🍕 **Default values for parameters**
```python
def make_pizza(topping='pineapple'):
    """Make a single-topping pizza."""
    print(f"Have a {topping} pizza! 🍕")
```
```python
make_pizza()              # Output: Have a pineapple pizza! 🍍🍕
make_pizza('mushroom')    # Output: Have a mushroom pizza! 🍄🍕
```

### ➕ **Returning a value**
```python
def add_numbers(x, y):
    """Add two numbers and return the sum."""
    return x + y
```
```python
sum = add_numbers(3, 5)
print(sum)  # Output: 8 🎉
```

## 8. 🚗 **Classes**

_A class defines the behavior of an object and the kind of information an object can store. The information in a class is stored in attributes, and functions that belong to a class are called methods. A child class inherits the attributes and methods from its parent class._ 🧑‍🏫

### 🚗 **Creating a Car class**
```python
class Car:
    """Represent a car."""
    
    def __init__(self, make, model):
        """Initialize car object."""
        self.make = make
        self.model = model
        
    def start_engine(self):
        """Simulate starting the engine."""
        print(f"The {self.make} {self.model}'s engine is now running! 🚗💨")
```

```python
my_car = Car('Tesla', 'Model S')
print(f"My car is a {my_car.make} {my_car.model}.")
my_car.start_engine()  # Output: The Tesla Model S's engine is now running! 🚗💨
```

### 🏎️ **Inheritance**
```python
class ElectricCar(Car):
    """Represent an electric car, a specific kind of car."""
    
    def __init__(self, make, model, battery_size=75):
        """Initialize the electric car."""
        super().__init__(make, model)
        self.battery_size = battery_size
        
    def charge_battery(self):
        """Simulate charging the battery."""
        print(f"The {self.make} {self.model} is charging its {self.battery_size}-kWh battery 🔋⚡.")
```

```python
my_electric_car = ElectricCar('Tesla', 'Model X', 100)
print(f"{my_electric_car.make} {my_electric_car.model} has a {my_electric_car.battery_size}-kWh battery.")
my_electric_car.start_engine()
my_electric_car.charge_battery()
```

### 📁 **Working with Files**

Your programs can read from and write to files. The pathlib library makes working with files and directories easier.

### 📖 **Reading the contents of a file**
```python
from pathlib import Path

path = Path('example.txt')
contents = path.read_text()
lines = contents.splitlines()

for line in lines:
    print(line)  # Output: each line from the file
```

### ✍️ **Writing to a file**
```python
path = Path('journal.txt')
msg = "I love programming! 💻❤️"
path.write_text(msg)  # Writes the message to the file
```

### 🚨 **Exceptions**

_Exceptions help you respond appropriately to errors that are likely to occur. You place code that might cause an error in the try block. Code that should run in response to an error goes in the except block. Code that should run only if the try block was successful goes in the else block._

### ❗ **Catching an exception**
```python
prompt = "How many tickets do you need? "
num_tickets = input(prompt)

try:
    num_tickets = int(num_tickets)
except ValueError:
    print("Oops! That's not a valid number. Please try again. 😅")
else:
    print("Your tickets are printing! 🎟️")
```
## 🐍 Python Cheat Sheet - Lists 📜

### **What are lists?** 🤔
_A list stores a series of items in a specific order. You can store anything from a few items to millions of them! Lists are one of Python's most powerful features—simple yet mighty. 💪_

### **Defining a List** 📋
_Use square brackets `[]` to define a list, and commas to separate items. Use plural names for lists, like `fruits`, to show it's holding more than one thing._

#### 🍎 Making a List
```python
users = ['Shyanukant', 'alice', 'elon', 'tony', 'bruce']
```

### **Accessing Elements** 🧑‍💻
_You can access list items by their index. The first element has an index of 0, the second is 1, and so on. Use negative indices for items from the end!_

### 🥇 Getting the first element
```python
first_user = users[0]  # 'Shyanukant'
```
### 🥈 Getting the second element
```python
second_user = users[1]  # 'alice'
```
### 🏅 Getting the last element
```python
last_user = users[-1]  # 'bruce'
```

### **Modifying Elements** 🔧
_You can update a list by referring to an element’s index and assigning it a new value._

### 🛠️ Changing an element
```python
users[0] = 'shy'
users[2] = 'Elon_Musk_2.0'
```

### **Adding Elements** ➕
_Adding to a list is easy! You can add items to the end with append() or insert them at a specific position with insert()._

### 🚀 Adding an element to the end
```python
users.append('natasha')
```
### 📝 Starting with an empty list
```python
users = []
users.append('Shyanukant')
users.append('steve')
```
### ✨ Inserting elements at a position
```python
users.insert(1, 'wanda')  # Inserts 'wanda' at position 1
```

### **Removing Elements** ❌
_Remove items by their position or value. If removing by value, only the first match is removed._

### 🗑️ Deleting an element by position
```python
del users[-1]  # Removes the last user
```
### 💥 Removing an element by value
```python
users.remove('steve')  # Poor Steve 😢
```

### **Popping Elements** 🎈
_You can "pop" an item off a list—like popping balloons! 🎈 The default is to pop the last element, but you can pop from any index._

### 🧨 Pop the last item
```python
most_recent_user = users.pop()  # Removes 'natasha'
```
### 🥳 Pop the first item
```python
first_user = users.pop(0)  # Removes 'Shyanukant'
```

### List Length 📏
Use len() to find the number of items in your list.

### 📊 Find the length of a list
```python
num_users = len(users)
print(f"We have {num_users} users!")  # Cool, huh? 😎
```

### **Sorting a List** 🗃️
_Sorting is a breeze! Use sort() for permanent sorting, and sorted() if you just need a temporary sort._

### 📈 Sorting a list alphabetically
```python
users.sort()
```
### 📉 Sorting in reverse alphabetical order
```python
users.sort(reverse=True)
```
### 🔄 Reversing the order of a list
```python
users.reverse()
```

### **Looping Through a List** ♻️
_Loops let you work with every item in a list. Each item gets assigned to a temporary variable._

### 🔍 Printing all users
```python
for user in users:
    print(user)
```
### ✉️ Printing a welcome message for each user
```python
for user in users:
    print(f"Welcome, {user}!")
print("We're so glad you're all here! 🎉")
```
```python
The range() Function 🚶
Use range() to efficiently generate numbers.
```
### 🔢 Printing numbers 0 to 10
```python
for number in range(11):
    print(number)
```
### 🎇 Making a list of numbers
```python
numbers = list(range(1, 21))  # Numbers from 1 to 20
```

### **Simple Statistics** 📊
_You can find the minimum, maximum, and sum of a list of numbers._

### 🥇 Finding the youngest age
```python
ages = [25, 32, 18, 40, 22]
youngest = min(ages)  # 18
```
### 🏆 Finding the oldest age
```python
oldest = max(ages)  # 40
```
### ➕ Finding the total years
```python
total_years = sum(ages)  # 137 years combined!
```

### **Slicing a List** ✂️
_Work with just a part of your list by slicing it._

### 🥧 Getting the first three finishers
```python
finishers = ['kai', 'abe', 'ada', 'gus', 'zoe']
first_three = finishers[:3]  # ['kai', 'abe', 'ada']
```
### 🏁 Getting the middle three finishers
```python
middle_three = finishers[1:4]  # ['abe', 'ada', 'gus']
```
### 🎉 Getting the last three finishers
```python
last_three = finishers[-3:]  # ['ada', 'gus', 'zoe']
```

### **Copying a List** 📑
_When copying lists, be careful to make an actual copy, or changes to one list might affect the other!_

### 📋 Copying a list
```python
copy_of_finishers = finishers[:]  # Full copy of the list
```
## 📝 Python List Comprehensions Cheatsheet
### 🚀 What are List Comprehensions?
_You can use a loop to generate a list based on a range of numbers or an existing list. While loops work fine, list comprehensions are a more efficient and Pythonic way to get the job done. They may look tricky at first, but don't worry, practice makes perfect! 🎯_

### 🔄 Loop vs List Comprehension
_You can always fall back to loops, but once you get comfortable, comprehensions will make you feel like a Python ninja 🐍🗡️._

### 📐 Generate a List of Square Numbers
### 🌀 Using a loop:
```python
squares = []
for x in range(1, 11):
    square = x**2
    squares.append(square)

print(squares)
```
### ⚡ Using a comprehension:
```python
squares = [x**2 for x in range(1, 11)]
print(squares)  # Efficient and clean! ✨
```
### 🔤 Convert Names to Upper Case
### 🌀 Using a loop:
```python
names = ['shyan', 'arjun', 'olivia', 'bella', 'zoe']
upper_names = []
for name in names:
    upper_names.append(name.upper())

print(upper_names)
```
### ⚡ Using a comprehension:
```python
names = ['shyan', 'arjun', 'olivia', 'bella', 'zoe']
upper_names = [name.upper() for name in names]
print(upper_names)  # All caps, ready for the spotlight! 💡
```
### 🍎 List Comprehensions Fun Example
```python
fruits = ['apple', 'banana', 'cherry', 'date']
tasty_fruits = [f"{fruit} is tasty! 😋" for fruit in fruits]
print(tasty_fruits)
```
