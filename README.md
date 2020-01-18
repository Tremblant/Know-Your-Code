Know Your Code
-----------------------

### on your mark, get set, python!

Taking the first step in learning any programming language is usually the hardest. We all have doubts about whether the path we will be taking will lead to success.

Learning to code in python was the best choice I ever made. Python is a simple language to use with powerful functionalities. Below I will take you through the basics of python to kick off your python journey.


### print () function

In python, functions are used to cause an effect like displaying contents on the screen or solve problems like finding prime numbers in a range of values. Taking an example below:

```python
# simple print()function
print("Hello World!\nWelcome to Africa Awakening.")

Hello World!
Welcome to Africa Awakening.
```
 
The **print() function** above has a string as an argument delimited by quotes. Notice the output produces two lines of sentences, this is because of the escape character and 'n' character(\n) which tells our code to move to a new line. From above we see 'Hello World!' comes before 'Welcome to Africa Awakening', this in python is known as a **positional argument** where the passing of argument depends on the position and a second argument can't come before the first.
     
Another method of passing arguments is known as a **keyword argument** where arguments are executed using special words. The keyword argument comprises of:
    
- A keyword which is used to identify the argument (e.g sep, end) 
    
- An equal sign(=)
    
- And a value assigned to the argument

_**Note**_: _Any keywords arguments used, come after the last execution of positional argument._ 

```python
# 'end'keyword argument
print ("Hello World!", "Welcome to Africa Awakening.", end="**")
print("Africa is a beautiful continent.")

Hello World! Welcome to Africa Awakening.**Africa is a beautiful continent
```

### Python as a Calculator

Python can be used to perform addition(+), subtraction(-), multiplication(*) and division(/) operations. Before delving deeper into this one needs to understand the difference between integers and floats.
    
  - **Integers** consist of whole numbers which can be positive, negative or zero without the fraction part. For example; 0, 87, -8, 100
  
  - **Floats**, on the other hand, consist of both the whole number and the fraction part. For example; 4.333, 7.0, -1.456
  
Some of the operators to take note include; division operator where (/) gives a float value and (//) gives an integer output, the remainder operator (%) displays remainder after an integer division and the exponential operator (**) used to calculate the power of a number.
        
```python
17 / 3 # division returns a float
5.666666666666667
17 // 3 # integer division discards the fractional part
5
17 % 3 # the % operator returns the remainder of the division
2
2 ** 7 # 2 to the power of 7
128
```

### String Literals

String comes to play when **text processing** is involved. The string is usually placed inside single quotes (' ') or double quotes(" "). The **escape character(/)** is used to escape quotes.
    
```python
# string literal
print('I\'m \nlearning \n"Monty Python"')

I'm 
learning 
"Monty Python"

s = 'First line.\nSecond line.' # \n means newline
print(s)

First line.
Second line.
```

_**Note**_: _From above, the second command has introduced what we call variable assignment. In python, a variable is used to store values which can be used later. A variable usually consists of a name and a value which is the content being stored._

### Compound Data Types

**Lists**

Grouping of values is very common in python. The most frequently used method is _**'lists'**_ which contains comma-separated values inside square brackets.
    
```python
# list in action
digits = [1, 4, 9, 16, 25, 36]
print(digits)

[1, 4, 9, 16, 25, 36]
```

_Other compound data types include **tuples, sets and dictionary** which are a great area of study under **data structures**._

### Control Flow Tools

**if statement**

```python
if number >= 10:
    print("True")
else:
    print("False")
```

_**if statements**_ are used to control the flow of the program. For example, above if statement checks if our number is greater then or equal to 10, if so it outputs 'True' on the screen, otherwise, it outputs 'False' when the above condition is not met.
    
**while loop**

_**while loop**_ is an iterative condition which executes as long as the condition is true.
    
```python
x = 0
while x < 5:
    print(x)
    x = x + 1 # x += 1
```

Above while loop prints values that are less than 5. The values will begin at 0 up to the less than 5 threshold is achieved.
    
**for loop**

Python's _**for statement**_ iterates over the items of any sequence(a list or a string) and in the order, they appear in the sequence.
    
```python
# Measure some strings:
words = ['cat', 'window', 'defenestrate']
for w in words:
    print(w, len(w))
    
cat 3
window 6
defenestrate 12
```

### Functions

Functions are used to define tasks to be carried out by the computer depending on the inputs. Below is a simple example of a function:
    
```python
#function calculating square of number
def square(num):
    return number**2
```

_**def keyword**_ introduces the function definition. Then, we have the _**function name**_ (in this case 'square') and _**parameters**_ of the function are placed inside the parenthesis. Statements that form the body of the function starts after the colon and must be indented. The keyword return shows that our function will generate some output.
    
_**Happy coding ...**_    