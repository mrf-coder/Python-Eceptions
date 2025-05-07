# Python-Eceptions
```
In Python, an exception is an event that occurs during the execution of a program that disrupts the
 normal flow of instructions. It is a way to handle errors and other exceptional circumstances that
may arise while the program is running. When an exception occurs, Python creates an exception object,
 which contains information about the error, such as its type and a message describing what went wrong.


Python has many built-in exceptions, such as TypeError, ValueError, IndexError, and FileNotFoundError.
 You can also define your own custom exceptions by creating a new class that inherits from the built-in
 Exception class or one of its subclasses.
To handle exceptions, you can use a try...except block. The code that might raise an exception is placed
 inside the try block, and the code that handles the exception is placed inside the except block. If an
 exception occurs in the try block, Python will jump to the except block that matches the type of exception
that was raised. If no matching except block is found, the exception will propagate up the call stack until
it is caught or the program terminates.
```
```js
try:
    # Code that might raise an exception
    result = 10 / 0
except ZeroDivisionError as e:
    # Code that handles the exception
    print(f"An error occurred: {e}")

```
```js
  print("hello, world)
```
SyntaxError: unterminated string literal (detected at line 3)
```
```
```js
  input cat
x = int(input("What,s X?"))
print(f"X is {x}")
```
```js
try:
     x = int(input("What,s X?"))
     print(f"X is {x}")
except ValueError:
     print("X is not an integer")     

````
```js
```
NameError: name 'x' is not defined
```
try:
     x = int(input("What,s X?"))
except ValueError:
     print("X is not an integer") 


     print(f"X is {x}")    

```

ValueError: invalid literal for int() with base 10: 'cat'
```
```
