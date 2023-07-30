---
aliases: 
section: python
category: course
course_name: codecademy_python
location: codecademy
type: notebook
tags: function
priority:
status: done
date: [[2022-02-05]]
---
%%
parents:: [[Codecademy Outline]]
child::
siblings::
%%
# Python
- [[#First Steps|First Steps]]
- [[#Data Types|Data Types]]
	- [[#Data Types#Comment|Comment]]
	- [[#Data Types#Variables|Variables]]
	- [[#Data Types#Intergers|Intergers]]
	- [[#Data Types#Floating point numbers|Floating point numbers]]
	- [[#Data Types#Boolean Values|Boolean Values]]
- [[#Statements|Statements]]
	- [[#Statements#elif Statement|elif Statement]]
	- [[#Statements#' if ' Statement|' if ' Statement]]
	- [[#Statements#' else ' Statement|' else ' Statement]]
- [[#Operators|Operators]]
	- [[#Operators#Arithmatic operations|Arithmatic operations]]
	- [[#Operators#Plus-Equals Operator|Plus-Equals Operator]]
	- [[#Operators#Modulo Operator|Modulo Operator]]
	- [[#Operators#print() Function|print() Function]]
	- [[#Operators#' or ' Operator|' or ' Operator]]
	- [[#Operators#Equal Operator ' == '|Equal Operator ' == ']]
	- [[#Operators#Not Equals Operator ' != '|Not Equals Operator ' != ']]
	- [[#Operators#Comparison Operators|Comparison Operators]]
	- [[#Operators#' and ' Operator|' and ' Operator]]
	- [[#Operators#' not ' Operator|' not ' Operator]]
- [[#Error Codes|Error Codes]]
	- [[#Error Codes#Errors|Errors]]
	- [[#Error Codes#ZeroDivisionError|ZeroDivisionError]]
	- [[#Error Codes#SyntaxError|SyntaxError]]
	- [[#Error Codes#NameError|NameError]]
	- [[#Error Codes#IndexError|IndexError]]
	- [[#Error Codes#IndentationError|IndentationError]]
	- [[#Error Codes#Other Error Codes|Other Error Codes]]
		- [[#Other Error Codes#Infinite Loop Error|Infinite Loop Error]]
- [[#Lists|Lists]]
	- [[#Lists#Adding Lists Together|Adding Lists Together]]
	- [[#Lists#Python Lists: Data Types|Python Lists: Data Types]]
	- [[#Lists#Zero Indexing|Zero Indexing]]
	- [[#Lists#List Indices|List Indices]]
	- [[#Lists#Negative List Indices|Negative List Indices]]
	- [[#Lists#Modifying 2D Lists|Modifying 2D Lists]]
	- [[#Lists#Accessing 2D Lists|Accessing 2D Lists]]
	- [[#Lists#List Method|List Method]]
		- [[#List Method#.append( )|.append( )]]
		- [[#List Method#.remove( )|.remove( )]]
		- [[#List Method#.count( )|.count( )]]
		- [[#List Method#.sort ( )|.sort ( )]]
		- [[#List Method#.insert( )|.insert( )]]
		- [[#List Method#.pop( )|.pop( )]]
	- [[#Lists#Determining List Length with len( )|Determining List Length with len( )]]
	- [[#Lists#List Slicing|List Slicing]]
	- [[#Lists#sorted ( ) Function|sorted ( ) Function]]
- [[#Loops|Loops]]
	- [[#Loops#'break' Keyword|'break' Keyword]]
	- [[#Loops#List Comprehension|List Comprehension]]
	- [[#Loops#'for' Loop|'for' Loop]]
	- [[#Loops#'continue' Keyword|'continue' Keyword]]
	- [[#Loops#Loops with 'range( )'|Loops with 'range( )']]
	- [[#Loops#Infinite Loop|Infinite Loop]]
	- [[#Loops#'while' Loops|'while' Loops]]
	- [[#Loops#Nested Loops|Nested Loops]]
- [[#Functions|Functions]]
	- [[#Functions#Function Parameters|Function Parameters]]
	- [[#Functions#Multiple Parameters|Multiple Parameters]]
	- [[#Functions#Function Indentation|Function Indentation]]
	- [[#Functions#Calling Functions|Calling Functions]]
	- [[#Functions#Function Arguments|Function Arguments]]
	- [[#Functions#Function Keyword Arguments|Function Keyword Arguments]]
	- [[#Functions#Returning Multiple Values|Returning Multiple Values]]
	- [[#Functions#The scope of Variables|The scope of Variables]]
	- [[#Functions#Returning Value from Function|Returning Value from Function]]
	- [[#Functions#Global Variables|Global Variables]]
	- [[#Functions#Parameters as Local Variables|Parameters as Local Variables]]
- [[#Strings|Strings]]
	- [[#Strings#Escaping Characters|Escaping Characters]]
	- [[#Strings#The 'in' Syntax|The 'in' Syntax]]
	- [[#Strings#Indexing and Slicing Strings|Indexing and Slicing Strings]]
	- [[#Strings#Iterate String|Iterate String]]
	- [[#Strings#Build-in Function 'len( )'|Build-in Function 'len( )']]
	- [[#Strings#String Concatenation|String Concatenation]] 
	- [[#Strings#Immutable Strings|Immutable Strings]]
	- [[#Strings#String Methods|String Methods]]
		- [[#String Methods#.format( )|.format( )]]
		- [[#String Methods#.lower( )|.lower( )]]
		- [[#String Methods#.strip( )|.strip( )]]
		- [[#String Methods#.title( )|.title( )]]
		- [[#String Methods#.split( )|.split( )]]
		- [[#String Methods#.find ( )|.find ( )]]
		- [[#String Methods#.upper( )|.upper( )]]
		- [[#String Methods#.join( )|.join( )]]
	- [[#Strings#String Replace|String Replace]]
- [[#Modules|Modules]]
	- [[#Modules#Date and Time|Date and Time]]
	- [[#Modules#Aliasing with 'as' keyword|Aliasing with 'as' keyword]]
	- [[#Modules#Import Python Modules|Import Python Modules]]
	- [[#Modules#random.randint( ) - random.choice( )|random.randint( ) - random.choice( )]]
	- [[#Modules#Module Importing|Module Importing]]
- [[#Dictionaries|Dictionaries]]
	- [[#Dictionaries#Accessing and Writing Data in a Python Dictionary|Accessing and Writing Data in a Python Dictionary]]
	- [[#Dictionaries#Syntax of the Python Dictionary|Syntax of the Python Dictionary]]
	- [[#Dictionaries#Dictionary Value Types|Dictionary Value Types]]
	- [[#Dictionaries#Python dictionaries|Python dictionaries]]
	- [[#Dictionaries#Dictionary Methods|Dictionary Methods]]
		- [[#Dictionary Methods#Dictionary Key-Value Methods|Dictionary Key-Value Methods]]
		- [[#Dictionary Methods#get( ) Method for Dictionary|get( ) Method for Dictionary]]
		- [[#Dictionary Methods#Merging Dictionaries with the .update( ) method in Python|Merging Dictionaries with the .update( ) method in Python]]
		- [[#Dictionary Methods#The .pop( ) Method for Dictionaries in Python|The .pop( ) Method for Dictionaries in Python]]
- [[#Files|Files]]
	- [[#Files#Python File Object|Python File Object]]
	- [[#Files#Python Readline Method|Python Readline Method]]
	- [[#Files#Parsing JSON Files to Dictionary|Parsing JSON Files to Dictionary]]
	- [[#Files#Python Append to File|Python Append to File]]
	- [[#Files#Python Write to File|Python Write to File]]
	- [[#Files#Python Readlines Method|Python Readlines Method]]
	- [[#Files#Class csv.DictWriter|Class csv.DictWriter]]
	- [[#Files#Python Read Method|Python Read Method]]
- [[#Classes|Classes]]
	- [[#Classes#' repr ' Method|' repr ' Method]]
	- [[#Classes#Class Methods|Class Methods]] ^1ca14c
	- [[#Classes#Instantiate Python Class|Instantiate Python Class]]
	- [[#Classes#Class Variables|Class Variables]]
	- [[#Classes#' init ' Method|' init ' Method]]
	- [[#Classes#' type( ) ' Function|' type( ) ' Function]]
	- [[#Classes#Python Class|Python Class]]
	- [[#Classes#' dir( ) ' Function|' dir( ) ' Function]]
	- [[#Classes#__main__ in Python|__main__ in Python]]

## First Steps: 

1. Download Python
2. Download VS Code and install Python extensions
3. Make a GitHub account to store code/notes
     
You don’t have to use the text editor window in your compiler to run Python code. Down in your terminal, you can run `python` alone. You will be presented with `>>>` in the terminal window. You can then run live, interactive code. You could type `1+1` and it will run that calculation.

## Data Types
- [[#Comment|Comment]]
- [[#Variables|Variables]]
- [[#Intergers|Intergers]] 
- [[#Floating point numbers|Floating point numbers]]
- [[#Boolean Values|Boolean Values]]
### Comment
#comment 

````python
# This is a comment 

user = "JDoe" # this is a comment after code
````

comment = piece of text within a program that is not executed. 
> - provides additional information (notes for yourself/others)
>- ''#'' character used to start comment and it finishes at the end of the line

this is also a comment: 
```python
"""
This is a comment
"""
```

**TIP** keyboard shortcut: `CTRL + /` 

### Variables
#variable

Variable can store a value-- a number, some text, even an image or video or more

```python
# These are all valid variable names and assignments

user_name = "codey"
user_id = 100
verified = False

# A variable's value can be changed after assignment

points = 100
points = 120
```
- A variable is just a container for a value within your own program.
	- can use 'x' or use a [[Lecture 0 Transcript 1#^0b8216|name]]
	- '=' means [[Lecture 0 Transcript 1#^0b8216|assigned]] to 

Used to store data that will be used by the program
> - can be a number, string, boolean, a list or some other data type
> - Every Variable has a name consisting of letters, numbers, or/and the underscore character
- The '=' sign assigns what is on the right to what is on the left.

###### Other notes on Variables
- [[Python_Notebook#The Scope of Variables|The Scope of Variables]]
- [[Python_Notebook#Global Variables|Global Variables]]
- [[Python_Notebook#Parameters as Local Variables|Parameters as Local Variables]]
- [[Python_Notebook#Class Variables|Class Variables]]

### Intergers

int = interger

#interger 
```python
# Example integer numbers

chairs = 4
table = 1
broken_chairs = -2
sofas = 0

# Non-interger numbers

lights = 2.5
left_overs = 0.0
```

Interger: 
>- number written without fractional part (no decimal)
>- can be positive, negative or zero

```python
x = input("What's x? ")
y = input("What's y? ")

z = int(x) + int(y)

print(z)
```

- `int(x)` = **casting**
	- a value is temporarily changed from one type of #variable (in this case #string) to another (here, an #integer)

Improve by running function on functions:
```python
x = int(input("What's x? "))
y = int(input("What's y? "))

print(x + y)
```

First the `input` function is run, then the `int`

### Floating point numbers
#FloatingPoint

Floating point value = decimal in it 
```python
# Floating point numbers

pi = 3.14159
meal_cost = 12.99
tip_percent = 0.20
```

```python
x = float(input("What's x? "))
y = float(input("What's y? "))

print(x + y)
```
A value that contains a decimal portion.

**NOTE**  use a `.` and not a `,`

`0.4` can be written as `.4` 
`4.0` can be written as `4.`

#### Round Floats: 
Round to the nearest interger:
```python
# Get the user's input
x = float(input("What's x? "))
y = float(input("What's y? "))

# Create a rounded result
z = round(x + y)

# Print the result
print(z)
```
Round the result to the nearest two decimal points:
```python
# Get the user's input
x = float(input("What's x? "))
y = float(input("What's y? "))

# Calculate the result and round
z = round(x / y, 2)

# Print the result
print(z)
```

#### Round with fstring

Use `fstring` to format the output: 
```python
# Get the user's input
x = float(input("What's x? "))
y = float(input("What's y? "))

# Calculate the result
z = x / y

# Print the result
print(f"{z:.2f}")
```

#### Long Numbers Output:
```python
# Get the user's input
x = float(input("What's x? "))
y = float(input("What's y? "))

# Create a rounded result
z = round(x + y)

# Print the formatted result
print(f"{z:,}")
```

### Boolean Values
#boolean
```python
is_true = True
is_false = False

print(type(is_true))
# will output: <class 'bool'>
```
    
Booleans only have two values: 
- <span style='color:#20bf6b'>True</span>
- <span style='color:#20bf6b'>False</span>
     
^ These two values are of the <span style='color:#20bf6b'>bool</span> type. 

## Statements
#statement
Also known as [[Python Control Flow|Control Flow]]
    
- [[#' if ' Statement|' if ' Statement]]
- [[#elif Statement|elif Statement]]
- [[#' else ' Statement|' else ' Statement]]
- [[#`match` Statement|'match' Statement]]
    
### ' if ' Statement
#if #statement 
````python
# if Statement

test_value = 100 

if test_value > 1:
	# Expression evaluates to True
	print("This code is executed!")

if test_value > 1000: 
	# Expression evaluates to False
	print("This code is NOT executed!")

print("Program continues at this point.")
````

<span style='color:#20bf6b'>If</span> Statement is used to determine the execution of code based on the evaluation of a Boolean expression. 
    
<span style='color:#20bf6b'>True</span> = the indented code following the statement is executed. 
    
<span style='color:#20bf6b'>False</span> = the indented code following the statement is skipped and the program executes the next line of code which is indented at the same level as the <span style='color:#20bf6b'>if</span> statement.      

```python
x = int(input("What's x? "))
y = int(input("What's y? "))

if x < y:
    print("x is less than y")
```
- x and y casted as [[Lecture 0 Notes#Lecture 0 Reading [Integers or int](https://cs50.harvard.edu/python/2022/notes/0/ integers-or-int) Integers or int|interger]] and saves them in their respective x and y [[Lecture 0 Notes#Lecture 0 Reading [Variables](https://cs50.harvard.edu/python/2022/notes/0/ variables) Variables|variables]] 
- the `if` [[Python_Notebook#' if ' Statement|statement]] compares x and y
- If the condition of `x < y` is met, the `print` statement is executed.
    
>If statements use `bool` or [[Python_Notebook#Boolean Values|boolean]] values (true or false) to decide whether or not to execute. If the statement of `x > y` is true, the compiler will register it as `true` and execute the code.

```python
x = int(input("What's x? "))
y = int(input("What's y? "))

if x < y:
    print("x is less than y")
if x > y:
    print("x is greater than y")
if x == y:
    print("x is equal to y")
```

- the first `if` [[Python_Notebook#' if ' Statement|statement]] is evaluated
- Then, the second `if` statement is evaluated
- and so on
	- This flow of decisions is called “control flow.”
![[Pasted image 20230305140656.png|200]]
### ' elif ' Statement
#elif #statement 
Can be improved by not asking three consecutive questions:
```python
x = int(input("What's x? "))
y = int(input("What's y? "))

if x < y:
    print("x is less than y")
elif x > y:
    print("x is greater than y")
elif x == y:
    print("x is equal to y")
```
- [[Python_Notebook#' elif ' Statement|elif]] allows the program to make less decisions
	- the `if` statement is evaluated
		- If this statement is found to be [[Python_Notebook#Boolean Values|true]], all the `elif` statements not be run at all
	- if the `if` statement is found to be false, the first `elif` will be evaluated. 
		- If this is true, it will not run the final evaluation.
![[Pasted image 20230305140815.png|400]]
    
````python
pet_type = "fish" 

if pet_type == "dog":
	print("You have a dog.")
elif pet_type == "cat":
	print("You have a cat.")
elif pet_type == "fish"
	# this is performed
	print("You have a fish.")
else: 
	print("Not sure!")
````
    
<span style='color:#20bf6b'>elif</span> statement allows for continued checks to be performed after an initial <span style='color:#20bf6b'>if</span> statement. 
    
<span style='color:#20bf6b'>elif</span> differs from <span style='color:#20bf6b'>else</span> statement because another expression is provided to be checked, same as <span style='color:#20bf6b'>if</span> statement
    
<span style='color:#20bf6b'>True</span> = indented code following<span style='color:#20bf6b'> elif</span> is executed
    
<span style='color:#20bf6b'>False</span> = the code can continue to an optional <span style='color:#20bf6b'>else</span> statement
    
Multiple <span style='color:#20bf6b'>elif</span> statements can be used following an initial <span style='color:#20bf6b'>if</span> to perform a series of <mark style='background:#20bf6b'>checks</mark>. 
    
Once <span style='color:#20bf6b'>elif</span> expression evaluates to <span style='color:#20bf6b'>True</span>, no further <span style='color:#20bf6b'>elif</span> statements are executed.
    
> [!TIP] less tasks = less use of server
    
### ' else ' Statement
#else #statement 
```python
x = int(input("What's x? "))
y = int(input("What's y? "))

if x < y:
    print("x is less than y")
elif x > y:
    print("x is greater than y")
else:
    print("x is equal to y")
```

![[Pasted image 20230305140951.png|400]]

    
```python
# else Statement

test_value = 50

if test_value < 1: 
	print("Value is < 1")
else:
	print("Value is >= 1")

test_string = "VALID"

if test_string == "NOT VALID":
	print("String equals NOT_VALID")
else:
	print("String equals something else!")
```

<span style='color:#20bf6b'>else</span> Statement provides alternative code to execute if the expression in an <span style='color:#20bf6b'>if</span> statement evaluates to <span style='color:#20bf6b'>False</span>. 
    
The indented code for the <span style='color:#20bf6b'>if</span> statement is executed if the expression evaluates to <span style='color:#20bf6b'>True</span>. 
    
The indented code immediately following the <span style='color:#20bf6b'>else</span> is executed only if the expression evaluates to <span style='color:#20bf6b'>False</span>. 
    
To mark the end of the <span style='color:#20bf6b'>else</span> block, the code must be unindented to the same level as the starting <span style='color:#20bf6b'>if</span> line.

### `match` Statement
#match #case
The `match` statement is used to perform pattern matching on a value, and consists of several branches, each of which contains a pattern and the code to execute if the pattern matches
```python
def describe(x):     
	match x:         
		case 0:             
			return "zero"         
		case 1:             
			return "one"         
		case _:             
			return "many"`
```
In this example, we define a function `describe` that takes a single argument `x`. The `match` statement is used to match `x` against several patterns. The first pattern `case 0:` matches the value `0`, and the code block following it returns the string `"zero"`. The second pattern `case 1:` matches the value `1`, and the code block following it returns the string `"one"`. The final pattern `case _:` matches any other value, and the code block following it returns the string `"many"`.
    
When we call the `describe` function with a value, the value is matched against the patterns in the `match` statement. If a pattern matches, the corresponding code block is executed and the result is returned. If no pattern matches, a `MatchError` is raised.
    
A match statement compares the value following the `match` keyword with each of the values following the `case` keywords. In the event a match is found, the respective indented code section is executed and the program stops the matching.
    
>[!TIP] `match` statements can be used to conditionally run code that matches certain values.

Harry Potter House Example: 
```python
  name = input("What's your name? ")

  match name: 
      case "Harry":
          print("Gryffindor")
      case "Hermione":
          print("Gryffindor")
      case "Ron": 
          print("Gryffindor")
      case "Draco":
          print("Slytherin")
      case _:
          print("Who?")
```
 `_`  symbol will match with any input = similar behavior as  [[Python_Notebook#' else ' Statement| else]] statement.

Further improve code:
```python
  name = input("What's your name? ")

  match name: 
      case "Harry" | "Hermione" | "Ron":
          print("Gryffindor")
      case "Draco":
          print("Slytherin")
      case _:
          print("Who?")
```
-  vertical bar `|` allows us to check for multiple values in the same `case` statement
	- similar to [[Python_Notebook#' or ' Operator|or]] keyword
## Operators
Allows you to allow program to make decisions. Also known as Conditional [[Python_Notebook#Statements|statements]] who compare a left-hand term to a right-hand term.
    
#operator #operation
- [[#Arithmatic operations|Arithmatic operations]]
- [[#Plus-Equals Operator|Plus-Equals Operator]]
- [[#Modulo Operator|Modulo Operator]]
- [[#print() Function|print() Function]]
- [[#' or ' Operator|' or ' Operator]]
- [[#Equal Operator ' == '|Equal Operator ' == ']]
- [[#Not Equals Operator ' != '|Not Equals Operator ' != ']]
- [[#Comparison Operators|Comparison Operators]]
- [[#' and ' Operator|' and ' Operator]]
- [[#' not ' Operator|' not ' Operator]]
### Arithmatic operations
#math #operator
```
result = 10 + 30
result = 40 - 10
result = 50 * 5
result = 16 / 4      # always returns a floating point
result = 16 // 4     # always returns an interger unless used with a float
result = 25 % 2
result = 5 ** 3
```

% for moduls (returns the remainder)
** for exponentiation

#### Division

```python
print(6 / 4)

print(6 // 4)

print(6 // 4.)
print(6. // 4)
print(6. // 4.)

print(-6 / 4)
print(-6 // 4)
print(6. // -4)
```

**NOTE** When using a float, will return a float, except division will always return a float unless using the proper notation for an interger to be returned. 

**NOTE** Integer division can also be called **floor division**

#### Exponents

The result clearly shows that **the exponentiation operator uses right-sided binding**.

```python
print(2 ** (2 ** 3))
print(2 ** 2 ** 3)
print((2 ** 2) ** 3)
```

### Plus-Equals Operator
#PlusEqual #operator 
```python
# Plus-Equal Operator

counter = 0
counter += 10

# this is equivalent to

counter = 0
counter = counter + 10

# The operator will also perform string concatenation

message = “Part 1 of message”
message += “Part 2 of message”
```

Provides way to add a value to an existing variable and assign the new value back to the same variable.

In the case where the variable and the value are strings, this operator performs string concatenation instead of addition

The operator is performed in place, meaning that any other variable being updated will also be updated 

### Modulo Operator
#Modulo #math #operator 
- The **modulo** `%` operator in programming allows one to see if two numbers divide evenly or divide and have a remainder.
	- even or odd operator 
	- 4 % 2 would result in zero, because it evenly divides. However, 3 % 2 does not divide evenly and would result in a number other than zero
```python
# Mudulo operations 

zero = 8 % 4

nonzero = 12 % 5
```

A modulo calculation returns the **<span style='color:#20bf6b'>remainder of a division</span>** between the first and second number. 

Example: 
	- 4 % 2 = 0 because 4 is evenly divisible by 2 leaving no remainder
	- 7 % 3 = 1 because 7 is not evenly divisible by 3, leaving a remainder of 1

```python
x = int(input("What's x? "))

if x % 2 == 0:
    print("Even")
else:
    print("Odd")
```

##### Creating a Parity Function
```python
def main():
    x = int(input("What's x? "))
    if is_even(x):
        print("Even")
    else:
        print("Odd")
 
 
def is_even(n):
    return n % 2 == 0
```

The `if` statement `is_even(x)` works, even though there is no operator there. This is because our function returns a `bool` (or boolean), true or false, back to the main function. The `if` statement simply evaluates whether or not `is_even` of `x` is true or false.

 ```python
def main():
    x = int(input("What's x? ")
    if is_even(x):
        print("Even")
    else:
        print("Odd")


def is_even(n):
    if n % 2 == 0:
        return True
    else:
        return False


main()
```
    
```python
def main():
    x = int(input("What's x? ")
    if is_even(x):
        print("Even")
    else:
        print("Odd")


def is_even(n):
    return True if n % 2 == 0 else False


main()
```
    
```python
def main():
    x = int(input("What's x? ")
    if is_even(x):
        print("Even")
    else:
        print("Odd")

def is_even(n):
    return True if n % 2 == 0 else False

main()
```

### print() Function
#print #operator 
```python
print("hello World!")
print(100)
pi = 3.14159
print(pi)
```

This function is used to output text, numbers, or other printable information to the console. 
    
It takes one or more arguments and will output each of the arguments to the console seperated by a space. If no arguments are provided, the <span style='color:#20bf6b'>print()</span> function will output a blank line. 

### ' or ' Operator
#or #operator 

Allows your program to decide between one or more alternatives
```Python
True or True     # Evaluates to True
True or False    # Evaluates to True
False or False   # Evaluates to False
1 < 2 or 3 < 1   # Evaluates to True
3 < 1 or 1 > 6   # Evaluates to False
1 == 1 or 1 < 2  # Evaluates to True
```

<span style='color:#20bf6b'>Or</span> Operator combines **two Boolean expressions** and evaluates to <span style='color:#20bf6b'>True</span> if at least one of the expressions returns <span style='color:#20bf6b'>True</span>. 

If both expressions are <span style='color:#20bf6b'>False</span>, then the entire expression evaluates to <span style='color:#20bf6b'>False</span>. 

```python
x = int(input("What's x? "))
y = int(input("What's y? "))

if x < y or x > y:
    print("x is not equal to y")
else:
    print("x is equal to y")
```

![[Pasted image 20230306123832.png|300]]
### Equal Operator ' == '
#equal #operator 

```python
# Equal Operator

if 'Yes' == 'Yes':
	# evaluates to True
	print('Both expressions give the same result')

c = '2'
d = 2

if c == d:
	print('They are equal')

if c == d:
	print('They are equal')
else: 
	print('They are not equal')
```

<span style='color:#20bf6b'>==</span> is used to compare two values, variables or expressions to determine if they are the same. 
	- same values being compared = <span style='color:#20bf6b'>True</span>
	- otherwise = <span style='color:#20bf6b'>False</span>

The operator takes the data type into account when making the comparison, so a string value of <span style='color:#20bf6b'>"2"</span> is not considered the same as a numeric value of <span style='color:#20bf6b'>2</span>
```python
x = int(input("What's x? "))
y = int(input("What's y? "))

if x == y:
    print("x is equal to y")
else:
    print("x is not equal to y")
```

![[Pasted image 20230305141015.png|400]]
### Not Equals Operator ' != '
#NotEqual #Operator
```python
# Not Equals Operator

if "Yes" != "No":
	# evaluates to True
	print("They are NOT equal")

val1 = 10
val2 = 20

if val1 != val2:
	print("They are NOT equal")

if (10 > 1) != (10 > 1000):
	# True != False
	print("They are NOT equal")
```

<span style='color:#20bf6b'>!=</span> is used to compare two values, variables or expressions to determine if they are NOT the same. 

<span style='color:#20bf6b'>True</span> = Not the same
<span style='color:#20bf6b'>False</span> = They are the same

The operator takes the data type into account, meaning a value of<span style='color:#20bf6b'> 10</span> would NOT be equal to the string value <span style='color:#20bf6b'>"10"</span> and the operator would return <span style='color:#20bf6b'>True</span>. 

If expressions are used, then they are evaluated to a value of <span style='color:#20bf6b'>True</span> or <span style='color:#20bf6b'>False</span> before the comparison is made by operator. 

```python
x = int(input("What's x? "))
y = int(input("What's y? "))

if x != y:
    print("x is not equal to y")
else:
    print("x is equal to y")
```

![[Pasted image 20230306123941.png|400]]

### Comparison Operators 
#Comparison #Operator

Relational operators compare two values or expressions

'<' less than
'>' greater than
'<='  less than or equal to 
'>=' greater than or equal to

```python
a = 2
b = 3
a < b  # Evaluates to True
a > b  # Evaluates to False
a >= b # Evaluates to False
a <= b # Evaluates to True
a <= a # Evaluates to True
```

If the relation is sound, then the entire expression will evaluate to <span style='color:#20bf6b'>True</span>. If not =<span style='color:#20bf6b'> False</span>. 

### ' and ' Operator
#and #Operator

Similar to [[#' or ' Operator|or]]
```python
True and True     # Evaluates to True
True and False    # Evaluates to False
False and False   # Evaluates to False
1 == 1 and 1 < 2  # Evaluates to True
1 < 2 and 3 < 1   # Evaluates to False
"Yes" and 100     # Evaluates to True
```

Performs a Boolean comparison between two Boolean values, variables or expressions.
>- If both sides of the operator evaluate to <span style='color:#20bf6b'>True</span> then the and operator returns <span style='color:#20bf6b'>True</span>. 
>- If either side (or both sides) evaluates to <span style='color:#20bf6b'>False</span>, then the and operator returns <span style='color:#20bf6b'>False</span>. 

A non-Boolean value (or variable that stores a value) will always evaluate to <span style='color:#20bf6b'>True</span>

```python
score = int(input("Score: "))

if score >= 90 and score <= 100:
    print("Grade: A")
elif score >=80 and score < 90:
    print("Grade: B")
elif score >=70 and score < 80:
    print("Grade: C")
elif score >=60 and score < 70:
    print("Grade: D")
else:
    print("Grade: F")
```
^Has potential for bugs, never trust user to input the correct information

Improve code: 
```python
# Demonstrates fewer comparisons
 
score = int(input("Score: "))
 
if score >= 90:
    print("Grade: A")
elif score >= 80:
    print("Grade: B")
elif score >= 70:
    print("Grade: C")
elif score >= 60:
    print("Grade: D")
else:
    print("Grade: F")
```

### ' not ' Operator
#not #Operator

```python
not True    # Evaluates to False
not False   # Evaluates to True
1 > 2       # Evaluates to False
not 1 > 2   # Evaluates to True
1 == 1      # Evaluatesto True
not 1 == 1  # Evaluates to False
```

Is used in a Boolean expression in order to evaluate the expression to its inverse value. 
> If the original expression was <span style='color:#20bf6b'>True</span>, including the <span style='color:#20bf6b'>not</span> operator would make it <span style='color:#20bf6b'>False</span>, and vice versa. 

### Shortcut Operators
#shortcut 
Very often, we want to use one and the same variable both to the right and left sides of the = operator.

For example, if we need to calculate a series of successive values of powers of 2, we may use a piece like this:

```python
x = x * 2
```

You may use an expression like this if you can't fall asleep and you're trying to deal with it using some good, old-fashioned methods:

```python
sheep = sheep + 1
```

Python offers you a shortened way of writing operations like these, which can be coded as follows:

```python
x *= 2
sheep += 1
```

Let's try to present a general description for these operations.

If `op` is a two-argument operator (this is a very important condition) and the operator is used in the following context:

```python
variable = variable op expression 
```

It can be simplified and shown as follows:

```python
variable op= expression 
``` 

Take a look at the examples below. Make sure you understand them all.

```python
print(i = i + 2 * j) 
print(i += 2 * j)

print(var = var / 2) 
print(var /= 2)

print(rem = rem % 10) 
print(rem %= 10)

print(j = j - (i + var + rem)) 
print(j -= (i + var + rem))

print(x = x ** 2)
print(x **= 2)
```

## Error Codes
#error 

The Python interpreter will report errors in code <span style='color:#20bf6b'>^</span>

**Table of Contents**
- [[#Errors|Errors]]
- [[#ZeroDivisionError|ZeroDivisionError]]
- [[#SyntaxError|SyntaxError]]
- [[#NameError|NameError]]
- [[#IndexError|IndexError]]
- [[#IndentationError|IndentationError]]
- [[#Other Error Codes|Other Error Codes]]
	- [[#Other Error Codes#Infinite Loop Error|Infinite Loop Error]]
	- [[#Other Error Codes#KeyError|KeyError]]
### Errors
#error
```python
if False ISNOTEQUAL True:
                  ^
SyntaxError: invalid syntax
```
Most error cases, the interpreter place a ^ under the portion of the line of code where the error is detected. 
### ZeroDivisionError
#zerodivision #error 
```python
numerator = 100
denominator = 0
bad_results = numerator / denominator

ZeroDivisionError: division by zero
```
Reported when detects a division operation is being performed and the denominator is 0. 
- dividing by 0 has no defined value
- can also happen if a variable is used as the denominator and its value has been set to or changed to 0. 
### SyntaxError
#syntax #error 
```python
age = 7 + 5 = 4

File "<stdin>", line 1
SyntaxError: can't assign to operator
```
Reported when some portion of the code is incorrect. 
>This can include: 
- misspelled keywords, 
- missing or too many bracket or parenthesis,
-  incorrect operators, 
- missing or too many quotation marks, 
- other conditions
### NameError
#name #error 
```python
misspelled_variable_name

NameError: name 'misspelled_variable_name' is not defined
```
Detects a variable that is unknown. 
	- occurs when variable is used before it has been assigned a value 
	- if a variable name is spelled differently than the point at which it was defined
### IndexError
#index #error 
```python
fruit = "Berry"
indx = fruit(6)
```
Generated when trying to access an index that doesn't exist. 
### IndentationError
#error #indent 
See [[#Python For Loop]] notes
### Other Error Codes
#error 
#### Infinite Loop Error
See [[#Infinite Loop]] notes
#### KeyError
#error 
See [[#Accessing and Writing Data in a Python Dictionary]] notes
## Lists
#lists #python #list 
- [[#Adding Lists Together|Adding Lists Together]]
- [[#Python Lists: Data Types|Python Lists: Data Types]]
- [[#Zero Indexing|Zero Indexing]]
- [[#List Indices|List Indices]]
- [[#Negative List Indices|Negative List Indices]]
- [[#Modifying 2D Lists|Modifying 2D Lists]]
- [[#Accessing 2D Lists|Accessing 2D Lists]]
- [[#List Method|List Method]]
	- [[#List Method#.append( )|.append( )]]
	- [[#List Method#.remove( )|.remove( )]]
	- [[#List Method#.count( )|.count( )]]
	- [[#List Method#.sort ( )|.sort ( )]]
	- [[#List Method#.insert( )|.insert( )]]
	- [[#List Method#.pop( )|.pop( )]]
- [[#Determining List Length with len( )|Determining List Length with len( )]]
- [[#List Slicing|List Slicing]]
- [[#sorted ( ) Function|sorted ( ) Function]]

```python
primes = [2, 3,5,7,11]
print(primes)

empty_list = []
```

Lists = ordered collections of items that allow for easy use of a set of data

placed between <span style='color:#20bf6b'>[  ]</span> and seperated by commas. 

Values in list can be repeated

Empty lists do not contain any values within the square brackets. 
### Adding Lists Together
#addlist #python #list 
```python
items = ['cake', 'cookie', 'bread'
total_items = items + ['biscuit', 'tart']
print(total_items)
# Result: ['cake', 'cookie', 'bread', 'biscuit', 'tart']
```

Add lists together using <span style='color:#20bf6b'>+</span>
> results in new list containing the same items in the same order with the first list's items coming first. 

Note: this will not work for adding one item at a time (use [[#.append( )]] method). In order to add one item, create a new list with a single value and then use the plus symbol to add the list. 

### Python Lists: Data Types
#datatype #PythonList #list #python 

```python
numbers = [1, 2, 3, 4, 10]
names = ['Jenny', 'Sam', 'Alexis']
mixed = ['Jenny', 1, 2]
list_of_lists = [['a', 1], ['b', 2]]
```

Lists are a versatile data type that can contain multiple different data types within the same square brackets. 
>numbers, strings, other objects, and even other lists. 

### Zero Indexing 
#index #list #zero #python 
```python
names = ['Roger', 'Rafael', 'Andy', 'Novak']
```

List index begins at zero and ends at length of the list minus one. 
>ex., in this list <span style='color:#20bf6b'>'Andy'</span> is found at index <span style='color:#20bf6b'>2</span>

### List Indices 
#Index #list #python 
```python
berries = ["blueberry", "cranberry", "raspberry"]

berries[0]   # "blueberry"
berries[2]   # "raspberry"
```

Python list elements are ordered by index
>- Index = a number referring to their placement in the list. 
>- List indices start at 0 and increment by one. 

To access a list element by index, square bracket notation is used: <span style='color:#20bf6b'>list[index]</span>

### Negative List Indices
#Negative #index #list #python 
```python
soups = ['minestrone', 'lentil', 'pho', 'laksa']
soups[-1]   # 'laksa'
soups[-3]   # 'lentil', 'pho', 'laksa'
soups[-2]   # 'minestrone', 'lentil'
```

Can be used to reference elements in relation to the end of a list. 
>Used to access single list. This can be used to access single list elements or as part of defining a list range. 

>- to select the last element <span style='color:#20bf6b'>`my_list[-1]`</span>
>- to select the last three elements <span style='color:#20bf6b'>`my_list[-3:]`</span>
>- to select everything except the last two elements <span style='color:#20bf6b'>`my_list[:-2]`</span>

### Modifying 2D Lists
#modify #2D #list #python #modifylist 
```python
# A 2D list of names and hobbies
class_name_hobbies = [["Jenny", "breakdancing"], ["Alexus", "Photography"], ["Grace", "Soccer"]]

# The sublist of Jenny is at index 0. The hobby is at index 1 of the sublists.
class_name_hobbies[0][1] = "Meditation"
print(class_name_hobbies)

# Output
# [["Jenny", "Meditation"], ["Alexus", "Photography"], ["Grace", "Soccer"]]
```

In order to modify elements in a 2D list, an index for a sublist and the index for the element of the sublist need to be provided. 

Format: 
>- `list[sublist_index]`
>- `[element_in_sublist_index] =`
>- `new_value`

### Accessing 2D Lists
#2D #list #accesslist #python 
```python
# 2D list of people"s heights
heights = [["Noelle", 61], ["Ali", 70], ["Sam", 67]]
# Access the sublist at the index 0, and then access the 1st index of that sublist. 
noelles_height = heights[0][1]

print(noelles_height)

# Output
# 61
```

To access: an index for the sublist and the index for element of the sublist both need to be provided

Format: 
> - `list[sublist_index`
> - `element_in_sublist_index`

### List Method
#method #list #python 
- [[#.append( )|.append( )]]
- [[#.remove( )|.remove( )]]
- [[#.count( )|.count( )]]
- [[#.sort ( )|.sort ( )]]
- [[#.insert( )|.insert( )]]
- [[#.pop( )|.pop( )]]
#### .append( )
#append #list #python 

```python
orders = ['daisies', 'periwinkle']
orders.append('Tulips')
print(orders)
# Result: ['daisies', 'periwinkle', 'tulips']
```

Add values to the end of a list using <span style='color:#20bf6b'>.append( )</span> method. 
> This will place the object passed in as a new element at the very end of a list. Printing the list afterwards will visually show the appended value. 

<span style='color:#eb3b5a'>DO NOT</span> confuse with returning an entirely new list with the passed object. 

#### .remove( )
#list #remove #python 
```python
# Create a list 
shopping_line = ["Cole", "Kip", "Chris", "Sylvana", "Chris"]

# Removes the first occurance of "Chris"
shopping_line.remove("Chris")
print(shopping_line)

# Output
# ["Cole", "Kip", "Sylvana", "Chris"]
```

Used to remove an element from a list by passing in the value of the element to be removed as an argument. 

In cases where two or more elements in the list have the same value, the first occurence of the element is removed. 

#### .count( )
#list #count #python 
```python
backpack = ['pencil', 'pen', 'notebook', 'textbook', 'pen', 'highlighter', 'pen']
numPen = backpack.count('pen')

print(numPen)
# Output: 3
```

Searches a list for whatever term it receives as an argument, then returns the number of matching entries found. 

#### .sort ( )
#list #sort #python 
```python
exampleList = [4, 2, 1, 3]
exampleList.sort()
print(exampleList)
# Output: [1, 2, 3, 4]
```

Will sort the contents of whatever list it is called on. 
> Numerical lists will be sorted in ascending order, and lists of Strings will be sorted into alphabetical order. It modifies the original list, and has no return value

#### .insert( )
#insert #list #python 
```python
# Here is a list representing a line of people at a store
store_line = ["Karla", "Maxium", "Martin", "Isabella"]

# Here is how to insert "Vikor" after "Maxium" abd before "Martin"
store_line.insert(2, "Vikor")

print(store_line)
# Output: ['Karla', 'Maxium', 'Vikor', 'Martin', 'Isabella']
```

Allows to add an element to a specific index in a list. 

It takes in two inputs: 
>- The index that you want to insert into
>- The element that you want to inser at the specified index

#### .pop( )
#remove #list #pop #python 
```python
cs_topics = ["Python", "Data Structures", "Balloon Making", "Algorithms", "Clowns 101"]

# Pop the last element 
removed_element = cs_topics.
pop()

print(cs_topics)
print(removed_element)

# Output:
# ['Python', 'Data Structures', 'Balloon Making', 'Algorithms']
# 'Clowns 101'

# Pop the element "Balloon Making"
cs_topics.pop(2)
print(cs_topics)

# output
# ['Python', 'Data Structures', 'Balloon Making', 'Algorithms']
# 'Clowns 101'

# pop the element "Baloon Making"
cs_topics.pop(2)
print(cs_topics)

# Output:
# ['Python', 'Data Structures', 'Algorithms']
```

Allows us to remove an element from a list while also returning it. 
>It accepts one optional input which is the index of the element to remove. 

If no index is provided, the last element in list will be removed and returned

### Determining List Length with len( )
#length #list #len #python 
```python
knapsack = [2, 4, 3, 7, 10]
size = len(knapsack)
print(size)
# Output: 5
```

Can be used to determine the number of items found in the lists it accepts as an argument. 

### List Slicing
#list #slice #python #python 
```python
tools = ['pen', 'hammer', 'lever']
tools_slice = tools[1:3] # ['hammer', 'lever']
tools_slice[0] = 'nail'

# Original list is unaltered:
print(tools) # ['pen', 'hammer', 'lever']
```

Slice = sublist of Python list elements

Can be selected from a list using a colon-separated starting and ending point

Syntax Pattern:
>`mylist[START_NUMBER:END_NUMBER].` The slice will include the `START_NUMBER` index, and everything until but excluding the `END_NUMBER` item. 

### sorted ( )
#sort #list #python 
```python
unsortedList = [4, 2, 1, 3]
sortedList = sorted(
unsortedList)
print(sortedList)
# Output: [1, 2, 3, 4]
```

Accepts a list as an argument and will return a new, sorted list containing the same elements as the original. 
>Numerical list = ascending order
>Lists with Strings = alphabetical order

Will not modify the original, unsorted list. 

## Loops
#python #loops 
Loops do something over and over again
    
- [[#'break' Keyword|'break' Keyword]]
- [[#List Comprehension|List Comprehension]]
- [[#'for' Loop|'for' Loop]]
- [[#'continue' Keyword|'continue' Keyword]]
- [[#Loops with 'range( )'|Loops with 'range( )']]
- [[#Infinite Loop|Infinite Loop]]
- [[#'while' Loops|'while' Loops]]
- [[#Nested Loops|Nested Loops]]
### 'break' Keyword
#break #keyword #loop #python 

```python
numbers = [0, 254, 2, -1, 3]

for num in numbers:
  if (num<0):
    print("Negative number detected!")
    break
  print(num)

# 0
# 254
# 2
# Negative number detected!
```

In a loop, the break keyword escapes the loops, regardless of the iteration number. Once break executes, the program will continue to execute after the loop. 

### List Comprehension
#python #list #loop 

```python
# List comprehension for the squares of all even numbers between 0 and 9
result = [x**2 for x in range (10) if x % 2 == 0]

print(result)
# [0, 4, 16, 36, 64]
```

Provides a concise way for creating lists. It consists of brackets containing an expression followed by a for clause, then zero or more for or if clauses: . <span style='color:#20bf6b'>[ EXPRESSION for ITEM in LIST *IF CONDITIONAL*]</span>

The expressions can be anything - any kind of object can go into a list.

A list comprehension always returns a list. 

### 'for' Loop 
#for #loop #python 

```python
for <temporary variable> in <list variable>:
  <action statement>
  <action statement>
#each num in nums will be printed below
nums = [1,2,3,4,5]
for num in nums:
  print(num)
```

Used to iterate over a list of items and perform a set of actions on each item. 

Syntax consists of assigning a temporary value to a variable on each successive iteration. 

Remember to properly indent each action, otherwise an [[#IndentationError]] will result. 

### 'continue' Keyword
#continue #loop #python #keyword 

```python
big_number_list = [1, 2, -1, 4, -5, 5, 2, -9,]

# Print only positive numbers:
for i in big_number_list:
  if i < 0:
    continue
  print(i)
```

Used inside  a loop to skip the remaining code inside the loop to skip the remaining code inside the loop code block and begin the next loop iteration. 

### range( )
#range #loop #python 
```python
# Print the numbers 0, 1, 2: 
for i in range(3):
  print(i)

# Print "WARNING" 3 times: 
for i in range(3):
  print("WARNING")
```

The <span style='color:#20bf6b'>for</span> loop is used to perform an action a specific set of times in a row.

The <span style='color:#20bf6b'>range( )</span> function can be used to create a list that can be used to specify the number of iterations in a <span style='color:#20bf6b'>for</span> loop.

### Infinite Loop
#infinite #loop #python 
A loop that never terminates. 
> Results when the conditions of the loop prevent it from terminating. This could be due to a typo in the conditional statement within the loop or incorrect logic. 

To interrupt a program that is running forever, press <span style='color:#20bf6b'>ctrl</span> + <span style='color:#20bf6b'>C </span>

Also see [[#Infinite Loop Error]]

### 'while' Loops
#python #while #loop 
Will repeat a block of code over and over again

```python
i = 3
while i != 0:
	print("meow") # infinite loop, will never stop
```

Fix: 
```python
i = 3
while i != 0:
  print("meow")
  i = i - 1

# output: 
			# meow
			# meow
			# meow
```

![[Pasted image 20230308093311.png|300]]
- Defines a variable `i` with an initial value of 3, and then enters a `while` loop that will continue as long as the value of `i` is not equal to 0.
    
- Inside the loop, the code prints the string "meow" to the console using the [[Python_Notebook#print() Function|print()]] function. Then, it decrements the value of `i` by 1 using the assignment operator `-=`. This means that each time through the loop, the value of `i` will be decreased by 1.
    
- When `i` reaches the value of 0, the condition of the `while` loop will be `False`, and the loop will terminate. At this point, the code will exit the loop and move on to any subsequent code that follows
```python
# This loop will only run 1 time
hungry = True
while hungry:
  print("time to eat!")
  hungry = false

# This loop will run 5 times 
i = 1
while i <6:
  print(i)
  i = i + 1
```

It will repeatedly execute a code block as long as the condition evaluates to True. 
    
The condition of a <span style='color:#20bf6b'>while</span> loop always checked first before the block code runs. If the condition is not met initially, then the code block will never run. 

### Nested Loops
#nest #nested #loop #python 

```python
groups = [["Jobs", "Gates"],["Newton", "Euclid"],["Einstein", "Feynman"]]

# This outer loop will iterate over each list in the groups list
for group in groups:
  # This inner loop will go through each name in each list 
  for name in group:
    print(name)
```

Loops can be nested inside other loops. Nested loops can be used to access items of lists which are inside other lists. 
> The item selected from the outer loop can be used as the list for the inner loop to iterate over. 

## Functions
#function #python #def #return 

Python has Built-in functions and the ability to create your own. 
    
See [Built-In Functions](https://docs.python.org/3/library/functions.html)
    
Function = action or verb
    
Functions have side effects --> audio, visual, etc
    
Some tasks need to be performed multiple times within a program. Rather than rewrite the same code in multiple places, a function my be defined using the <span style='color:#20bf6b'>def</span> keyword. 
    
Example of Built-in Function `print()`:
```python
# Demonstrates a function with a positional argument

print("hello, world")
```
Example print("Hello, world!")
		- print = function --> It knows how to print to terminal
		- "Hello, world" = arguments
		- The `print` function takes arguments. In this case, `"hello, world"` are the arguments that the `print` function takes.
    
> Function definitions may include parameters, providing data input to the function. 

Example of a non built-in function:
```python
# Define a function my_function() with parameter x

def my_function(x):
  return x + 1

# Invoke the function

print(my_function(2))    # Output: 3
print(my_function(3+5))  # Output: 9
```

Functions may return a value using the <span style='color:#20bf6b'>return</span> keyword followed by the value to return.
    
**Table of Contents**
- [[#Def|Def]]
- [[#Function Parameters|Function Parameters]]
- [[#Multiple Parameters|Multiple Parameters]]
- [[#Function Indentation|Function Indentation]]
- [[#Calling Functions|Calling Functions]]
- [[#Function Arguments|Function Arguments]]
- [[#Function Keyword Arguments|Function Keyword Arguments]]
- [[#Returning Value from Function|Returning Value from Function]]
- [[#Returning Multiple Values|Returning Multiple Values]]
- [[#The Scope of Variables|The Scope of Variables]]
- [[#Global Variables|Global Variables]]
- [[#Parameters as Local Variables|Parameters as Local Variables]]

### Def
```python
name = input("What's your name? ")
hello()
print(name)
```
This code throws an #error
	- no defined #function

```python
def hello():
    print("hello")


name = input("What's your name? ")
hello()
print(name)
```
- **everything under `def hello()` is indented**
	- must be or will treat as if it is not inside the `hello` function.

###### Pass values into functions
Further improve code: 
```python

# Create our own function
def hello(to):
    print("hello,", to)


# Output using our own function
name = input("What's your name? ")
hello(name)
```
You are telling the compiler that this function takes a single parameter: a variable called `to`. Therefore, when you call `hello(name)` the computer passes `name` into the `hello` function as `to`

Change code to add a default value to `hello`:
```python
# Create our own function
def hello(to="world"):
    print("hello,", to)


# Output using our own function
name = input("What's your name? ")
hello(name)

# Output without passing the expected arguments
hello()
```

The first `hello` as expected and the second hello, which is not passed a value, will by default output `hello, world`.

we need to tell the compiler that we have a #main function and we have a separate #hello function:
```python
def main():

    # Output using our own function
    name = input("What's your name? ")
    hello(name)

    # Output without passing the expected arguments
    hello()


# Create our own function
def hello(to="world"):
    print("hello,", to)
```
- This code throws an #error
	- nothing in this code is actually calling the `main` function

Small mod to fix this: #main function
```python
def main():

    # Output using our own function
    name = input("What's your name? ")
    hello(name)

    # Output without passing the expected arguments
    hello()


# Create our own function
def hello(to="world"):
    print("hello,", to)


main()
```
Restored!

###### More on `main`
[[Python_Notebook#main__ in Python|Main in Python]]
    
### Function Parameters
#function #parameter #python 

```python
def write_a_book(character, setting, special_skill):
  print(character + " is in " +
        setting + " Practicing her " + 
        special_skill) 
```

Sometimes functions require input to provide data for their code.
> Defined using parameters. 

parameters = variables defined in the function definition. 
> They are assigned the values which were passed as arguments when the function was called elsewhere in the code

Example: 
> the function definition defines parameters for a character, a setting and a skill, which are used as inputs to write the first sentence of a book. 

### Multiple Parameters

#multiple #parameter #python 

```python
def ready_for_school(backpack, pencil_case):
  if (backpack == 'full' and pencil_case == 'full'):
    print ("I'm ready for school!")
```

Functions can have multiple parameters, they may need more than one input to carry out their operations. 

To define a function:
> - Place names one after another
> - Must be seperated by commas
> - All within the parenthesis of the function

### Function Indentation
#function #indent #python 

```python
# Indentation is used to identify code blocks

def testfunction(number):
  # This code is part of testfunction
  print("Inside the testfunction")
  sum = 0
  for x in range(number):
    # More indentation because 'for' has a code block
    # but still part of the function
    sum += x
  return sum
print("This is not part of testfunction")
```

Indentation is used to identify blocks of code. 
> - Code within the same block should be indented at the same level. 
> - All code under a function declaration should be indented to identify it as part of the function. 
> - There can be additional indentation within a function to handle other statements so long as the lines are not indented less than the first line of the function code. 

### Calling Functions
#call #function #python 

```python
doHomework()
```

Python uses simple syntax to use, invoke or call a pre-existing function, called by writing the name of it, followed by parentheses. 

### Function Arguments
#function #argument #python #parameter
```python
def sales(grocery_store, item_on_sale, cost):
  print(grocery_store + " is selling " + item_on_sale + " for " + cost)

sales("The farmer's Market", "toothpaste", "$1")
```

Parameters in python are variables --- placeholders for actual values the function needs. When the function is called, these values are passed as arguments. 

### Function Keyword Arguments
#function #python #keyword #argument 

```python
def findvolume(length=1, width=1, depth=1):
  print("length =" + str(length))
  print("Width = " +str(width))
  print("Depth = " + str(depth))
  return length * witdth * depth;

findvolume(1, 2, 3)
findvolume(length=5, depth=2, width=4)
findvolume(2, depth=3, width=4)
```

Keyword argument = when function arguments are passed using their names. 

Python functions can be defined with named arguments which may have default values provided. The use when calling a function allows the arguments to be passed in any order -- not just the order defined. 

If the function is invoked without a value specific argument, the default will be used. 

### Returning Value from Function
#return #function #python #statement 
    
```python
def main():
    x = int(input("What's x? "))
    print("x squared is", square(x))


def square(n):
    return n * n


main()
```
<span style='color:#20bf6b'>return</span> keyword is used to return a value from a function. 
> Returned value can be assigned to a variable which can then be used in the program
    
```python
def check_leap_year(year):
  if year % 4 == 0:
    return str(year) + " is a leap year. "
  else: 
    return str(year) + " is not a leap year."

year_to_check = 2018
returned_value = check_leap_year(year_to_check)
print(returned_value)  # 2018 is not a leap year. 
```
    
<span style='color:#20bf6b'>check_leap_year</span> returns a string which indicates if the passed parameter is a leap year or not
    
### Returning Multiple Values
#return #python #function #statement 

```python
def square_point(x,y,z):
  x_squared = x * x
  y_squared = y * y
  z_squared = z * z
  # Return all three values: 
  return x_squared, y_squared, z_squared

three_squared, four_squared, five_squared = squared_point(3, 4, 5)
```

Functions are able to return multiple values using one <span style='color:#20bf6b'>return</span> statement. 
> All values that should be returned are listed after the <span style='color:#20bf6b'>return</span> keyword and are seperated by commas. 

In this example, the function <span style='color:#20bf6b'>square_point()</span> returns <span style='color:#20bf6b'>x_squared</span>, <span style='color:#20bf6b'>y_squared</span> and <span style='color:#20bf6b'>z_squared</span>. 

### The Scope of Variables
#variable  #function  #python 
Local variable = variable defined inside a function
	- it cannot be used outside the scope of the function
		- attempting to do so without defining the variable outside of the function  will cause an error. 

```python
a = 5

def f1():
  a = 2
  print(a)

print(a)  # Will print 5
f1()      # Will print 2
```

- variable <span style='color:#20bf6b'>a</span> is defined both inside and outside the function
- When function <span style='color:#20bf6b'>f1()</span> is implemeted, <span style='color:#20bf6b'>a</span> is printed as <span style='color:#20bf6b'>2</span> 
	- it is locally defined to be so. 
- When printing <span style='color:#20bf6b'>a</span> outside of the of function, <span style='color:#20bf6b'>5</span> is printed 
	- it is implemented outside the scope of the function. 

### Global Variables 
#global #variable #function #python 

- Global variable:
	- A variable that is defined outside of a function. It can be accessed inside the body of a function.

```python
a = "Helllo"

def prints_a():
  print(a)

# will print "Hello"
prints_a()
```

- variable <span style='color:#20bf6b'>a</span> is a global variable
	- It is defined outside of the function <span style='color:#20bf6b'>prints_a()</span>
	- accessible to <span style='color:#20bf6b'>prints_a</span> which prints the value <span style='color:#20bf6b'>a</span>

### Parameters as Local Variables 
#local #variable #parameter #function #python 

Function parameters behave identically to a function's local variables. They are initialized with the values passed inti the function when it was called. 

Like local variables, parameters cannot be referenced from outside the scope of the function. 

```python
def my_function(value): 
  print(value) 

# Pass the value 7 into the function
my_function(7)

# Causes an error as `value` no linger exists
print(value)
```

- The parameter value is defined as part of the definition of <span style='color:#20bf6b'>my_function</span>
	- can only be accessed within <span style='color:#20bf6b'>my_function</span>. 
	- attempting to print the contents of <span style='color:#20bf6b'>value</span> from outside the function causes an error 

## Strings
#string #python 
`str` = string (in python) = sequence of text

Parameters = arguments that can be taken by a function

Sequences of characters are referred to as strings. Strings can be any length and can include any character such as letters, numbers, symbols, and whitespace (spaces, tabs, new lines).
    
Functions take arguments that influence their behaviour
```python
user = "User Full Name" 
game = 'Monopoly'

longer = "This string is broken up \
over multiple lines"
```
**Table of Contents**
- [[#Escaping Characters|Escaping Characters]]
- [[#Quotation Marks]]
- [[#The 'in' Syntax|The 'in' Syntax]]
- [[#Indexing and Slicing Strings|Indexing and Slicing Strings]]
- [[#Iterate String|Iterate String]]
- [[#Built-in Function 'len( )'|Built-in Function 'len( )']]
- [[#String Concatenation|String Concatenation]]
- [[#Immutable Strings|Immutable Strings]]
- [[#Formatting Strings|Formatting Strings]]
- [[#String Methods|String Methods]]
	- [[#String Methods#.format( )|.format( )]]
	- [[#String Methods#.lower( )|.lower( )]]
	- [[#String Methods#.strip( )|.strip( )]]
	- [[#String Methods#.title( )|.title( )]]
	- [[#String Methods#.split( )|.split( )]]
	- [[#String Methods#.find ( )|.find ( )]]
	- [[#String Methods#.upper( )|.upper( )]]
	- [[#String Methods#.join( )|.join( )]]
	- [[#String Methods#.replace( )|.replace( )]]
- [[#More on Strings]]
    
### Escaping Characters
#backslash #string #python #escape
Backslashes ( \ ) are used to escape characters in a Python string. 
```python
txt = "She said \"Never let go\"."
print(txt)  # She said "Never let go".
```
To print a sting with quotation marks, the given code snippet can be used. 
    
The `print()` function automatically include a piece of code `end='\n'.` 
	-  `\n` = [[Lecture 0 Transcript 1#^abb03a|new line]]
	- The print function takes an argument called end' and the default is to create a new line. 
	- you can provide an arguments for `end` so a new line isnt created. 
```python
# Ask the user for their name
name = input("What is your name? ")
print("hello,", end="")
print(name)
```
By providing  `end=""` we are over-writing the default value of `end` such that it never creates a [[Lecture 0 Transcript 1#^abb03a|new line]] after this first print statement.
     
### Quotation Marks
-   `print("hello,"friend"")` will not work and the compiler will throw an error.
-   Generally, there are two approaches to fixing this. First, you could simply change the quotes to single quote marks.
-   Another, more commonly used approach would be code as `print("hello, \"friend\"")`. The backslashes tell the compiler that the following character should be considered a quotation mark in the string and avoid a compiler error.
    
### The 'in' Syntax
#in #syntax #string #python 
```python
game = "Popular Nintendo Game: Mario KArt"

print("l" in game)  # Prints: True
print("x" in game)  # Prints: False
```
The <span style='color:#20bf6b'>in</span> syntax is used to determine if a letter or a substring exists in a string. It returns <span style='color:#20bf6b'>True</span> if a match is found, otherwise <span style='color:#20bf6b'>False</span> is returned. 
     
### Indexing and Slicing Strings 
#index #slice #string 

```python
str = "yellow"
str[1]   # => 'e'
str[-1]  # => 'w'
str[4:6] # => 'ow'
str[:4]  # => 'yell'
str[-3]  # => 'low'
```
    
Strings can be indexed using the same notation as lists, since strings are lists of characters. A single character can be accessed with brack notation(<span style='color:#20bf6b'>[index]</span>), or a substring can be accessed using slicing (<span style='color:#20bf6b'>[start:end]</span>).
    
Indexing with negative numbers counts from the end of the string. 
     
See also [[#List Slicing]]
    
### Iterate String 
#string #in #for 
```python
str = "hello"
for c in str:
  print(c)

# h
# e
# l
# l
# o
```

To iterate through a string, "for..in" notation is used. 
    
### len( )
#len #string 
```python
length = len("Hello")
print(length)
# Outpput: 5

colors = ['red', 'yellow', 'green']
print(len(colors))
# Output: 3
```

The built-in <span style='color:#20bf6b'>len()</span> function can be used to determine the length of an object. it can be used to compute the length of strings, lists, sets, and other countable objects. 

See also [[#Determining List Length with len( )]]
    
### String Concatenation 
#string #operator 
```python
# String concatenation

first = "Hello "
second = "World" 

result = first + second

long_result = first + second + "!"
```
The joining of strings together using the <span style='color:#20bf6b'>+</span> operator
->  also used for mathematical additions
    
If the parameters passed to the <span style='color:#20bf6b'>+</span> operator are strings, then concatenation will be performed. If the parameter passed to <span style='color:#20bf6b'>+</span> have different types, then Python will report an error condition. 
    
Multiple variables or literal strings can be joined together using <span style='color:#20bf6b'>+</span>
    
### Immutable Strings
#string 
Strings are immutable in Python. 
- Once a string has been defined, it can't be changed.
    
There are no mutating methods for strings. This is unlike data types like lists, which can be modified once they are created. 
    
### Formatting Strings
```python
# Ask the user for their name
name = input("whats your name? ")
print(f"hello, {name}")
```
`f` is a [[Lecture 0 Transcript 1#^5e2d51|special indicator]] to Python to treat this string a special way, different than previous approaches. 
	= most elegant way
     
### String Methods
- [[#.format( )|.format( )]]
- [[#.lower( )|.lower( )]]
- [[#.strip( )|.strip( )]]
- [[#.title( )|.title( )]]
- [[#.split( )|.split( )]]
- [[#.find ( )|.find ( )]]
- [[#.upper( )|.upper( )]]
- [[#.join( )|.join( )]]
- [[#.replace( )|.replace( )]]
    
#### .format( )
#string #format
```python
msg1 = 'Fred scored {} out of {} points.'
msg1.format(3, 10)
# => 'Fred scored 3 out of 10 points.'

msg2 = 'Fred {verb} a {adjective} {noun}.'
msg2.format(adjective='fluffy', verb='tickled', noun='hamster')
# => 'Fred tickled a fluffy hamster.'
```
<span style='color:#20bf6b'>.format()</span> replaces empty brace({}) placeholders in the string with its arguments. 
    
If keywords are specified within the placeholders, they are replaced with the corresponding named arguments to the method. 
#### .lower( )
#string #lower
```python
greeting = "Welcome To Chili's"

print(greeting.lower())
# Prints: welcome to chili's
```
    
The sting method<span style='color:#20bf6b'> .lower()</span> returns a string with all uppercase characters converted into lowercase. 
    
#### .strip( )
#string #strip
```python
text1 = '   apples and oranges   '
text1.strip()       # => 'apples and oranges'

text2 = '...+...lemons and limes...-...'

# Here we strip just the "." characters
text2.strip('.')    # => '+...lemons and limes...-'

# Here we strip both "." and "+" characters
text2.strip('.+')   # => 'lemons and limes...-'

# Here we strip ".", "+", and "-" characters
text2.strip('.+-')  # => 'lemons and limes'
```
<span style='color:#20bf6b'>.strip()</span> can be used to remove characters from the beginning and the end of a string. 
    
A string argument can be passed to the method, specifying the set of characters to be stripped. With no arguments to the method, whitespace is removed. 
    
#### .title( )
#string #title
```python
my_var = "dark knight"
print(my_var.title())

# Prints: Dark Knight
```
<span style='color:#20bf6b'>.title()</span> returns the string in title case. 
- the first letter of each word is capitalized
- the rest of the characters are lowercase
#### .split( )
#string #split

```python
text = "Silicon Valley"

print(text.split())
# Prints: ['Silicon', 'Valley']

print(text.split('i'))
# Prints: ['S', 'l', 'con Valley']
```
    
<span style='color:#20bf6b'>.split()</span> splits a string into a list of items: 
- if no argument is passed, the default behaviour is to split on whitespace. 
- if an argument is passed to the method, that value is used as the delimiter on which to split the string. 
     
#### .find ( )
#find #string #index 
```python
mountain_name = "Mount Kilimanjaro"
print(mountain_name.find("o"))
 # Prints 1 in the console. 
```
<span style='color:#20bf6b'>.find()</span> returns the index of the first occurrence of the string passed as the argument. It returns -1 if no occurrence is found. 
#### .upper( )
#uppercase #string 

```python
dinosaur = "T-Rex"

print(dinosaur.upper())
# Prints: T-REX
```
<span style='color:#20bf6b'>.upper()</span> returns the string with all lowercase characters converted to uppercase. 
#### .join( )
#join #string 
```python
x = "-".join(["Codecademy", "is", "awesome"])

print(x)
# Prints: Codecademy-is-awesome
```
<span style='color:#20bf6b'>.join()</span> concatenates a list of strings together to create a new string joined with the desired delimiter. 
->  This is run on the delimiter and the array of strings to be concatenated together is in as an argument. 
#### .replace( )
#string #replace
```python
fruit = "Strawberry"
print(fruit.replace('r', 'R'))

# StRawbeRRy
```
<span style='color:#20bf6b'><span style='color:#20bf6b'>.replace()</span></span> is used to replace the occurence of the first argument with the second argument within the string. 

The first argument is the old substring to be replaced, and the second argument is the new substring that will replace every occurrence of the first one within the string. 

### More on Strings 
- never expect your user will cooperate as intended
- ability to remove whitespace from a string (user typed too many spaces)
- #strip [[Lecture 0 Transcript 1#^d95d7c|method]]: `name = name.strip()` 

>the equal sign assignment is going to copy that value from the right to the left, thereby updating the value inside of my name variable. So you can not only assign values to variables, you can absolutely change the value of variables by just using the assignment operator, the equal sign again, and again, and again, and it will just keep copying from right to left whatever the new value should be.

```python
# Ask the user for their name
name = input("What's your name? ")

# Remove whitespace from the str
name = name.strip()

# Print the output
print(f"hello, {name}")
```

- Avoid repeatedly typing commands, use the up arrow of your keyboard to recall the most recent terminal commands you have made.
- R-strip = strip to right
- L-strip = strip to left

More efficient way to write code: 
```python
# Ask the user for their name
name = input("What's your name? ")

# Remove whitespace from the str and capitalize the first letter of each word
name = name.strip().title()

# Print the output
print(f"hello, {name}")
```

`name.capitalize()` = capitalize 1st letter 
`name.title()` = [[Lecture 0 Transcript 1#^20d3ea|titlecase]]

Even more efficient: chaining functions together
```python
# Ask the user for their name, remove whitespace from the str and capitalize the first letter of each word
name = input("What's your name? ").strip().title()

# Print the output
print(f"hello, {name}")
```

- longer lines of code with multiple functions are less readable than multiple lines
- `.split` splits strings into smaller, substrings
## Modules
- [[#Date and Time|Date and Time]]
- [[#Aliasing with 'as' keyword|Aliasing with 'as' keyword]]
- [[#Import Python Modules|Import Python Modules]]
- [[#random.randint( ) / random.choice( )|random.randint( ) / random.choice( )]]
- [[#Module Importing|Module Importing]]
### date.time
#datetime #module #function 
```python
import datetime
feb_16_2019 = datetime.date(year=2019, month=2, day=16)
feb_16_2019 = datetime.date(2019, 2, 16)
print(feb_16_2019) #2019-02-16

time_13_48min_5sec = datetime.time(hours=13, minute=48, second=5)
time_13_48min_5sec = datetime.time(13, 48, 5)
print(time_13_48min_5sec) #13:48:05

timestamp= datetime.datetime(year=2019, month=2, day=16, hour=13, minute=48, second=5)
timestamp = datetime.datetime(2019, 2, 16, 13, 48, 5)
print (timestamp) #2019-01-0213:48:05
```
<span style='color:#20bf6b'>datetime</span> = module to deal with dates and times

It allows you to set <span style='color:#20bf6b'>date.time</span> or both <span style='color:#20bf6b'>date</span> and <span style='color:#20bf6b'>time</span> using the<span style='color:#20bf6b'> date().time()</span> and <span style='color:#20bf6b'>datetime()</span> functions respectively, after importing the <span style='color:#20bf6b'>datetime</span> module. 
### Aliasing with 'as' keyword
```python
# Aliasing matplotlib.pyplot as plt
from matplotlib import pyplot as plt
plt.plot(x,y)

# Aliasing calendar as c
import calendar as c
print(c.month_name[1])
```
The <span style='color:#20bf6b'>as</span> keyword can be used to give an alternative name as an alias for a Python module or function
### Import Python Modules
#import #module 
```python
# Three different ways to import modules: 
# First way
import module
module.function()

# Second way
from module import function
function()

# Third way
from module import *
function()
```
### random.randint( ) / random.choice( )
#random #module 
```python
# Returns a random interger N in a given range, such that start <= N <= end
# random.randint(start,end)
r1 = random.randint(0, 10)
print(r1) # Random interger where 0 <= r1 <= 10

# Prints a random element from a sequence 
seq = ["a", "b", "c", "d", "e"]
r2 = random.choice(seq)
print(r2) # Random element in the sequence
```
The <span style='color:#20bf6b'>random</span> module offers methods to stimulate non-deterministic behaviour in selecting a random number from a range and choosing a random item from a list. 
- The <span style='color:#20bf6b'>.randint()</span> method provides a uniform random selection from a range of integers. 
- The <span style='color:#20bf6b'>.choice()</span> method provides a uniform selection of a random element from a sequence.
### Module Importing
#import #module 
```python
# file1 content
# def f1_funtion():
#     return "Hello World"

#file2
import file1

# Now we can use f1_function, because we imported file1
f1_function()
```
Import and use the content of another file using <span style='color:#20bf6b'>import filename</span>, provided that it is in the same folder as the current file you are writing. 
## Dictionaries
- [[#Accessing and Writing Data in a Python Dictionary|Accessing and Writing Data in a Python Dictionary]]
- [[#Syntax of the Python Dictionary|Syntax of the Python Dictionary]]
- [[#Dictionary Value Types|Dictionary Value Types]]
- [[#Python dictionaries|Python dictionaries]]
- [[#Dictionary Methods|Dictionary Methods]]
	- [[#Dictionary Methods#Dictionary Key-Value Methods|Dictionary Key-Value Methods]]
	- [[#Dictionary Methods#get( ) Method for Dictionary|get( ) Method for Dictionary]]
	- [[#Dictionary Methods#Merging Dictionaries with the .update( ) method in Python|Merging Dictionaries with the .update( ) method in Python]]
	- [[#Dictionary Methods#The .pop( ) Method for Dictionaries in Python|The .pop( ) Method for Dictionaries in Python]]
### Accessing and Writing Data in a Python Dictionary
#dictionary

Dictionary can be accessed by placing the key within square brackets next to the dictionary. Values written by placing key within square brackets next to the dictionary and using the assignment operator (<span style='color:#20bf6b'>=</span>).
- If the key already exists, the old value will be overwritten. 
- Attempting to access a value with a key that does not exist will cause a [[#KeyError]]
```python
my_dictionary = {"song": "Estranged", "artist": "Guns N' Roses"}
print(my_dictionary["song"])
my_dictionary["song"] = "Paradise City"
```
The second line of the example code block shows the way to access the value using the key <span style='color:#20bf6b'>"song"</span>. The third line of code block overwrites the value that corresponds to the key <span style='color:#20bf6b'>"song"</span>. 
### Syntax of the Python Dictionary
#syntax #dictionary 
```python
roaster = {"q1": "Ashley", "q2": "Dolly"}
```
Begins with left curly brace (<span style='color:#20bf6b'>{</span>), ends with the right curly brace (<span style='color:#20bf6b'>}</span>), and contains zero or more <span style='color:#20bf6b'>key : value</span> items seperated by commas. The key is separated from the value by a colon(<span style='color:#20bf6b'>:</span>)
### Dictionary Value Types
#dictionary 

Values in a dictionary can be any type (string, integer, list, dictionary, boolean, etc).
- Keys must be an immutable data type, such as [[#Immutable Strings]], numbers or tuples. 
```python
dictionary = {
1: 'hello'
'two': True,
'3': [1, 2, 3]
'Four': {'fun': 'addition'},
5.0: 5.5
}
```
The keys are string or numbers (int or float) in the example. The values, however, are many varied data types. 
### Python dictionaries
#dictionary 

```python
my_dictionary = {1: "L.A. Lakers", 2: "Houston Rockets"}
```
A python dictionary is an unordered collection of items. It contains data as a set of <span style='color:#20bf6b'>key : value</span> pairs
### Dictionary Methods
- [[#Dictionary Key-Value Methods|Dictionary Key-Value Methods]]
- [[#get( ) Method for Dictionary|get( ) Method for Dictionary]]
- [[#Merging Dictionaries with the .update( ) method in Python|Merging Dictionaries with the .update( ) method in Python]]
- [[#The .pop( ) Method for Dictionaries in Python|The .pop( ) Method for Dictionaries in Python]]
#### Dictionary Key-Value Methods 
#dictionary #method #key #value #item 
```python
ex_dict = {"a": "anteater", "b": "bumblebee", "c": "cheetah"}

ex_dict.keys()
# dict_keys(["a", "b", "c"])

ex_dict.values()
# dict_values(["anteater", "bumblebee", "cheetah"])

ex_dict.items()
# dict_items([("a","anteater"), ("b","bumblebee"), ("c","cheetah")])
```
When trying to look at information in a python dictionary, there are multiple methods that return objects that contain the dictionary keys and values. 
- <span style='color:#20bf6b'>.keys()</span> returns the keys through a dict_keys object
- <span style='color:#20bf6b'>.values()</span> returns the values through a dict_values object
- <span style='color:#20bf6b'> .items()</span> returns both the keys and values through dict_items object
#### get( ) Method for Dictionary
#dictionary #method #get
```python
# without default
{"name": "victor"}.get("name")
# returns "victor"

{"name": "Victor"}.get("nickname")
# returns None

# with default
{"name": "Victor"}.get("nickname", "nickname is not a key")
# returns "nickname is not a key"
```
Use <span style='color:#20bf6b'>.get()</span> method to access a dictionary if it exists. 

This method takes the <span style='color:#20bf6b'>key</span> as the first argument and an optional  default value as the second argument, and it returns the value for the specified <span style='color:#20bf6b'>key</span> if <span style='color:#20bf6b'>key</span> is in the dictionary.
- if the second argument is not specified and <span style='color:#20bf6b'>key</span> is not found then <span style='color:#20bf6b'>None</span> is returned. 
#### Merging Dictionaries with the .update( ) method in Python
#merge #dictionary #method #update
```python
dict1 = {'color': 'blue', 'shape': 'circle'}
dict2 = {}'color': 'red', 'number': 42}

dict1.update(dict2)

# dict1 is not {'color': 'red', 'shape': 'circle', 'number': 42}
```
<span style='color:#20bf6b'>.update()</span> function combines libraries. 
- for <span style='color:#20bf6b'>dict1.update(dict2)</span>, the key-value pairs of <span style='color:#20bf6b'>dict2</span> will be written into the <span style='color:#20bf6b'>dict1</span> dictionary.
- For keys in both <span style='color:#20bf6b'>dict1</span> and <span style='color:#20bf6b'>dict2</span>, the value in <span style='color:#20bf6b'>dict1</span> will be overwritten by the corresponding value in <span style='color:#20bf6b'>dict2</span>.
#### The .pop( ) Method for Dictionaries in Python
#pop 
```python
famous_museums = {'Washington',: 'Smithsonian Institution', 'Paris': 'Le Louvre', 'Athens'}: 'The Acropolis Museum'}
famous_museums.pop('Athens')
print(famous_museums) # {'Washington': 'Smithsonian Institution', 'Paris': 'Le Louvre'}
```
Dictionaries can remove key-value pairs with<span style='color:#20bf6b'> .pop()</span>. 
- Takes a <span style='color:#20bf6b'>key</span> as an argument and removes it from dictionary. At the same time, it also returns the value that it removes from the dictionary. 
## Files
- [[#Python File Object|Python File Object]]
- [[#Python Readline Method|Python Readline Method]]
- [[#Parsing JSON Files to Dictionary|Parsing JSON Files to Dictionary]]
- [[#Python Append to File|Python Append to File]]
- [[#Python Write to File|Python Write to File]]
- [[#Python Readlines Method|Python Readlines Method]]
- [[#Class csv.DictWriter|Class csv.DictWriter]]
- [[#Python Read Method|Python Read Method]]
### Python File Object
#open #file 
A file object is created when a file is opened with the <span style='color:#20bf6b'>open()</span> function.
- you can associate this file object with a variable when you open a file using <span style='color:#20bf6b'>with</span> and <span style='color:#20bf6b'>as</span> keywords. 
```python
with open('somefile.txt') as file_object:
```
You can then print the content of file object,<span style='color:#20bf6b'> file_object</span> with <span style='color:#20bf6b'>print()</span>
```python
print(file_object)
```
You might see something like this on the output terminal: 
```python
<_io.TextIOWrapper name='
somefile.txt' mode='r'
encoding='UTF-8'>
```
### .readline( )
#readline #file #open 

<span style='color:#20bf6b'>.readline()</span> on a file object that is returned from the <span style='color:#20bf6b'>open()</span> function **to read only one line** instead of multiple lines in a Python file.
-->  Every subsequent <span style='color:#20bf6b'>.readline()</span> will extract the next line from in the file if it exists.
```python
with open('story.txt') as story_object:
  print(story_object.readline())
```
Will print only the first like in <span style='color:#20bf6b'>story.txt</span>
### Parsing JSON Files to Dictionary 
```python
# Use json.load with an opened file object to read the contents into a python dictionary. 

# Contents of file.json
# { 'UserId': 10 }

import json
with open('file.json') as json_file:
  python_dict = json.load(json_file)

print(python_dict.get('UserId'))
# Prints 10
```
JSON format is used to store key value pairs. 
- the <span style='color:#20bf6b'>JSON</span> module allows reading such data format and parsing it to a dictionary. 
- the<span style='color:#20bf6b'> json.load</span> function takes a file object as an argument and returns the data in a dictionary format
### Python Append to File
#append #open #file 

Writing to an opened file with the '<span style='color:#20bf6b'>w'</span> flag overwrites all previous content in the file. To avoid this, we can append to a file instead. 
- Use the <span style='color:#20bf6b'>'a'</span> flag as the second argument to <span style='color:#20bf6b'>open()</span>
- if a file doesn't exist, it will be created for append mode. 
```python
with open('shopping.txt', 'a')
  as shop:
    shop.write('Tomatoes, cucumbers, celery\n')
```
### .write( )
#file #open #write 

<span style='color:#20bf6b'>open()</span> will only open file for reading. 
- a second argument 'r' is passed by default. 

To write to a file: 
- open the file with write permission via the<span style='color:#20bf6b'> 'w'</span> argument
- then use the .write() method to write the file.
- If the file already exists, all prior content will be overwritten. 
```python
with open('diary.txt', 'w') as 
  diary:
    diary.write('Special events for today')
```
### Python Readlines Method
#file #readline #read 

Read a single line at a time instead of the entire content of a file.<span style='color:#20bf6b'> .read()</span> returns a string, whereas<span style='color:#20bf6b'> .readlines()</span> will return a list of strings, each representing an individual line in the file. 

Calling this code: 
```python
with open('lines.txt') as file_object:
  file_data = file_object.readlines()
print(file_data)
```
returns a list of strings in <span style='color:#20bf6b'>file_data</span>:
```python
['1. Learn Python.\n', '2. Work Hard.\n', '3. Graduate.']
```
Iterating over the list,<span style='color:#20bf6b'> file_data</span> and printing it:
```python
for line in file_data:
  print(line)
```
Outputs:
```python
1. Learn Python.
  
2. Work hard
  
3. Graduate.
```
### csv.DictWriter
#write #file #operator #fieldnames #class
```python
# An example of csv.DictWriter 
import csv

with open('companies.csv', 'w') as csvfile:
  fieldnames = ['name', 'type']
  write = csv.DictWriter(csvfile, fieldnames=fieldnames)
  writer.writeheader()
  writer.writerow({'name': 'Codecademy', 'type': 'Learning'}]
  writer.writerow({'name': 'Google', 'type': 'Search'})

  """
  After running the above code, companies.csv will contain the following information:

  name,type
  Codecademy,Learning
  Google, Search
  """
```
The <span style='color:#20bf6b'>CSV</span>  module implements classes to read and write tabular data in CSV format.
- The class <span style='color:#20bf6b'>DictWriter</span> operates like a regular writer but maps a dictionary onto output rows
- The keys of the dictionary are column names while values are actual data. 

The <span style='color:#20bf6b'>csv.DictWrite</span> constructor takes two arguments: 
- The first is to open the file handler that eh CSV is being written to.
- The second named parameter, <span style='color:#20bf6b'>fieldnames</span>, is a list of field names that the CSV is going to handle. 
### .read( )
#file #read #open 

After a file is opened with <span style='color:#20bf6b'>open()</span> returning a file object, call the <span style='color:#20bf6b'>.read()</span> method of the file object to return the entire file content as a Python string.

Execute the following Python code:
```python
with open('mystery.txt') as text_file:
  text_data = text_file.read()
print(text_data)
```
will produce a string containing the entire content of the read file: 
```python
Mystery solved.
Congratulations!
```
## Classes
- [[#' repr ' Method|' repr ' Method]]
- [[#Class Methods|Class Methods]] ^2ed189
- [[#Instantiate Python Class|Instantiate Python Class]]
- [[#Class Variables|Class Variables]]
- [[#' init ' Method|' init ' Method]]
- [[#' type( ) ' Function|' type( ) ' Function]]
- [[#Python Class|Python Class]]
- [[#' dir( ) ' Function|' dir( ) ' Function]]
- [[#__main__ in Python|__main__ in Python]]
### ' repr ' Method
#class #self #init #pepr 

```python
class Employee:
  def__init__(self, name):
    self.name = name

def__repr__(self):
  return self.name

john = Employee('John')
print(john) # John
```
Used to tell Python what the string representation of the class should be. It can only have one parameter, <span style='color:#20bf6b'>self</span>, and it should return a string. 
### Class Methods

^fa803a

#class #function 
```python
# Dog class
class Dog:
  # Method of the class
  def bark(self):
    print("Ham-Ham")

# Create a new instance
charlie = Dog()

# Call the method
charlie.bark()
# This will output "Ham-HAm"
```
Methods are functions that are defined as part of a class. It is common practice that the first argument of any method that is part of the class is the actual object calling the method. This argument is usually called self. 
### Instantiate Python Class
#class
```python
class Car:
  "This is an empty class"
  pass

# Class instantiation
ferrari = Car()
```
A class needs to be instantiated before use. 

As an analogy, a class can be thought of as a blueprint (Car), and an insance is an actual implementation of the blueprint (Ferrari)
### Class Variables
#class #variable 
```python
class my_class:
  class_variable = "I am a Class variable!"

x = my_class()
y = my_class()

print(x.class_variable) #I am a Class Variable!
print(y.class_variable) #I am a class Variable!
```
Class variables are defined outside of all methods and have the same value for every instance of the class. 

Class variables are accessed with the <span style='color:#20bf6b'>instance.variable</span> or <span style='color:#20bf6b'>class_name.variable</span> syntaxes. 
### init
#init #class 

```python
class Animal: 
	def __init__(self, voice):
   self.voice = voice

# When a class instance is created, the instance variable # 'voice' is created and set to the input value.
cat = Animal('Meow')
print(cat.voice) # Output: Meow

dog = Animal('Woof')
print(dog.voice) # Output: Woof
```
The `.__init__()` method is used to initialize a newly created object. It is called every time the class is instantiated. 
### ' type( ) ' Function
#type #function #class 

```python
a = 1
print(type(a)) # <class 'int'>

a = 1.1
print(type(a)) # <class 'float'>

a = 'b'
print(type(a)) # <class 'str'>

a = None
print(type(a)) # <class 'NoneType'>
```
Returns the data type of the argument passed to it. 
### Python Class
#class 

```python
# Defining a class 
class Animal:
  def __init__(self, name):
    self.name = name
    self.number_of_legs = number_of_legs
```
A class is a template for a data type. A class can be defined using the <span style='color:#20bf6b'>class</span> keyword. 
### ' dir( ) ' Function
#class 

```python
class Employee:
  def __init__(self):
    self.name = name

  def print_name(self):
    print("Hi, I'm " + self.name)

print(dir())
# ['Employee', '__builtins__', '__doc__', '__file__', '__name__', '__package__', 'new_employee']

print(dir(Employee))
# ['__doc__', '__init__', '__module__', 'print_name']
```
The built-in dir() function, without any argument, returns a list of all the attributes in the current scope. 
- With an object as an argument, dir() tries to return all valid object attributes. 
### main__ in Python
#main #class 
An identifier used to reference the current file context. When a module is read from standard input, a script, or from an interactive prompt, its `__name__` is set equal to `__main__`.

Example:
> We create an instance of a class called CoolClass. Printing the type() of the instance will result in
```python
<class '__main__.CoolClass'>
```
This means that the class CoolClass was defined in the current script file. 