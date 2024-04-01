### Python
Python is a high-level, interpreted programming language. It is widely used in various fields such as web development, data science, artificial intelligence and automation.

### Inbuilt Function
pre-defined function
Examples: str(), int(), float()
### Data Type
1. **Numeric Data Types:**
   - **int**: Represents integers (whole numbers). Example: `x = 5`
   - **float**: Represents floating-point numbers (numbers with decimal points). Example: `y = 3.14`
   - **complex**: Represents complex numbers. Example: `z = 2 + 3j`

2. **Sequence Types:**
   - **str**: Represents strings (sequences of characters). Example: `text = "Hello, World"`
   - **list**: Represents lists (ordered, mutable sequences). Example: `my_list = [1, 2, 3]`
   - **tuple**: Represents tuples (ordered, immutable sequences). Example: `my_tuple = (1, 2, 3)`

3. **Mapping Type:**
   - **dict**: Represents dictionaries (key-value pairs). Example: `my_dict = {'name': 'John', 'age': 30}`

4. **Set Types:**
   - **set**: Represents sets (unordered collections of unique elements). Example: `my_set = {1, 2, 3}`
   - **frozenset**: Represents immutable sets. Example: `my_frozenset = frozenset([1, 2, 3])`

5. **Boolean Type:**
   - **bool**: Represents Boolean values (`True` or `False`). Example: `is_valid = True`

6. **Binary Types:**
   - **bytes**: Represents immutable sequences of bytes. Example: `data = b'Hello'`
   - **bytearray**: Represents mutable sequences of bytes. Example: `data = bytearray(b'Hello')`

7. **None Type:**
   - **NoneType**: Represents the `None` object, which is used to indicate the absence of a value or a null value.

8. **Custom Data Types:**
   - You can also define your custom data types using classes and objects.
   
### Keywords
1. **and**: It is a logical operator that returns `True` if both operands are true.

2. **or**: It is a logical operator that returns `True` if at least one of the operands is true.

3. **not**: It is a logical operator that returns the opposite of the operand's truth value.

4. **if**: It is used to start a conditional statement and is followed by a condition that determines whether the code block is executed.

5. **else**: It is used in conjunction with `if` to define an alternative code block to execute when the `if` condition is `False`.

6. **elif**: Short for "else if," it is used to check additional conditions after an `if` statement and is used in combination with `if` and `else`.

7. **while**: It is used to create a loop that repeatedly executes a block of code as long as a specified condition is true.

8. **for**: It is used to create a loop that iterates over a sequence (such as a list, tuple, or string) and executes a block of code for each item in the sequence.

9. **in**: Used with `for`, it checks if a value is present in a sequence.

10. **try**: It is the beginning of a block of code that is subject to exception handling. It is followed by `except` to catch and handle exceptions.

11. **except**: Used with `try`, it defines a block of code to execute when an exception is raised in the corresponding `try` block.

12. **finally**: Used with `try`, it defines a block of code that is always executed, whether an exception is raised or not.

13. **def**: It is used to define a function in Python.

14. **return**: It is used within a function to specify the value that the function should return.

15. **class**: It is used to define a class, which is a blueprint for creating objects in object-oriented programming.

16. **import**: It is used to import modules or libraries to access their functions, classes, or variables.

17. **from**: Used with `import` to specify which specific components from a module should be imported.

18. **as**: Used with `import` to create an alias for a module, making it easier to reference in the code.

19. **True**: It represents a boolean value for "true."

20. **False**: It represents a boolean value for "false."

21. **None**: It represents a special null value or absence of value.

22. **is**: It is used for identity comparison, checking if two variables refer to the same object in memory.

23. **lambda**: It is used to create small, anonymous functions (lambda functions).

24. **with**: It is used for context management, ensuring that certain operations are performed before and after a block of code.

25. **global**: It is used to declare a global variable within a function's scope.

26. **nonlocal**: It is used to declare a variable as nonlocal, which allows modifying a variable in an enclosing (but non-global) scope.

### Variable
```
name = "arbab"
print(name)
```
here `name` is variable and `"arbab"` is string

#### Global variable

Global variables are defined outside of any function.
 ```python
   y = 20  # Global variable

   def another_function():
       print(y)  # This will access the global variable 'y'

   another_function()
   print(y)  # This will print 20
   ```
#### Local varibale
Local variables are defined within a function or a block.
 ```python
   def my_function():
       x = 10  # Local variable
       print(x)
   
   my_function()
   print(x)  # This will raise an error since 'x' is not defined outside the function.
   ```
#### Snake casing: `_`
example: arbab_khan
#### Camel casing: `A`
example: khanArbab
#### Function
function is a block of reusable code that performs a specific task. Functions are defined using the `def`
#### Module
Modules can define functions, classes, and variables that can be used in other Python files by importing the module. `import`
#### Packages
Package is a collection of modules organized in directories.
#### Virtual Environment
logical separation for python machine
```
# Create a virtual environment
python -m venv myenv

# Activate the virtual environment (on macOS/Linux)
source myenv/bin/activate
```
### Command line argument
To access command line variables in Python, you can use the `sys.argv`
### Enviornment variable
To access environment variables in Python, you can use The `os.geten`

### Operator
#### Arithmetic Operators

+: Addition

-: Subtraction

*: Multiplication

/: Division

%: Modulus (remainder)

//: Floor division (integer division)

**: Exponentiation

#### Comparison Operators

==: Equal to

!=: Not equal to

<: Less than

<=: Less than or equal to

>: Greater than
>
>=: Greater than or equal to

#### Logical Operators

`and`, `or`, `not`

#### Assignment Operators

=: Assignment

+=: Add and assign

-=: Subtract and assign

*=: Multiply and assign

/=: Divide and assign

%=: Modulus and assign

**=: Exponentiate and assign

//=: Floor divide and assign

#### Membership Operators

in: Checks if an element is in a sequence

not in: Checks if an element is not in a sequence

#### Identity Operators

is: Checks if two objects are the same object

is not: Checks if two objects are not the same object

#### Bitwise Operators

&: Bitwise AND

|: Bitwise OR

^: Bitwise XOR

~: Bitwise NOT

<<: Bitwise left shift

>>: Bitwise right shift

#### Other Operators

(): Parentheses for grouping expressions

[]: Square brackets for indexing and slicing

{}: Curly braces for sets and dictionaries

:: Colon for slicing and dictionary keys

;: Semicolon for separating statements

. : Dot operator for accessing object attributes
