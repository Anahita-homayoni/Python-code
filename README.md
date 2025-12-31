

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
