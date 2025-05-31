# Python-Eceptions

- __[Python-Conditionals](https://github.com/mrf-coder/Python-Conditionals.git)__ - 
- __[Python-Loops](https://github.com/mrf-coder/Python-Loops.git)__ - 
- __[Python-Eceptions ](https://github.com/mrf-coder/Python-Eceptions.git)__ - 
- __[Python-Libraries ](https://github.com/mrf-coder/Python-Libraries.git)__ - 
- __[Python-UnitTest ](https://github.com/mrf-coder/Python-UnitTest.git)__ - 
- __[Python-I-o](https://github.com/mrf-coder/Python-I-o.git)__ - 
- __[Regular-Expressions ](https://github.com/mrf-coder/Regular-Expressions.git)__ - 
- __[Object-Oriented-Programming](https://github.com/mrf-coder/Object-Oriented-Programming.git)__ - 
- __[Et-Cetera](https://github.com/mrf-coder/Et-Cetera.git)__ - 


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
```
SyntaxError: unterminated string literal (detected at line 3)
```
  print("hello, world)

```
```js
  input cat
x = int(input("What,s X?"))
print(f"X is {x}")
```
```js
```

ValueError: invalid literal for int() with base 10: 'cat'
```
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
```js
 try:
     x = int(input("What,s X?"))
except ValueError:
     print("X is not an integer") 
else:

     print(f"X is {x}")    
```
```js
   try again and again because loop
  breack the when enter an integer
while True:
    try:
         x = int(input("What,s X?"))
    except ValueError:
         print("X is not an integer") 
    else:
        break
print(f"X is {x}")    
```
```js
while True:
    try:
         x = int(input("What,s X?"))
         break
    except ValueError:
         print("X is not an integer") 
    
       
print(f"X is {x}")    

````
```js
def main():
    x = get_int()
    print(f"X is {x}")  


def get_int():
    while True:
        try:
            x = int(input("What's X? "))  # Also corrected typo in prompt
        except ValueError:
            print("X is not an integer") 
        else:
            break
        
    return x  # Fixed indentation


main()

```
- __[Python-Conditionals](https://github.com/mrf-coder/Python-Conditionals.git)__ - 
- __[Python-Loops](https://github.com/mrf-coder/Python-Loops.git)__ - 
- __[Python-Eceptions ](https://github.com/mrf-coder/Python-Eceptions.git)__ - 
- __[Python-Libraries ](https://github.com/mrf-coder/Python-Libraries.git)__ - 
- __[Python-UnitTest ](https://github.com/mrf-coder/Python-UnitTest.git)__ - 
- __[Python-I-o](https://github.com/mrf-coder/Python-I-o.git)__ - 
- __[Regular-Expressions ](https://github.com/mrf-coder/Regular-Expressions.git)__ - 
- __[Object-Oriented-Programming](https://github.com/mrf-coder/Object-Oriented-Programming.git)__ - 
- __[Et-Cetera](https://github.com/mrf-coder/Et-Cetera.git)__ - 








