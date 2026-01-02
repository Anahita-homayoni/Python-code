

# Python-code
Python Quick Start
Course Description

<p>Python—the popular and highly-readable object-oriented language—is both powerful and relatively easy to learn. Whether you're new to programming or an experienced developer, this course can help you get started with Python.

<p>This course includes Code Challenges powered by CoderPad. Code Challenges are interactive coding exercises with real-time feedback, so you can get hands-on coding practice alongside the course content to advance your programming skills.</p>


CoderPad is a browser-based coding platform used for live technical interviews and collaborative programming, where you can write and run code during the interview.
🧠 What CoderPad Is Used For
✅ Technical Interviews

Companies use CoderPad to ask coding questions in real time and watch you solve them — almost like a shared coding editor.

✅ Live Coding

You and the interviewer can type and run code together, with instant output.

✅ Supports Many Languages

You can write and run code in languages like:

Python

JavaScript

Java

C++

Go

SQL
…and more.





https://www.python.org/
python interpreter => launch interactive shell  =>REPEL : READ, EVALUATE, PRINT AND LOOP




Total Built-in Data Types

There are 14 main built-in data types:

int

float

complex

str

list

tuple

range

dict

set

frozenset

bool

bytes

bytearray

memoryview

NoneType


Python Dictionary (dict) – Brief Explanation

A dictionary in Python is a built-in data type used to store data in key–value pairs.

Each value is accessed using its unique key.

Dictionaries are unordered, changeable (mutable), and do not allow duplicate keys.

Example:
student = {
    "name": "Alex",
    "age": 20,
    "course": "Python"
}


In this example:

Keys: name, age, course

Values: "Alex", 20, "Python"

Why use a dictionary?

Fast data lookup using keys

Well-structured and easy to manage data

Commonly used to store records, settings, and configurations





Conditional Formatting in Python

Conditional formatting means changing the appearance of data based on certain conditions.
In Python, it is mainly used while working with Excel files and data tables to highlight values that meet specific rules.

It helps to easily identify important data such as high values, low values, errors, or duplicates.

Example (Using Pandas & Excel)
import pandas as pd

data = {'Marks': [45, 67, 89, 30, 95]}
df = pd.DataFrame(data)

def highlight(val):
    return 'background-color: lightgreen' if val > 80 else ''

df.style.applymap(highlight)


Explanation:

Marks above 80 will be highlighted in green.

Others remain unchanged.

Where it is used:

Excel report generation

Data analysis

Dashboards and reports

Highlighting errors or important values




Python for Loop with break, continue, pass, and enumerate()

A for loop is used to iterate over a sequence such as a list, tuple, string, or range.

1. break Statement

Stops the loop completely when a condition is met.

for i in range(1, 6):
    if i == 4:
        break
    print(i)

2. continue Statement

Skips the current iteration and continues with the next one.

for i in range(1, 6):
    if i == 3:
        continue
    print(i)

3. pass Statement

Acts as a placeholder. It does nothing but keeps the program running without errors.

for i in range(1, 6):
    if i == 3:
        pass
    print(i)

4. enumerate() Function

enumerate() adds a counter to an iterable and returns both the index and value.

fruits = ["Apple", "Banana", "Mango"]

for index, fruit in enumerate(fruits):
    print(index, fruit)


Output:

0 Apple
1 Banana
2 Mango

Summary
Feature	Purpose
break	Stops the loop
continue	Skips an iteration
pass	Does nothing (placeholder)
enumerate()	Returns index and value together

Basic Functions of Python

Python provides several built-in functions that perform common tasks and make programming easier.

Some Important Basic Functions:
Function	Purpose	Example
print()	Displays output on the screen	print("Hello")
input()	Takes input from the user	name = input("Enter name: ")
type()	Returns the data type of a value	type(10)
len()	Returns length of an object	len("Python")
int()	Converts to integer	int("5")
float()	Converts to float	float("3.2")
str()	Converts to string	str(100)
sum()	Returns total of values	sum([1,2,3])
max()	Returns highest value	max(10, 50, 20)
min()	Returns smallest value	min(10, 50, 20)
range()	Generates a sequence of numbers	range(1,5)
In Simple Words:

Basic functions in Python help you display data, take input, check types, convert values, and perform common operations easily.


LINK FOR BULID IN FUNCTION:https://docs.python.org/3/library/functions.html




# retrieve today's weekday (0=Monday, 6=Sunday)
print("TODAY'S WEEKDAY #:", today.weekday())

DAYS = ["MON", "TUE", "WED", "THURS", "FRI", "SAT", "SUN"]

print("Which is:", DAYS[today.weekday()])


🕒 What is timedelta in Python?

In Python, timedelta is a class from the datetime module used to represent a duration of time — the difference between two dates or times.

It lets you add or subtract time such as days, hours, minutes, or seconds from a date.

Importing timedelta
from datetime import timedelta

Creating a timedelta
from datetime import timedelta

time_gap = timedelta(days=5, hours=3, minutes=30)
print(time_gap)


Output:

5 days, 3:30:00

Adding time to a date
from datetime import date, timedelta

today = date.today()
future = today + timedelta(days=10)

print("Today:", today)
print("After 10 days:", future)

Subtracting time from a date
from datetime import date, timedelta

today = date.today()
past = today - timedelta(days=7)

print("7 days ago:", past)

Finding difference between two dates
from datetime import date

d1 = date(2026, 1, 1)
d2 = date(2026, 1, 15)

difference = d2 - d1
print(difference)


Output:

14 days, 0:00:00

Why timedelta is useful

Scheduling tasks

Calculating deadlines

Tracking time differences

Working with calendars

Date arithmetic
