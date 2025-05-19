### Python Questions

1. **What is a variable in Python?**
   A variable in Python is a name used to refer to a value stored in memory. It acts as a placeholder for data that can be used throughout a program.

2. **How do you assign a value to a variable in Python?**
   You assign a value to a variable using the `=` operator. For example:

   ```python
   x = 10
   ```

3. **What are the different types of variables in Python?**
   Python has various data types, including:

   * **int** (integer)
   * **float** (floating point number)
   * **str** (string)
   * **bool** (boolean)
   * **list** (list)
   * **tuple** (tuple)
   * **set** (set)
   * **dict** (dictionary)

4. **Explain the concept of operators in Python.**
   Operators are special symbols in Python that perform operations on variables and values. They can perform arithmetic, comparison, logical, and other operations.

5. **What is an operand in an expression?**
   An operand is a value or variable that an operator acts upon. For example, in the expression `5 + 3`, `5` and `3` are operands, and `+` is the operator.

6. **What is the difference between `=` and `==` in Python?**

   * `=` is the assignment operator, used to assign a value to a variable.
   * `==` is the equality operator, used to compare two values.

7. **What are the different types of operators in Python?**
   Python supports various types of operators:

   * **Arithmetic operators**: `+`, `-`, `*`, `/`, `%`, `//`, `**`
   * **Comparison operators**: `==`, `!=`, `<`, `>`, `<=`, `>=`
   * **Logical operators**: `and`, `or`, `not`
   * **Assignment operators**: `=`, `+=`, `-=`, `*=`, `/=`
   * **Bitwise operators**: `&`, `|`, `^`, `<<`, `>>`
   * **Membership operators**: `in`, `not in`
   * **Identity operators**: `is`, `is not`

8. **What is the order of operations in Python?**
   Python follows the standard order of operations, often remembered by the acronym PEMDAS:

   * Parentheses `()`
   * Exponents `**`
   * Multiplication, Division, and Modulus `* / %`
   * Addition and Subtraction `+ -`
   * Comparison operators
   * Logical operators

9. **Explain the difference between expressions and statements.**

   * **Expression**: A combination of values, variables, and operators that yields a result (e.g., `2 + 3`).
   * **Statement**: A complete line of code that performs an action (e.g., `x = 5`).

10. **How do you perform arithmetic operations in Python?**
    Arithmetic operations are performed using operators like `+`, `-`, `*`, `/`, `%`, `//`, and `**`. Example:

    ```python
    result = 10 + 5  # Addition
    ```

11. **What are the Python keywords?**
    Python keywords are reserved words that have a specific meaning and cannot be used as identifiers (e.g., `if`, `else`, `for`, `while`, `import`).

12. **How does Python handle string concatenation?**
    Python uses the `+` operator to concatenate strings. Example:

    ```python
    str1 = "Hello"
    str2 = "World"
    result = str1 + " " + str2  # Result: "Hello World"
    ```

13. **What is the use of the `+` operator in strings?**
    The `+` operator in strings is used for concatenation, joining two or more strings together.

14. **What are string escape sequences in Python?**
    Escape sequences are special character combinations that allow certain characters to be represented in a string (e.g., `\n` for newline, `\t` for tab).

15. **What is the purpose of comments in Python?**
    Comments are used to explain code and make it more understandable. They are ignored during execution and are prefixed by `#`.

16. **How do you take input from the user in Python?**
    Use the `input()` function to take input from the user. Example:

    ```python
    name = input("Enter your name: ")
    ```

17. **What is the syntax for defining a string in Python?**
    Strings can be defined using either single quotes (`'`) or double quotes (`"`). Example:

    ```python
    name = 'Alice'
    message = "Hello"
    ```

18. **What is the `len()` function in Python used for?**
    The `len()` function returns the length of a sequence (e.g., string, list). Example:

    ```python
    len("Hello")  # Returns 5
    ```

19. **How do you convert a string to uppercase in Python?**
    Use the `upper()` method on a string:

    ```python
    "hello".upper()  # "HELLO"
    ```

20. **What is the purpose of the `input()` function in Python?**
    The `input()` function allows you to prompt the user for input and read it as a string.

21. **What does the `type()` function do in Python?**
    The `type()` function returns the data type of an object. Example:

    ```python
    type(5)  # <class 'int'>
    ```

22. **How do you convert an integer to a string in Python?**
    Use the `str()` function to convert an integer to a string:

    ```python
    str(10)  # "10"
    ```

23. **What is the purpose of `str()` and `int()` functions in Python?**

    * `str()` converts an object to a string.
    * `int()` converts an object to an integer.

24. **How do you format strings in Python?**
    You can format strings using f-strings, `format()`, or the `%` operator:

    ```python
    name = "Alice"
    greeting = f"Hello, {name}!"  # Using f-string
    ```

25. **What are the differences between single and double quotes in strings?**
    In Python, there is no functional difference between single (`'`) and double (`"`) quotes. The choice is a matter of style or convenience, especially when one type of quote is used inside the string.

26. **What are multiline strings in Python and how do you create them?**
    Multiline strings are enclosed in triple quotes (`'''` or `"""`). Example:

    ```python
    multiline_string = """This is
    a multiline
    string."""
    ```

27. **What is an expression in Python?**
    An expression is a combination of values, variables, and operators that results in a value.

28. **What is a statement in Python?**
    A statement is an instruction that Python executes, such as assignments, function calls, or loops.

29. **How do you use the modulus operator in Python?**
    The modulus operator (`%`) returns the remainder of a division. Example:

    ```python
    10 % 3  # 1
    ```

30. **How do you perform exponentiation in Python?**
    The exponentiation operator (`**`) is used to raise a number to the power of another number:

    ```python
    2 ** 3  # 8
    ```

31. **What does `//` do in Python?**
    The `//` operator performs floor division, returning the largest integer less than or equal to the result of the division:

    ```python
    7 // 3  # 2
    ```

32. **How do you perform division with floating-point numbers in Python?**
    Use the `/` operator for floating-point division. It returns a float:

    ```python
    7 / 3  # 2.3333...
    ```

33. **How do you check if a number is an integer or float in Python?**
    Use the `type()` function to check the data type of a number:

    ```python
    type(5)  # <class 'int'>
    type(5.0)  # <class 'float'>
    ```

34. **Explain string indexing in Python.**
    String indexing allows you to access individual characters in a string using their position (index), starting from 0. Example:

    ```python
    s = "Hello"
    s[0]  # 'H'
    ```

35. **How do you check the data type of a variable in Python?**
    Use the `type()` function to check the data type of a variable:

    ```python
    type(x)  # <class 'int'>
    ```

36. **What are the common types of operators used in Python?**
    Common operators include:

    * **Arithmetic operators**: `+`, `-`, `*`, `/`, `%`
    * **Comparison operators**: `==`, `!=`, `<`, `>`, `<=`, `>=`
    * **Logical operators**: `and`, `or`, `not`

37. **How do you perform comparisons in Python?**
    Comparison operators like `==`, `!=`, `<`, `>`, `<=`, and `>=` are used to compare values. Example:

    ```python
    5 > 3  # True
    ```

38. **What is the purpose of the `and` operator?**
    The `and` operator is used to combine two boolean expressions and returns `True` if both expressions are `True`.

39. **What is the `or` operator in Python?**
    The `or` operator combines two boolean expressions and returns `True` if at least one expression is `True`.

40. **What does `not` do in Python?**
    The `not` operator inverts the boolean value of an expression. If the expression is `True`, it returns `False`, and vice versa.
    
41. **What is a conditional statement in Python?**
    A conditional statement allows you to execute specific blocks of code based on certain conditions. The most common conditional statements in Python are `if`, `elif`, and `else`.

42. **What is the syntax of an `if` statement in Python?**
    The `if` statement has the following syntax:

```python
if condition:
    # code to execute if condition is True
```

43. **How does an `if-else` statement work in Python?**
    The `if-else` statement allows you to execute one block of code if a condition is true, and another block of code if the condition is false:

```python
if condition:
    # code if condition is True
else:
    # code if condition is False
```

44. **What is an `if-elif-else` statement in Python?**
    The `if-elif-else` statement allows you to check multiple conditions:

```python
if condition1:
    # code if condition1 is True
elif condition2:
    # code if condition2 is True
else:
    # code if all conditions are False
```

45. **How do you write a nested `if` condition in Python?**
    A nested `if` condition is an `if` statement inside another `if` statement:

```python
if condition1:
    if condition2:
        # code if both conditions are True
```

46. **What does the modulus operator `%` do?**
    The modulus operator returns the remainder when dividing two numbers:

```python
10 % 3  # 1
```

47. **Explain how to use logical operators in Python.**
    Logical operators (`and`, `or`, `not`) are used to combine or negate boolean expressions:

* `and`: Returns `True` if both conditions are `True`.
* `or`: Returns `True` if at least one condition is `True`.
* `not`: Reverses the boolean value of the condition.

48. **How do you check if a number is divisible by another number in Python?**
    Use the modulus operator (`%`) to check divisibility:

```python
if number % divisor == 0:
    # number is divisible by divisor
```

49. **What is a `while` loop in Python?**
    A `while` loop repeatedly executes a block of code as long as a condition is `True`:

```python
while condition:
    # code to execute while condition is True
```

50. **How do you exit a `while` loop prematurely in Python?**
    Use the `break` statement to exit a loop prematurely:

```python
while True:
    if some_condition:
        break
```

51. **What is the purpose of the `break` statement in Python?**
    The `break` statement is used to exit a loop immediately, regardless of the loop's condition.

52. **What is the purpose of the `continue` statement in Python?**
    The `continue` statement skips the current iteration and moves to the next iteration of the loop.

53. **How do you create an infinite loop in Python?**
    You can create an infinite loop using a `while` loop with a condition that always evaluates to `True`:

```python
while True:
    # infinite loop
```

54. **What is the syntax for a `for` loop in Python?**
    A `for` loop in Python is used to iterate over a sequence (such as a list, tuple, or string):

```python
for item in iterable:
    # code to execute for each item
```

55. **How do you loop over a list using a `for` loop in Python?**
    You can loop over a list using the `for` loop like this:

```python
numbers = [1, 2, 3, 4]
for num in numbers:
    print(num)
```

56. **What is the `range()` function used for in Python?**
    The `range()` function generates a sequence of numbers, commonly used in loops:

```python
for i in range(5):  # Generates numbers from 0 to 4
    print(i)
```

57. **How do you iterate over the characters in a string using a `for` loop?**
    You can iterate over the characters in a string like this:

```python
for char in "Hello":
    print(char)
```

58. **What is the purpose of the `else` clause in a loop?**
    The `else` clause in a loop executes after the loop finishes iterating, unless the loop was terminated with a `break` statement.

59. **How do you use a `break` statement inside a loop?**
    The `break` statement can be used to exit the loop prematurely:

```python
for num in range(10):
    if num == 5:
        break  # Exits the loop when num is 5
```

60. **How do you create a nested loop in Python?**
    A nested loop is a loop inside another loop:

```python
for i in range(3):
    for j in range(2):
        print(i, j)
```

61. **What is the difference between a `while` loop and a `for` loop in Python?**

* A `while` loop repeats until a condition is `False`.
* A `for` loop iterates over a sequence of items (e.g., a list, tuple, or string).

62. **What is the syntax of a `for` loop with `else` in Python?**
    A `for` loop with `else` will execute the `else` block if the loop completes normally (i.e., without a `break`):

```python
for item in iterable:
    # code
else:
    # code if loop completed without break
```

63. **How can you iterate over multiple lists simultaneously in Python?**
    You can use `zip()` to iterate over multiple lists at the same time:

```python
list1 = [1, 2, 3]
list2 = ['a', 'b', 'c']
for item1, item2 in zip(list1, list2):
    print(item1, item2)
```

64. **What is list comprehension in Python?**
    List comprehension is a concise way to create lists based on existing iterables:

```python
squares = [x ** 2 for x in range(5)]
```

65. **How do you use `continue` in a loop?**
    The `continue` statement skips the current iteration and moves to the next one:

```python
for i in range(5):
    if i == 3:
        continue  # Skip when i is 3
    print(i)
```

66. **What does `continue` do in a `for` loop?**
    The `continue` statement in a `for` loop skips the rest of the current iteration and moves to the next iteration.

67. **How do you implement a countdown using a `while` loop?**
    A countdown can be implemented as follows:

```python
count = 10
while count > 0:
    print(count)
    count -= 1
```

68. **How do you sum all elements in a list using a loop?**
    You can use a loop to sum all elements in a list:

```python
total = 0
for num in [1, 2, 3, 4]:
    total += num
```

69. **How do you find the largest number in a list using a loop?**
    To find the largest number:

```python
largest = numbers[0]
for num in numbers:
    if num > largest:
        largest = num
```

70. **How do you reverse a list using a loop?**
    To reverse a list using a loop:

```python
reversed_list = []
for item in numbers:
    reversed_list.insert(0, item)
```

71. **Write a program to print numbers from 1 to 10 using a `for` loop.**

```python
for i in range(1, 11):
    print(i)
```

72. **How do you check if a number is prime using a loop in Python?**
    To check if a number is prime:

```python
def is_prime(num):
    for i in range(2, num):
        if num % i == 0:
            return False
    return True
```

73. **What is a nested loop and give an example?**
    A nested loop is a loop inside another loop:

```python
for i in range(3):
    for j in range(2):
        print(i, j)
```

74. **How do you loop through a dictionary in Python?**
    You can loop through a dictionary using its keys or values:

```python
my_dict = {'a': 1, 'b': 2}
for key, value in my_dict.items():
    print(key, value)
```

75. **What is the difference between a `while` loop and a `do-while` loop?**
    Python does not have a `do-while` loop. A `while` loop checks the condition before each iteration, while a `do-while` loop checks the condition after each iteration.

76. **How do you use `else` in a `while` loop?**
    The `else` block in a `while` loop runs after the loop finishes unless the loop is terminated by a `break`:

```python
while condition:
    # code
else:
    # code if loop completed without break
```

77. **How do you check if a string contains a specific substring using `in`?**
    The `in` operator checks if a substring is present in a string:

```python
"hello" in "hello world"  # True
```

78. **What does the `all()` function do in Python?**
    The `all()` function returns `True` if all elements of an iterable are true:

```python
all([True, True, False])  # False
```

79. **What does the `any()` function do in Python?**
    The `any()` function returns `True` if at least one element of an iterable is true:

```python
any([False, True, False])  # True
```

80. **What is the difference between `break` and `continue`?**

* `break` exits the loop entirely.
* `continue` skips the current iteration and proceeds to the next one.

81. **What is a function in Python?**
    A function is a block of reusable code that performs a specific task.

82. **How do you define a function in Python?**
    A function is defined using the `def` keyword:

```python
def my_function():
    print("Hello!")
```

83. **What are function parameters in Python?**
    Parameters are variables defined in the function signature that allow you to pass data into the function.

84. **What is the difference between parameters and arguments in Python?**

* Parameters are the variables in the function definition.
* Arguments are the values passed to the function when it is called.

85. **How do you call a function in Python?**
    You call a function by using its name followed by parentheses:

```python
my_function()
```

86. **What is the `return` statement in Python?**
    The `return` statement is used to return a value from a function:

```python
def add(a, b):
    return a + b
```

87. **How do you define a function with default values for parameters?**
    You can define default values for parameters by assigning them in the function definition:

```python
def greet(name="John"):
    print(f"Hello, {name}!")
```

88. \*\*What are \*args and **kwargs in Python?**

* `*args` allows a function to accept a variable number of positional arguments.
* `**kwargs` allows a function to accept a variable number of keyword arguments.

89. **How do you import a function from another file in Python?**
    You can import functions from another file using the `import` statement:

```python
from module_name import function_name
```

90. **What is a recursive function in Python?**
    A recursive function is a function that calls itself.

91. **How do you create a recursive function in Python?**
    A recursive function is created by calling the function within itself:

```python
def factorial(n):
    if n == 1:
        return 1
    return n * factorial(n-1)
```

92. **What is the base case in a recursive function?**
    The base case is the condition that stops the recursion and prevents an infinite loop.

93. **What happens if there is no base case in a recursive function?**
    If there is no base case, the function will recurse indefinitely and cause a `RecursionError`.

94. **What are the advantages of recursion in Python?**
    Recursion can simplify problems that have a repetitive or nested structure, like tree traversal or searching algorithms.

95. **What are the disadvantages of recursion in Python?**
    Recursion can be less efficient than iteration due to the overhead of function calls and can lead to a stack overflow if the recursion depth is too high.

96. **What is the difference between a local variable and a global variable?**

* A local variable is defined inside a function and can only be accessed within that function.
* A global variable is defined outside any function and can be accessed throughout the program.

97. **What is a lambda function in Python?**
    A lambda function is a small, anonymous function defined using the `lambda` keyword:

```python
square = lambda x: x ** 2
```

98. **How do you define an anonymous function in Python?**
    An anonymous function is defined using the `lambda` keyword. Example:

```python
multiply = lambda x, y: x * y
```

99. **What is the use of the `map()` function?**
    The `map()` function applies a given function to each item in an iterable:

```python
map(lambda x: x * 2, [1, 2, 3])  # [2, 4, 6]
```

100. **How do you use the `filter()` function in Python?**
     The `filter()` function filters elements from an iterable based on a function:

```python
filter(lambda x: x > 0, [-1, 2, 3])  # [2, 3]
```

101. **What is the reduce() function in Python?**
     The `reduce()` function from the `functools` module applies a function cumulatively to the items in an iterable, reducing the iterable to a single value:

```python
from functools import reduce
result = reduce(lambda x, y: x + y, [1, 2, 3, 4])  # Result: 10
```

102. **How do you use the sorted() function to sort a list?**
     The `sorted()` function returns a new sorted list:

```python
numbers = [3, 1, 4, 2]
sorted_numbers = sorted(numbers)  # [1, 2, 3, 4]
```

103. **What does the sum() function do in Python?**
     The `sum()` function returns the sum of all the elements in an iterable:

```python
result = sum([1, 2, 3, 4])  # 10
```

104. **What is a higher-order function in Python?**
     A higher-order function is a function that either takes one or more functions as arguments, or returns a function as its result.

105. **How do you return multiple values from a function?**
     You can return multiple values from a function as a tuple:

```python
def my_function():
    return 1, 2, 3
```

106. **How do you pass a function as an argument to another function?**
     You can pass a function as an argument by simply referencing the function name:

```python
def apply(func, x):
    return func(x)

def square(n):
    return n * n

result = apply(square, 4)  # 16
```

107. **How do you use the all() function in a function?**
     The `all()` function returns `True` if all elements in an iterable are true:

```python
def check_all_positive(numbers):
    return all(num > 0 for num in numbers)
```

108. **How do you use the any() function in a function?**
     The `any()` function returns `True` if at least one element in an iterable is true:

```python
def check_any_negative(numbers):
    return any(num < 0 for num in numbers)
```

109. **How do you handle exceptions in functions?**
     You handle exceptions using a `try-except` block:

```python
def safe_divide(a, b):
    try:
        return a / b
    except ZeroDivisionError:
        return "Cannot divide by zero"
```

110. **How can you define a function to find the factorial of a number?**
     You can define the factorial function using recursion:

```python
def factorial(n):
    if n == 1:
        return 1
    return n * factorial(n - 1)
```

111. **How do you use recursion to find the factorial of a number?**
     The recursive approach to finding the factorial is as follows:

```python
def factorial(n):
    if n == 1:
        return 1
    return n * factorial(n - 1)
```

112. **How can you define a function to find the Fibonacci sequence?**
     You can define a recursive function to calculate the nth Fibonacci number:

```python
def fibonacci(n):
    if n <= 1:
        return n
    return fibonacci(n-1) + fibonacci(n-2)
```

113. **What is recursion in Python?**
     Recursion is a process where a function calls itself to solve a problem by breaking it down into smaller, manageable subproblems.

114. **What is a recursive base case?**
     The base case is a condition that stops the recursion from continuing indefinitely, preventing a stack overflow.

115. **How do you prevent infinite recursion?**
     Infinite recursion can be prevented by ensuring the base case is reachable, i.e., by decrementing the argument toward the base case with each recursive call.

116. **What is the purpose of recursive functions in programming?**
     Recursive functions simplify problems where a task can be broken down into smaller, similar tasks, such as tree traversal or calculating Fibonacci numbers.

117. **Write a Python function that uses recursion to calculate the factorial of a number.**

```python
def factorial(n):
    if n == 1:
        return 1
    return n * factorial(n - 1)
```

118. **Write a Python function that uses recursion to find the Fibonacci number.**

```python
def fibonacci(n):
    if n <= 1:
        return n
    return fibonacci(n-1) + fibonacci(n-2)
```

119. **What is the stack overflow error in recursion?**
     A stack overflow occurs when the recursive function calls exceed the maximum recursion depth, causing the system's call stack to overflow.

120. **What is the time complexity of a recursive function?**
     The time complexity of a recursive function depends on the problem being solved. For example, in the case of Fibonacci, its time complexity is O(2^n) due to repeated calculations.

121. **What is a tail-recursive function?**
     A tail-recursive function is a function where the recursive call is the last operation performed in the function. This allows for optimization by some compilers to prevent stack overflow.

122. **How does recursion differ from iteration?**
     Recursion solves problems by calling the function within itself, while iteration uses loops to repeat a set of operations.

123. **Explain the concept of memoization in recursion.**
     Memoization is a technique to store the results of expensive function calls and reuse them when the same inputs occur again, reducing time complexity.
     
125. **What is a string in Python?**
     A string is a sequence of characters enclosed in quotes, either single or double:

```python
my_string = "Hello"
```

125. **How do you access individual characters in a string?**
     You can access characters using indexing:

```python
my_string = "Hello"
print(my_string[0])  # H
```

126. **How do you slice a string in Python?**
     You can slice a string by specifying the start and end indices:

```python
my_string = "Hello"
print(my_string[1:4])  # ell
```

127. **What is the purpose of the upper() method?**
     The `upper()` method converts all characters in a string to uppercase:

```python
my_string = "hello"
print(my_string.upper())  # HELLO
```

128. **How do you convert a string to lowercase in Python?**
     The `lower()` method converts all characters in a string to lowercase:

```python
my_string = "HELLO"
print(my_string.lower())  # hello
```

129. **What is the find() method used for in strings?**
     The `find()` method returns the lowest index of the substring if found, or -1 if not:

```python
my_string = "hello"
print(my_string.find('e'))  # 1
```

130. **What is the replace() method in strings?**
     The `replace()` method replaces a substring with another substring:

```python
my_string = "hello world"
print(my_string.replace("world", "Python"))  # hello Python
```

131. **How do you split a string into a list in Python?**
     The `split()` method splits a string into a list based on a delimiter:

```python
my_string = "hello world"
print(my_string.split())  # ['hello', 'world']
```

132. **What does the capitalize() method do in Python?**
     The `capitalize()` method capitalizes the first character of a string:

```python
my_string = "hello"
print(my_string.capitalize())  # Hello
```

133. **What is the count() method in Python used for?**
     The `count()` method counts how many times a substring occurs in the string:

```python
my_string = "hello"
print(my_string.count('l'))  # 2
```

134. **How do you check if a string is alphanumeric in Python?**
     The `isalnum()` method checks if all characters in a string are alphanumeric:

```python
my_string = "hello123"
print(my_string.isalnum())  # True
```

135. **What does the isalpha() method check in a string?**
     The `isalpha()` method checks if all characters in the string are alphabetic:

```python
my_string = "hello"
print(my_string.isalpha())  # True
```

136. **What is the purpose of the isdigit() method?**
     The `isdigit()` method checks if all characters in the string are digits:

```python
my_string = "123"
print(my_string.isdigit())  # True
```

137. **What is the join() method used for in Python?**
     The `join()` method concatenates the elements of an iterable into a single string, separated by a specified delimiter:

```python
my_list = ['hello', 'world']
print(" ".join(my_list))  # hello world
```

138. **What is the isspace() method in strings?**
     The `isspace()` method checks if all characters in a string are whitespace:

```python
my_string = "   "
print(my_string.isspace())  # True
```

139. **How do you check if a string is a number in Python?**
     You can check if a string is a number by using `isdigit()`:

```python
my_string = "123"
print(my_string.isdigit())  # True
```

140. **How do you concatenate two strings?**
     You concatenate strings using the `+` operator:

```python
string1 = "Hello"
string2 = "World"
result = string1 + " " + string2
```
141. **What is the len() function used for with strings?**
     The `len()` function returns the number of characters in a string:

```python
my_string = "hello"
print(len(my_string))  # 5
```

142. **What is the difference between split() and join() methods in Python?**

* `split()` breaks a string into a list based on a delimiter.
* `join()` concatenates a list of strings into a single string with a delimiter.

143. **How do you find the position of a substring in a string?**
     You can use the `find()` method to get the index of the substring:

```python
my_string = "hello"
print(my_string.find("e"))  # 1
```

144. **What is a list in Python?**
     A list is an ordered collection of elements that can be of any type:

```python
my_list = [1, 2, 3, 4]
```

145. **How do you create a list in Python?**
     A list is created using square brackets:

```python
my_list = [1, 2, 3]
```

146. **How do you access elements in a list?**
     Elements in a list are accessed using indexing:

```python
my_list = [1, 2, 3]
print(my_list[0])  # 1
```

147. **How do you update an element in a list?**
     You can update an element by assigning a new value to the index:

```python
my_list = [1, 2, 3]
my_list[1] = 10
print(my_list)  # [1, 10, 3]
```

148. **How do you add elements to a list in Python?**
     You can use `append()`, `insert()`, or `extend()` to add elements to a list:

```python
my_list = [1, 2]
my_list.append(3)  # [1, 2, 3]
```

149. **What is the append() method in Python?**
     The `append()` method adds a single element to the end of the list:

```python
my_list = [1, 2]
my_list.append(3)  # [1, 2, 3]
```

150. **What does the extend() method do in a list?**
     The `extend()` method adds multiple elements from an iterable to the end of the list:

```python
my_list = [1, 2]
my_list.extend([3, 4])  # [1, 2, 3, 4]
```

151. **What is the difference between append() and extend()?**

* `append()` adds a single element to the list.
* `extend()` adds elements from another iterable (e.g., a list) to the list.

152. **How do you remove elements from a list?**
     You can use `remove()`, `pop()`, or `del` to remove elements:

```python
my_list = [1, 2, 3]
my_list.remove(2)  # [1, 3]
```

153. **How do you delete an element at a specific index in a list?**
     You can use `del` or `pop()` to delete an element by index:

```python
my_list = [1, 2, 3]
del my_list[1]  # [1, 3]
```

154. **What does the pop() method do in a list?**
     The `pop()` method removes and returns the element at a specified index (default is the last item):

```python
my_list = [1, 2, 3]
item = my_list.pop()  # 3
```

155. **How do you reverse a list in Python?**
     The `reverse()` method reverses the elements in the list:

```python
my_list = [1, 2, 3]
my_list.reverse()  # [3, 2, 1]
```

156. **How do you find the length of a list in Python?**
     The `len()` function returns the number of elements in a list:

```python
my_list = [1, 2, 3]
print(len(my_list))  # 3
```

157. **What is list slicing in Python?**
     List slicing allows you to get a subset of a list:

```python
my_list = [1, 2, 3, 4]
print(my_list[1:3])  # [2, 3]
```

158. **How do you check if an item exists in a list?**
     You can use the `in` keyword to check for membership:

```python
my_list = [1, 2, 3]
print(2 in my_list)  # True
```

159. **How do you concatenate two lists in Python?**
     You can concatenate lists using the `+` operator:

```python
list1 = [1, 2]
list2 = [3, 4]
result = list1 + list2  # [1, 2, 3, 4]
```

160. **How do you create a list with a range of numbers?**
     Use the `range()` function with `list()` to create a list of numbers:

```python
my_list = list(range(1, 5))  # [1, 2, 3, 4]
```

161. **What is list comprehension and how do you use it?**
     List comprehension provides a concise way to create lists:

```python
my_list = [x * 2 for x in range(5)]  # [0, 2, 4, 6, 8]
```

162. **What is the difference between a list and a tuple?**

* Lists are mutable (can be changed), while tuples are immutable.
* Lists use square brackets, tuples use parentheses:

  ```python
  my_list = [1, 2]
  my_tuple = (1, 2)
  ```

163. **How do you sort a list in Python?**
     You can use the `sort()` method to sort the list in place or `sorted()` to return a new sorted list:

```python
my_list = [3, 1, 2]
my_list.sort()  # [1, 2, 3]
```

164. **How do you find the index of an element in a list?**
     Use the `index()` method to get the index of an element:

```python
my_list = [1, 2, 3]
print(my_list.index(2))  # 1
```

165. **How do you find the maximum and minimum value in a list?**
     Use `max()` and `min()` to find the maximum and minimum values:

```python
my_list = [1, 2, 3]
print(max(my_list))  # 3
print(min(my_list))  # 1
```

166. **What is the remove() method used for in lists?**
     The `remove()` method removes the first occurrence of a value from the list:

```python
my_list = [1, 2, 3]
my_list.remove(2)  # [1, 3]
```

167. **How do you check if a list is empty?**
     You can check if a list is empty using `not` or `len()`:

```python
my_list = []
print(not my_list)  # True
```

168. **How do you clear all elements from a list?**
     Use the `clear()` method to remove all elements from the list:

```python
my_list = [1, 2]
my_list.clear()  # []
```

169. **What is the count() method used for in lists?**
     The `count()` method returns the number of occurrences of an element in the list:

```python
my_list = [1, 1, 2]
print(my_list.count(1))  # 2
```

170. **How do you make a copy of a list?**
     You can make a copy of a list using slicing or `copy()`:

```python
my_list = [1, 2, 3]
copy_list = my_list[:]
```

171. **What is the insert() method used for in a list?**
     The `insert()` method adds an element at a specific index:

```python
my_list = [1, 2, 3]
my_list.insert(1, 4)  # [1, 4, 2, 3]
```

172. **How do you convert a list to a string in Python?**
     You can use the `join()` method to convert a list of strings into a single string:

```python
my_list = ['a', 'b', 'c']
result = ''.join(my_list)  # 'abc'
```
186. **What is a dictionary in Python?**
     A dictionary is an unordered collection of key-value pairs, where each key is unique:

```python
my_dict = {'name': 'John', 'age': 30}
```

187. **How do you create a dictionary in Python?**
     A dictionary is created using curly braces `{}` with key-value pairs:

```python
my_dict = {'key1': 'value1', 'key2': 'value2'}
```

188. **How do you access values in a dictionary?**
     You can access values using their keys:

```python
my_dict = {'name': 'John', 'age': 30}
print(my_dict['name'])  # John
```

189. **How do you add an item to a dictionary?**
     You can add an item by assigning a value to a new key:

```python
my_dict = {'name': 'John'}
my_dict['age'] = 30
print(my_dict)  # {'name': 'John', 'age': 30}
```

190. **How do you update an item in a dictionary?**
     You can update a dictionary item by assigning a new value to an existing key:

```python
my_dict = {'name': 'John', 'age': 30}
my_dict['age'] = 31
print(my_dict)  # {'name': 'John', 'age': 31}
```

191. **How do you remove an item from a dictionary?**
     You can remove an item using `del`, `pop()`, or `popitem()`:

```python
my_dict = {'name': 'John', 'age': 30}
del my_dict['age']
print(my_dict)  # {'name': 'John'}
```

192. **How do you check if a key exists in a dictionary?**
     You can use the `in` operator to check if a key exists:

```python
my_dict = {'name': 'John', 'age': 30}
print('name' in my_dict)  # True
```

193. **What is the get() method used for in dictionaries?**
     The `get()` method retrieves the value for a given key, returning `None` if the key is not found:

```python
my_dict = {'name': 'John', 'age': 30}
print(my_dict.get('name'))  # John
print(my_dict.get('address'))  # None
```

194. **How do you get all keys from a dictionary?**
     You can use the `keys()` method to get all the keys:

```python
my_dict = {'name': 'John', 'age': 30}
print(my_dict.keys())  # dict_keys(['name', 'age'])
```

195. **How do you get all values from a dictionary?**
     You can use the `values()` method to get all the values:

```python
my_dict = {'name': 'John', 'age': 30}
print(my_dict.values())  # dict_values(['John', 30])
```

196. **How do you iterate over a dictionary?**
     You can iterate over keys, values, or key-value pairs using a `for` loop:

```python
my_dict = {'name': 'John', 'age': 30}
for key, value in my_dict.items():
    print(key, value)
```

197. **What is the difference between items(), keys(), and values() in a dictionary?**

* `items()` returns a list of key-value pairs.
* `keys()` returns a list of keys.
* `values()` returns a list of values.

198. **How do you merge two dictionaries?**
     You can use the `update()` method or the `**` unpacking operator:

```python
dict1 = {'name': 'John'}
dict2 = {'age': 30}
dict1.update(dict2)
# or
merged_dict = {**dict1, **dict2}
```

199. **What is the pop() method in dictionaries?**
     The `pop()` method removes and returns the value for the specified key:

```python
my_dict = {'name': 'John', 'age': 30}
value = my_dict.pop('age')  # 30
print(my_dict)  # {'name': 'John'}
```

200. **How do you create a dictionary with default values?**
     You can use the `defaultdict` class from the `collections` module, or the `get()` method with a default value:

```python
from collections import defaultdict
my_dict = defaultdict(int)
print(my_dict['non_existing_key'])  # 0

# Or with get():
my_dict = {'name': 'John'}
print(my_dict.get('age', 25))  # 25 (default value)
```
201. **What is a tuple in Python?**
     A tuple is an immutable ordered collection of items in Python.

203. **How do you create a tuple in Python?**
     Use parentheses: `t = (1, 2, 3)`

204. **What is the difference between a list and a tuple?**
     Lists are mutable (can change), whereas tuples are immutable (cannot change).

205. **How do you access elements in a tuple?**
     Using indexing: `t[0]` accesses the first element.

206. **How do you find the length of a tuple?**
     Use the `len()` function: `len(t)`

207. **How do you concatenate two tuples?**
     Using the `+` operator: `t1 + t2`

208. **Can you modify the values of a tuple?**
     No, tuples are immutable and cannot be modified after creation.

209. **How do you convert a tuple to a list in Python?**
     Use `list()` function: `list(t)`

210. **How do you create a tuple with one item?**
     Include a trailing comma: `t = (5,)`

211. **What is tuple unpacking in Python?**
     Assigning tuple elements to variables: `a, b = (1, 2)`

212. **How do you iterate over a tuple?**
     Using a `for` loop:

```python
for item in t:
    print(item)
```

212. **How do you find the index of an element in a tuple?**
     Use `t.index(value)`

213. **What is the count() method used for in tuples?**
     Returns the number of times a value appears: `t.count(2)`

214. **What is the index() method used for in tuples?**
     Returns the index of the first occurrence of a value.

215. **How do you concatenate a tuple with a list?**
     Convert one to the other type first. Example: `tuple(list(t1) + lst)`

216. **How do you create a tuple with repeated elements?**
     Use multiplication: `t = (0,) * 5` creates `(0, 0, 0, 0, 0)`

217. **How do you check if an item exists in a tuple?**
     Use `in` keyword: `if item in t:`

218. **What is the immutability of a tuple in Python?**
     Once created, a tuple cannot be modified.

219. **What are named tuples in Python?**
     Tuples with named fields for better readability, defined using `collections.namedtuple()`.

220. **How do you create a named tuple in Python?**\\

```python
from collections import namedtuple
Point = namedtuple('Point', 'x y')
p = Point(1, 2)
```

221. **What are the advantages of using tuples over lists?**
     Tuples use less memory, are faster, and are safe from modification.

222. **How do you convert a list to a tuple in Python?**
     Use `tuple()` function: `tuple(lst)`

223. **Can you delete an item from a tuple?**
     No, tuples are immutable. You can delete the entire tuple with `del`.

224. **How do you convert a tuple to a string in Python?**
     Use `str()` or `"".join(t)` if it contains strings.

225. **What is object-oriented programming (OOP) in Python?**
     A programming paradigm based on the concept of objects containing data and methods.

226. **What is the difference between a class and an object in Python?**
     A class is a blueprint, and an object is an instance of the class.

227. **How do you define a class in Python?**
     Use the `class` keyword:

```python
class Person:
    pass
```

228. **How do you create an instance of a class in Python?**
     By calling the class name: `p = Person()`

229. **What is the **init**() method used for in Python?**
     It initializes a newly created object.

230. **What are attributes in Python classes?**
     Variables that belong to an object or class.

231. **What is inheritance in Python?**
     The ability of a class to derive properties and methods from another class.

232. **What is method overriding in Python?**
     Redefining a method in the child class that exists in the parent class.

233. **What is method overloading in Python?**
     Python does not support method overloading directly. It can be simulated using default arguments.

234. **What is polymorphism in Python?**
     The ability to use a shared interface for different data types or classes.

235. **What is data hiding in Python classes?**
     Hiding internal object details using name mangling (`__var`).

236. **How do you destroy an object in Python?**
     By using the `del` keyword or when the object goes out of scope.

237. **How do you access a class attribute in Python?**
     Use `object.attribute` or `ClassName.attribute`

238. **How do you define a class method in Python?**
     Use `@classmethod` decorator and `cls` parameter.

239. **What are class variables in Python?**
     Variables shared among all instances of a class.

240. **What are instance variables in Python?**
     Variables unique to each object instance.
     
242. **What is the difference between = and == in Python?**

     * `=` is the assignment operator, used to assign a value to a variable.
     * `==` is the equality operator, used to compare two values.

243. **What are keywords in Python?**
     * Keywords are reserved words in Python that have special meaning, such as `if`, `else`, `while`, `for`, `class`, etc. These cannot be used as identifiers (variable names).

244. **How do you declare a variable in Python?**
     * You declare a variable by simply assigning it a value, like so: `x = 10`.

245. **What is the purpose of the input() function in Python?**
     * `input()` is used to get user input from the console. The input is returned as a string.

246. **How do you print text to the console in Python?**
     * Use the `print()` function: `print("Hello, World!")`

247. **What is an expression in Python?**
     * An expression is any valid combination of operators and operands that Python can evaluate to produce a value, like `2 + 3` or `x * y`.

248. **What is a statement in Python?**
     * A statement is a line of code that performs an action, such as a variable assignment or a function call.

249. **What is the order of operations in Python?**
     * Python follows the standard mathematical precedence: Parentheses > Exponents > Multiplication/Division > Addition/Subtraction.

250. **What is a literal in Python?**
     * A literal is a value that is directly written into the code, such as `42`, `"Hello"`, or `3.14`.

251. **What is the purpose of comments in Python?**
     * Comments are used to explain code and make it more readable. They are ignored by the Python interpreter.

252. **What is the syntax to write a comment in Python?**
     * A comment starts with a `#`: `# This is a comment`

253. **How do you convert data types in Python?**
     * Use type conversion functions, like `int()`, `float()`, `str()`, etc.
       Example: `x = int("10")`

254. **What is the str() function used for?**
     * The `str()` function converts a value to a string.

255. **What are operators in Python?**
     * Operators are symbols used to perform operations on variables and values, such as `+`, `-`, `*`, `/`, etc.

256. **What is the modulus operator % used for?**
     * The modulus operator returns the remainder of the division of two numbers. Example: `7 % 3` gives `1`.

257. **What is the id() function used for in Python?**
     * `id()` returns the unique identifier of an object in memory.

258. **What are comparison operators in Python?**
     * Comparison operators are used to compare two values, such as `==`, `!=`, `<`, `>`, `<=`, `>=`.

259. **What are logical operators in Python?**
     * Logical operators include `and`, `or`, and `not`, used to combine conditional expressions.

260. **What is the purpose of and, or, and not in Python?**
     * `and`: returns `True` if both conditions are `True`.
     * `or`: returns `True` if at least one condition is `True`.
     * `not`: reverses the result, returns `True` if the condition is `False`.

261. **What are the assignment operators in Python?**
     * Assignment operators include `=`, `+=`, `-=`, `*=`, `/=`, etc., used to assign and update values.

261. **What is the purpose of an if statement in Python?**
     * An `if` statement allows you to execute code only if a condition is `True`.

262. **How do you use an if-else statement in Python?**
     * An `if-else` statement provides an alternative block of code when the condition is `False`.
       Example:

```python
if x > 10:
    print("x is greater than 10")
else:
    print("x is not greater than 10")
```

263. **What is the syntax of the if-elif-else statement?**
     * The `elif` statement is used to check multiple conditions, and `else` is the fallback if no conditions are met.
       Example:

```python
if x > 10:
    print("Greater")
elif x == 10:
    print("Equal")
else:
    print("Smaller")
```

264. **How do you use nested conditions in Python?**
     * Nested conditions involve placing one `if` statement inside another.
       Example:

```python
if x > 10:
    if x < 20:
        print("x is between 10 and 20")
```

265. **What is the break statement used for in Python loops?**
     * The `break` statement terminates the loop prematurely.

266. **What is the continue statement used for in loops?**
     * The `continue` statement skips the current iteration and moves to the next one.

267. **What is the purpose of a while loop in Python?**
     * A `while` loop repeatedly executes code as long as a condition is `True`.

268. **How does a for loop work in Python?**
     * A `for` loop iterates over a sequence (like a list or tuple) and executes a block of code for each item.

269. **What is the difference between for and while loops?**
     * A `for` loop is typically used when the number of iterations is known, while a `while` loop runs as long as a condition is `True`.

270. **How do you iterate over a string using a loop?**
     * Use a `for` loop to iterate over each character in the string:

```python
for char in "hello":
    print(char)
```

271. **What is the range() function used for in loops?**
     * `range()` generates a sequence of numbers, often used to control the number of iterations in a loop.

272. **What is a nested loop?**
     * A nested loop is a loop inside another loop. It is useful when iterating over multi-dimensional structures, like lists of lists.

273. **How do you use else with a loop in Python?**
     * An `else` block can be used after a loop to execute code if the loop completes without hitting a `break` statement.

274. **What is a Boolean expression in Python?**
     * A Boolean expression is an expression that evaluates to `True` or `False`.

275. **What is the modulus operator used for in Python?**
     * The modulus operator (`%`) returns the remainder of a division.

276. **What is the use of logical operators in conditions?**
     * Logical operators combine multiple conditions to form a complex condition.

277. **What is short-circuiting in logical operators?**
     * Short-circuiting occurs when Python stops evaluating a logical expression as soon as the result is determined (e.g., `True and ...` stops evaluating because it’s already `True`).

278. **How do you create a while loop that runs indefinitely?**
     * Use `while True:` to create an infinite loop, often used in server programs or when waiting for user input.

279. **How do you use a for loop to iterate over a list?**
     * You can iterate over a list using a `for` loop, like so:

```python
for item in my_list:
    print(item)
```

280. **What is an infinite loop in Python?**
     * An infinite loop is a loop that never ends unless externally interrupted or broken using a `break` statement.
       
281. **What is a function in Python?**
     * A function is a block of reusable code that performs a specific task. Functions help in making code modular and more manageable.

282. **How do you define a function in Python?**
     * Functions are defined using the `def` keyword, followed by the function name and parameters.
       Example:

```python
def greet(name):
    print(f"Hello, {name}!")
```

283. **What are parameters in a Python function?**
     * Parameters are variables listed in the function definition, which receive values when the function is called.

284. **What are arguments in a Python function?**
     * Arguments are the actual values passed to the function when calling it.

285. **What is the difference between parameters and arguments?**
     * Parameters are placeholders in the function definition, while arguments are the actual values passed during the function call.

286. **What is the return statement used for in functions?**
     * The `return` statement is used to exit the function and return a value to the caller.

287. **How do you call a function in Python?**
     * To call a function, simply use the function name followed by parentheses, optionally passing arguments.
       Example: `greet("Alice")`

288. **What are default arguments in Python functions?**
     * Default arguments are parameters that take a predefined value if no argument is passed when calling the function.
       Example:

```python
def greet(name="Guest"):
    print(f"Hello, {name}!")
```

289. **What is a recursive function in Python?**
     * A recursive function is one that calls itself in order to solve a problem by breaking it down into smaller subproblems.

290. **What are the advantages of recursion?**
     * Recursion allows for elegant solutions to problems that have a natural recursive structure, such as tree traversal, factorial calculation, and Fibonacci numbers.

291. **What are the disadvantages of recursion?**
     * Recursion can lead to high memory usage due to function call stack, and it may result in stack overflow if the base case is not defined or if the recursion depth is too deep.

292. **What is the base case in a recursive function?**
     * The base case is the condition that stops the recursion, preventing infinite recursion.

293. **How do you avoid recursion errors in Python?**
     * Ensure that the base case is well-defined and that recursion moves towards it in each call.

294. **What is the max() function used for in Python?**
     * The `max()` function returns the largest item from an iterable or from two or more arguments.

295. **What is the min() function used for in Python?**
     * The `min()` function returns the smallest item from an iterable or from two or more arguments.

296. **What is the round() function used for in Python?**
     * The `round()` function rounds a floating-point number to the nearest integer or to a specified number of decimal places.

297. **What is the abs() function used for in Python?**
     * The `abs()` function returns the absolute value of a number, i.e., its distance from zero.

298. **What is the pow() function in Python?**
     * The `pow()` function returns the value of a number raised to the power of another number. It also has an optional third argument for modulus.

299. **What are the built-in mathematical functions in Python?**
     * Some common built-in mathematical functions include `abs()`, `max()`, `min()`, `pow()`, `round()`, `sum()`, and `divmod()`.

300. **How do you import a function from another module?**
     * Use the `import` statement to include functions from other modules.
       Example:

```python
from math import sqrt
```
the `min()` function on the values: `min(d.values())`.

360. **What is the difference between del and pop() in dictionaries?**
* `del` removes a key-value pair, and `pop()` also removes and returns the value associated with the key.

361. **How do you create a tuple in Python?**
* Use parentheses: `t = (1, 2, 3)`.

362. **How do you access elements in a tuple?**
* Use indexing: `t[0]`.

363. **How do you find the length of a tuple?**
* Use the `len()` function: `len(t)`.

364. **Can you modify the contents of a tuple in Python?**
* No, tuples are immutable. You cannot change their contents.

365. **How do you concatenate two tuples?**
* Use the `+` operator: `t1 + t2`.

366. **How do you check if an item exists in a tuple?**
* Use the `in` keyword: `item in t`.

367. **What is tuple unpacking in Python?**
* Tuple unpacking allows you to assign the values in a tuple to separate variables.
  Example:

  ```python
  t = (1, 2, 3)
  a, b, c = t
  ```

368. **How do you convert a list to a tuple?**
* Use the `tuple()` function: `t = tuple(lst)`.

369. **How do you create a tuple with one item?**
* Add a comma after the item: `t = (1,)`.

370. **How do you iterate through a tuple?**
* Use a `for` loop:

```python
for item in t:
    print(item)
```

371. **What is the difference between a tuple and a list in Python?**
* Tuples are immutable (cannot be changed), while lists are mutable (can be changed).

372. **How do you check if a tuple contains duplicate elements?**
* Convert the tuple to a set and compare the lengths:

```python
len(t) != len(set(t))
```

373. **How do you find the maximum and minimum values in a tuple?**
* Use the `max()` and `min()` functions:
  `max(t)` and `min(t)`.

374. **What is the count() method used for in tuples?**
* The `count()` method returns the number of occurrences of a specified value in a tuple.
* 
375. **How do you convert a tuple to a string in Python?**
* Use the `join()` method after converting the tuple elements to strings:

```python
''.join(map(str, t))
```

376. **How do you remove an item from a tuple?**
* Tuples are immutable, so you cannot remove items directly. You can create a new tuple with the items you want to keep.

377. **What is the index() method used for in tuples?**
* The `index()` method returns the index of the first occurrence of a specified element in the tuple.

378. **How do you slice a tuple in Python?**
* Use slicing syntax: `t[start:end]`.

379. **What is a nested tuple?**
* A nested tuple is a tuple that contains other tuples as elements.

380. **How do you create a tuple from a string?**
* Use the `tuple()` function: `tuple('string')`.

---

***Module 2***

1. **Q:** What is Object‑Oriented Programming (OOP)?
   **A:** A paradigm organizing code into “objects” that bundle data (attributes) and behavior (methods).

2. **Q:** What is a class?
   **A:** A blueprint for creating objects, defined with the `class` keyword.

3. **Q:** How do you declare a simple class in Python?
   **A:**

   ```python
   class MyClass:
       pass
   ```

4. **Q:** What is an instance?
   **A:** A concrete object created from a class, e.g. `obj = MyClass()`.

5. **Q:** How do you initialize instance attributes?
   **A:** In the `__init__` method:

   ```python
   class Person:
       def __init__(self, name):
           self.name = name
   ```

6. **Q:** What is the `self` parameter?
   **A:** A reference to the current instance, used to access attributes/methods.

7. **Q:** How do you access an attribute?
   **A:** Using dot notation: `obj.attribute_name`.

8. **Q:** How do you define a method?
   **A:** Inside a class, with `def`, e.g.

   ```python
   def greet(self):
       print(f"Hello, {self.name}")
   ```

9. **Q:** What are built‑in class attributes?
   **A:** Special attributes provided by Python:

   * `__name__`, `__doc__`, `__module__`, `__dict__`, `__bases__`.

10. **Q:** How can you inspect an object’s namespace?
    **A:** Using `obj.__dict__` (instance) or `ClassName.__dict__` (class).

11. **Q:** What is a destructor in Python?
    **A:** The `__del__` method, called when an object is about to be destroyed.

12. **Q:** Why is relying on `__del__` discouraged?
    **A:** Its execution timing isn’t guaranteed due to garbage collection.

13. **Q:** How does Python destroy objects?
    **A:** Via reference counting and garbage collection when no references remain.

14. **Q:** What is inheritance?
    **A:** A mechanism for a class (child) to inherit attributes/methods from another (parent).

15. **Q:** How do you express single inheritance?
    **A:**

    ```python
    class Child(Parent):
        pass
    ```

16. **Q:** What is multiple inheritance?
    **A:** A class inheriting from more than one parent:

    ```python
    class C(A, B):
        pass
    ```

17. **Q:** What is method overriding?
    **A:** Redefining a parent’s method in a child class to change behavior.

18. **Q:** What is method overloading in Python?
    **A:** Python doesn’t support true overloading; simulate with default args or `*args, **kwargs`.

19. **Q:** How do you call a parent class’s method from a child?
    **A:** Using `super()`, e.g. `super().method_name()`.

20. **Q:** What is a class attribute?
    **A:** A variable defined in the class body, shared by all instances.

21. **Q:** How do you define a private attribute?
    **A:** Prefix name with double underscore: `self.__secret`.

22. **Q:** What is name mangling?
    **A:** Python rewrites `__attr` to `_ClassName__attr` to prevent external access.

23. **Q:** How do you access a mangled attribute?
    **A:** By its mangled name: `obj._ClassName__secret`.

24. **Q:** What is encapsulation?
    **A:** Hiding internal state and requiring all interaction through methods.

25. **Q:** What is data hiding?
    **A:** Restricting access to attributes (using single `_` or double `__` prefixes).

26. **Q:** What is polymorphism?
    **A:** The ability for different classes to be treated through a common interface.

27. **Q:** Give an example of polymorphism.
    **A:** Both `list` and `tuple` support `len()`, so you can write code that works with any sequence.

28. **Q:** What is an abstract class?
    **A:** A class that can’t be instantiated, defined using the `abc` module.

29. **Q:** How do you declare an abstract method?
    **A:**

    ```python
    from abc import ABC, abstractmethod

    class MyBase(ABC):
        @abstractmethod
        def do_something(self):
            pass
    ```

30. **Q:** What happens if you don’t implement all abstract methods?
    **A:** You cannot instantiate the subclass until all are overridden.

31. **Q:** What is a mixin class?
    **A:** A class designed to add reusable functionality through multiple inheritance.

32. **Q:** How can you check if an object is an instance of a class?
    **A:** Using `isinstance(obj, ClassName)`.

33. **Q:** How can you check class inheritance?
    **A:** Using `issubclass(Child, Parent)`.

34. **Q:** What is a static method?
    **A:** A method that doesn’t receive `self` or `cls`, defined with `@staticmethod`.

35. **Q:** What is a class method?
    **A:** A method that receives the class as first argument, decorated with `@classmethod`.

36. **Q:** When would you use a static method?
    **A:** For utility functions related to the class but not to any instance.

37. **Q:** When would you use a class method?
    **A:** To create alternate constructors or methods that operate on the class itself.

38. **Q:** How do you define an alternate constructor?
    **A:** With a `@classmethod`, e.g.:

    ```python
    @classmethod
    def from_string(cls, data_str):
        return cls(*data_str.split(','))
    ```

39. **Q:** What is composition?
    **A:** Building classes that contain instances of other classes (has‑a relationship).

40. **Q:** How does composition differ from inheritance?
    **A:** Composition delegates tasks to contained objects; inheritance reuses code via subclassing.

41. **Q:** Give an example of composition.
    **A:**

    ```python
    class Engine: ...
    class Car:
        def __init__(self):
            self.engine = Engine()
    ```

42. **Q:** What is duck typing?
    **A:** “If it quacks like a duck…”—Python’s dynamic typing lets you use any object with the right methods/attributes.

43. **Q:** How do you enforce read‑only attributes?
    **A:** Use a property with only a getter:

    ```python
    @property
    def value(self):
        return self._value
    ```

44. **Q:** How do you define a property setter?
    **A:**

    ```python
    @value.setter
    def value(self, new):
        self._value = new
    ```

45. **Q:** What is the `__slots__` declaration?
    **A:** Restricts allowed attributes and can reduce memory footprint.

46. **Q:** When should you use `__slots__`?
    **A:** For many instances of simple classes where you want to save memory.

47. **Q:** What is operator overloading?
    **A:** Defining special methods (`__add__`, `__lt__`, etc.) to customize operators.

48. **Q:** How do you overload the addition operator?
    **A:**

    ```python
    def __add__(self, other):
        return SomeClass(self.value + other.value)
    ```

49. **Q:** What is method resolution order (MRO)?
    **A:** The order Python uses to look up methods, accessed via `ClassName.__mro__`.

50. **Q:** How do you display a user‑friendly class representation?
    **A:** Implement `__str__`; for unambiguous repr use `__repr__`.

Here are questions **51–100** on **Python Exceptions & Regular Expressions**:

51. **Q:** What is an exception in Python?
    **A:** An event raised during execution when an error occurs, interrupting normal flow.

52. **Q:** How do you catch exceptions?
    **A:** With a `try…except` block:

    ```python
    try:
        # code
    except SomeError:
        # handler
    ```

53. **Q:** What does the `else` clause do in exception handling?
    **A:** Runs if no exception was raised in the `try` block.

54. **Q:** What is the purpose of the `finally` clause?
    **A:** Executes cleanup code whether or not an exception occurred.

55. **Q:** How do you catch multiple exception types in one block?
    **A:** Pass a tuple to `except`:

    ```python
    except (TypeError, ValueError):
        # handler
    ```

56. **Q:** How can you access the exception object?
    **A:** Using `as`, e.g. `except ValueError as e:`.

57. **Q:** What happens if an exception isn’t caught?
    **A:** It propagates up the call stack and, if uncaught, terminates the program.

58. **Q:** How do you raise an exception?
    **A:** Using `raise`, e.g. `raise ValueError("Bad value")`.

59. **Q:** How do you define a custom exception class?
    **A:** Inherit from `Exception`:

    ```python
    class MyError(Exception):
        pass
    ```

60. **Q:** How can you add additional attributes to a user‑defined exception?
    **A:** Extend `__init__`:

    ```python
    class MyError(Exception):
        def __init__(self, msg, code):
            super().__init__(msg)
            self.code = code
    ```

61. **Q:** What built‑in exception is raised for division by zero?
    **A:** `ZeroDivisionError`.

62. **Q:** Which exception is raised when a key is missing in a dict?
    **A:** `KeyError`.

63. **Q:** Which exception indicates an invalid type operation?
    **A:** `TypeError`.

64. **Q:** Which exception indicates conversion failure?
    **A:** `ValueError`.

65. **Q:** How do you re‑raise the current exception?
    **A:** Call `raise` with no arguments inside an `except`.

66. **Q:** What module provides regular expression support?
    **A:** The built‑in `re` module.

67. **Q:** How do you check if a pattern matches at the start of a string?
    **A:** `re.match(pattern, string)`.

68. **Q:** How do you search for a pattern anywhere in a string?
    **A:** `re.search(pattern, string)`.

69. **Q:** What method returns all non‑overlapping matches?
    **A:** `re.findall(pattern, string)`.

70. **Q:** How do you iterate over match objects?
    **A:** Use `re.finditer(pattern, string)`.

71. **Q:** How do you replace matches with a substring?
    **A:** `re.sub(pattern, repl, string)`.

72. **Q:** How do you split a string by a regex?
    **A:** `re.split(pattern, string)`.

73. **Q:** What character matches any digit?
    **A:** `\d`.

74. **Q:** What matches any whitespace character?
    **A:** `\s`.

75. **Q:** What matches any word character (alphanumeric plus underscore)?
    **A:** `\w`.

76. **Q:** How do you specify “zero or more” of the preceding item?
    **A:** Using `*` quantifier.

77. **Q:** How do you specify “one or more”?
    **A:** Using `+` quantifier.

78. **Q:** How do you specify “zero or one”?
    **A:** Using `?` quantifier.

79. **Q:** What is the difference between greedy and non‑greedy quantifiers?
    **A:** Greedy (`*`, `+`) match as much as possible; non‑greedy (`*?`, `+?`) match as little as possible.

80. **Q:** How do you group subpatterns?
    **A:** With parentheses: `(abc)`.

81. **Q:** What is a named group?
    **A:** A group with an identifier: `(?P<name>pattern)`.

82. **Q:** How do you refer back to a captured group in the pattern?
    **A:** Using `\1`, `\2`, etc., or `(?P=name)` for named groups.

83. **Q:** How do you compile a regex for reuse?
    **A:** `pattern = re.compile('...')`.

84. **Q:** How do you apply flags when compiling?
    **A:** Pass flags: `re.compile('...', re.I | re.M)`.

85. **Q:** What does `re.I` (or `re.IGNORECASE`) do?
    **A:** Makes matching case‑insensitive.

86. **Q:** What does `re.M` (or `re.MULTILINE`) do?
    **A:** `^` and `$` match the start/end of each line.

87. **Q:** What does `re.S` (or `re.DOTALL`) do?
    **A:** Lets `.` match newline characters.

88. **Q:** How do you ensure the pattern matches the entire string?
    **A:** Use `^pattern$`.

89. **Q:** What is a raw string literal and why use it in regex?
    **A:** Prefix with `r'...'` to avoid escaping backslashes twice.

90. **Q:** How do you escape a metacharacter to match it literally?
    **A:** Prefix with backslash, e.g. `\.` to match a dot.

91. **Q:** How do you use lookahead assertions?
    **A:**

    * Positive: `(?=pattern)`
    * Negative: `(?!pattern)`

92. **Q:** How do you use lookbehind assertions?
    **A:**

    * Positive: `(?<=pattern)`
    * Negative: `(?<!pattern)`

93. **Q:** What function returns a match object?
    **A:** Both `re.match()` and `re.search()`.

94. **Q:** How do you get the matched text from a match object?
    **A:** Use `.group()`, `.group(0)` or `.group(n)` for groups.

95. **Q:** How do you find the start and end positions of a match?
    **A:** Use `.start()`, `.end()` on the match object.

96. **Q:** How do you get a dictionary of named groups from a match?
    **A:** `.groupdict()`.

97. **Q:** How can you perform a substitution using a function?
    **A:** Pass a function as `re.sub(pattern, func, string)` where `func` receives a match.

98. **Q:** How do you remove all whitespace from a string using regex?
    **A:** `re.sub(r'\s+', '', text)`.

99. **Q:** How do you split on comma but ignore commas inside quotes?
    **A:** Use a pattern like `,(?=(?:[^"]*"[^"]*")*[^"]*$)`.

100. **Q:** How do you validate an email address with regex?
     **A:** Example pattern:
     `python
         r'^[\w\.-]+@[\w\.-]+\.\w+$'
         `
Here are questions **101–150** on **File Operations & Stacks/Queues**:

101. **Q:** How do you open a file for reading?
     **A:** `open('filename.txt', 'r')`

102. **Q:** How do you open a file for writing (overwriting)?
     **A:** `open('filename.txt', 'w')`

103. **Q:** How do you open a file for appending?
     **A:** `open('filename.txt', 'a')`

104. **Q:** How do you open a file for both reading and writing?
     **A:** `open('filename.txt', 'r+')`

105. **Q:** What mode opens a file in binary read mode?
     **A:** `'rb'`

106. **Q:** What mode opens a file in binary write mode?
     **A:** `'wb'`

107. **Q:** How do you read the entire contents of a file at once?
     **A:** `file.read()`

108. **Q:** How do you read one line from a file?
     **A:** `file.readline()`

109. **Q:** How do you read all lines into a list?
     **A:** `file.readlines()`

110. **Q:** How do you iterate over a file line by line?
     **A:**

     ```python
     for line in file:
         # process line
     ```

111. **Q:** How do you write a string to a file?
     **A:** `file.write('some text')`

112. **Q:** How do you write multiple lines at once?
     **A:** `file.writelines(['line1\n', 'line2\n'])`

113. **Q:** How do you move the file cursor to the beginning?
     **A:** `file.seek(0)`

114. **Q:** How do you find the current cursor position?
     **A:** `file.tell()`

115. **Q:** How do you close a file?
     **A:** `file.close()`

116. **Q:** Why should you use a context manager for file operations?
     **A:** It automatically closes the file even if errors occur.

117. **Q:** How do you open a file using a context manager?
     **A:**

     ```python
     with open('filename.txt', 'r') as file:
         data = file.read()
     ```

118. **Q:** How do you handle file opening errors?
     **A:** Wrap `open()` in a `try…except IOError` block.

119. **Q:** How can you check if a file exists before opening?
     **A:** Use `os.path.exists('filename.txt')`

120. **Q:** How do you delete a file?
     **A:** `os.remove('filename.txt')`

121. **Q:** How do you rename a file?
     **A:** `os.rename('old.txt', 'new.txt')`

122. **Q:** How do you copy a file?
     **A:** Use `shutil.copy('src.txt', 'dest.txt')`

123. **Q:** What function reads a CSV file line by line?
     **A:** The `csv.reader` in the `csv` module.

124. **Q:** How do you write rows to a CSV file?
     **A:** Use `csv.writer` and its `.writerow()` method.

125. **Q:** How do you open a file exclusively (fail if it exists)?
     **A:** `open('filename.txt', 'x')`

126. **Q:** How do you truncate a file’s contents?
     **A:** `file.truncate(size)` or open in write mode.

127. **Q:** How do you flush the write buffer without closing?
     **A:** `file.flush()`

128. **Q:** What is a stack?
     **A:** A Last-In, First-Out (LIFO) data structure.

129. **Q:** How do you implement a stack using a Python list?
     **A:** Use `append()` to push and `pop()` to pop.

130. **Q:** How do you check if a stack is empty?
     **A:** `if not stack:`

131. **Q:** How do you peek at the top item of a stack?
     **A:** `stack[-1]`

132. **Q:** How do you get the size of a stack?
     **A:** `len(stack)`

133. **Q:** How do you clear all items from a stack?
     **A:** `stack.clear()`

134. **Q:** What is a queue?
     **A:** A First-In, First-Out (FIFO) data structure.

135. **Q:** How do you implement a queue using a Python list?
     **A:** Use `append()` for enqueue and `pop(0)` for dequeue.

136. **Q:** How do you check if a queue is empty?
     **A:** `if not queue:`

137. **Q:** How do you peek at the front item of a queue?
     **A:** `queue[0]`

138. **Q:** How do you get the size of a queue?
     **A:** `len(queue)`

139. **Q:** What is the time complexity of `pop(0)` on a list?
     **A:** O(n), since it shifts elements.

140. **Q:** How can you implement a more efficient queue?
     **A:** Use `collections.deque` with `append()` and `popleft()`.

141. **Q:** How do you import `deque`?
     **A:** `from collections import deque`

142. **Q:** How do you push onto a `deque`?
     **A:** `dq.append(item)`

143. **Q:** How do you pop from the right of a `deque`?
     **A:** `dq.pop()`

144. **Q:** How do you pop from the left of a `deque`?
     **A:** `dq.popleft()`

145. **Q:** What is a circular queue?
     **A:** A fixed-size FIFO buffer that wraps around when it reaches the end.

146. **Q:** How do you implement a circular queue in Python?
     **A:** Use a fixed-size list with head/tail pointers and modulo arithmetic.

147. **Q:** How can you use two stacks to implement a queue?
     **A:** Push enqueues on `stack_in`; pop/dequeue from `stack_out`, transferring when empty.

148. **Q:** How do you transfer items between two stacks?
     **A:**

     ```python
     while stack_in:
         stack_out.append(stack_in.pop())
     ```

149. **Q:** Why use two stacks for a queue?
     **A:** To achieve amortized O(1) enqueue and dequeue operations.

150. **Q:** What are common stack applications?
     **A:** Expression evaluation, backtracking (e.g., undo), function call management.

Here are questions **151–200** covering **NumPy, SciPy, SymPy & Pandas**:

**NumPy & SciPy (151–170)**
151\. **Q:** What is NumPy?
**A:** A library for efficient numerical computation with N‑dimensional array objects.
152\. **Q:** How do you import NumPy?
**A:** `import numpy as np`
153\. **Q:** How do you create a 1D NumPy array?
**A:** `arr = np.array([1, 2, 3])`
154\. **Q:** How do you create a 2×3 array of zeros?
**A:** `np.zeros((2, 3))`
155\. **Q:** How do you create an array of evenly spaced values?
**A:** `np.linspace(start, stop, num)`
156\. **Q:** How do you reshape an array?
**A:** `arr.reshape(new_shape)`
157\. **Q:** How do you perform element‑wise multiplication?
**A:** `arr1 * arr2`
158\. **Q:** How do you compute the dot product?
**A:** `np.dot(arr1, arr2)` or `arr1.dot(arr2)`
159\. **Q:** How do you compute the mean of an array?
**A:** `arr.mean()` or `np.mean(arr)`
160\. **Q:** How do you find indices that satisfy a condition?
**A:** `np.where(arr > value)`
161\. **Q:** What is SciPy?
**A:** A library building on NumPy for advanced scientific computing (e.g., integration, optimization).
162\. **Q:** How do you import the optimize submodule?
**A:** `from scipy import optimize`
163\. **Q:** How do you find the minimum of a scalar function?
**A:** `optimize.minimize(fun, x0)`
164\. **Q:** How do you perform numerical integration?
**A:** `optimize.quad(func, a, b)`
165\. **Q:** How do you solve a system of linear equations?
**A:** `from scipy import linalg; linalg.solve(A, b)`
166\. **Q:** How do you compute the Fast Fourier Transform?
**A:** `from scipy.fft import fft; fft(arr)`
167\. **Q:** How do you generate a random sample from a normal distribution?
**A:** `np.random.normal(loc, scale, size)`
168\. **Q:** How do you compute the eigenvalues of a matrix?
**A:** `np.linalg.eigvals(A)`
169\. **Q:** How do you perform singular value decomposition?
**A:** `np.linalg.svd(A)`
170\. **Q:** How do you solve an ODE initial‑value problem?
**A:** `from scipy.integrate import solve_ivp; solve_ivp(fun, t_span, y0)`

**SymPy (171–180)**
171\. **Q:** What is SymPy?
**A:** A Python library for symbolic mathematics.
172\. **Q:** How do you import SymPy?
**A:** `import sympy as sp`
173\. **Q:** How do you define a symbolic variable?
**A:** `x = sp.symbols('x')`
174\. **Q:** How do you create a symbolic expression?
**A:** `expr = x**2 + 2*x + 1`
175\. **Q:** How do you simplify an expression?
**A:** `sp.simplify(expr)`
176\. **Q:** How do you expand an expression?
**A:** `sp.expand((x+1)**3)`
177\. **Q:** How do you factor a polynomial?
**A:** `sp.factor(x**2 - 1)`
178\. **Q:** How do you compute a derivative?
**A:** `sp.diff(expr, x)`
179\. **Q:** How do you perform an integral?
**A:** `sp.integrate(expr, x)`
180\. **Q:** How do you solve an equation symbolically?
**A:** `sp.solve(expr, x)`

**Pandas (181–200)**
181\. **Q:** How do you import Pandas?
**A:** `import pandas as pd`
182\. **Q:** How do you create a Series?
**A:** `pd.Series([1, 2, 3], index=['a','b','c'])`
183\. **Q:** How do you create a DataFrame from a dict?
**A:** `pd.DataFrame({'col1':[1,2], 'col2':[3,4]})`
184\. **Q:** How do you view the first 5 rows?
**A:** `df.head()`
185\. **Q:** How do you view DataFrame info (dtypes, non‑null)?
**A:** `df.info()`
186\. **Q:** How do you select a column?
**A:** `df['col_name']`
187\. **Q:** How do you select multiple columns?
**A:** `df[['col1', 'col2']]`
188\. **Q:** How do you select rows by label?
**A:** `df.loc['row_label']`
189\. **Q:** How do you select rows by integer position?
**A:** `df.iloc[0:3]`
190\. **Q:** How do you filter rows by condition?
**A:** `df[df['col'] > value]`
191\. **Q:** How do you detect missing values?
**A:** `df.isnull()` or `df.isna()`
192\. **Q:** How do you drop rows with missing data?
**A:** `df.dropna()`
193\. **Q:** How do you fill missing data with a value?
**A:** `df.fillna(value)`
194\. **Q:** How do you add a new column based on others?
**A:** `df['new'] = df['a'] + df['b']`
195\. **Q:** How do you merge two DataFrames on a key?
**A:** `pd.merge(df1, df2, on='key', how='inner')`
196\. **Q:** How do you group by a column and compute mean?
**A:** `df.groupby('col').mean()`
197\. **Q:** How do you pivot a DataFrame?
**A:** `df.pivot(index='r', columns='c', values='v')`
198\. **Q:** How do you reshape with melt?
**A:** `df.melt(id_vars=['id'], value_vars=['v1','v2'])`
199\. **Q:** How do you work with time‑series index?
**A:** Convert column: `df['date']=pd.to_datetime(df['date']); df.set_index('date', inplace=True)`
200\. **Q:** How do you read from and write to CSV/Excel?
**A:** `pd.read_csv('file.csv')`, `df.to_csv('out.csv')`, `pd.read_excel('file.xlsx')`, `df.to_excel('out.xlsx')`

201\. **Q:** What is the difference between composition and aggregation?
**A:** Composition implies ownership (lifecycle tied), aggregation is a loose association.

202. **Q:** How do you implement operator overloading for comparison?
     **A:** Define `__lt__`, `__le__`, `__gt__`, `__ge__`, `__eq__`, `__ne__`.

203. **Q:** What is the purpose of the `__call__` method?
     **A:** Allows an instance to be called like a function.

204. **Q:** How can you make a class iterable?
     **A:** Implement `__iter__` returning an iterator, and `__next__` in the iterator.

205. **Q:** How do you implement the context‑manager protocol in a class?
     **A:** Define `__enter__` and `__exit__` methods.

206. **Q:** What’s the difference between shallow and deep copy?
     **A:** Shallow copies references, deep copies recursively; use `copy.copy` vs `copy.deepcopy`.

207. **Q:** How do you define a singleton in Python?
     **A:** Override `__new__` to return the same instance on every call.

208. **Q:** How do you implement method chaining?
     **A:** Have methods return `self`.

209. **Q:** What is the Liskov Substitution Principle?
     **A:** Subclasses should be replaceable for their base classes without altering correctness.

210. **Q:** How do you enforce interface‑like behavior without `abc`?
     **A:** Rely on duck typing and documentation, or raise `NotImplementedError` in base methods.

211. **Q:** How do you hide implementation details in Python modules?
     **A:** Prefix internal names with a single underscore and avoid exporting them in `__all__`.

212. **Q:** What is the principle of coding to an interface?
     **A:** Depend on abstract base classes or protocols rather than concrete implementations.

213. **Q:** How do you use Python’s `typing` module for static type hints on classes?
     **A:** Use `from typing import Protocol, Generic, TypeVar` and annotate attributes/methods.

214. **Q:** How do you define a generic class?
     **A:**

```python
T = TypeVar('T')
class Box(Generic[T]):
    def __init__(self, content: T): self.content = content
```

215. **Q:** What is a protocol in typing?
     **A:** A structural interface that an object must satisfy, defined with `class P(Protocol): ...`.
     
216\. **Q:** How do you suppress exceptions without using an empty `except`?
**A:** Use `contextlib.suppress(ExceptionType)`.

217. **Q:** How do you chain exceptions to preserve context?
     **A:** Use `raise NewError from original_error`.

218. **Q:** What does `__context__` attribute of an exception hold?
     **A:** The previous exception implicitly chained.

219. **Q:** How do you implement a retry loop on exception?
     **A:** Wrap operation in a loop with `try…except` and break on success or max attempts reached.

220. **Q:** How do you log exceptions with traceback?
     **A:** Use `import logging; logging.exception("msg")`.

221. **Q:** How can you create exception-aware decorators?
     **A:** Wrap function in `try…except` inside the decorator and re-raise or handle accordingly.

222. **Q:** How do you define cleanup actions that depend on exception type?
     **A:** In `finally`, inspect `sys.exc_info()` or use separate `except` blocks before `finally`.

223. **Q:** How do you implement transaction-like behavior in pure Python?
     **A:** Use a context manager that commits on success in `__exit__` and rolls back on exception.

224. **Q:** What is the advantage of using `with open…` over manual `try…finally`?
     **A:** Cleaner syntax, automatically handles close even on exceptions.

225. **Q:** How do you define an exception hierarchy?
     **A:** Create base custom exception classes and subclass them for specific cases.

226\. **Q:** How do you compile a regex with verbose mode?
**A:** Use `re.VERBOSE` flag to allow whitespace and comments inside the pattern.

227. **Q:** How can you inline-debug your regex?
     **A:** Insert `(?x)` for verbose, `(?i)` for ignore‑case, etc., directly in the pattern.

228. **Q:** How do you prevent catastrophic backtracking?
     **A:** Use atomic grouping `(?>...)` or avoid nested quantifiers.

229. **Q:** What is an atomic group?
     **A:** A non‑backtracking group, defined as `(?>pattern)`.

230. **Q:** How can you match balanced parentheses with regex?
     **A:** Native regex can’t fully; use recursive patterns in PCRE or fall back to a parser.

231. **Q:** How do you use regex to parse CSV safely?
     **A:** Generally discouraged—better to use a CSV parser; regex may fail on edge cases.

232. **Q:** How do you benchmark regex performance?
     **A:** Use the `regex` module’s `regex.DEBUG` or Python’s `timeit`.

233. **Q:** How do you handle very large inputs efficiently?
     **A:** Compile once, use `finditer` with streaming, or switch to non‑regex parsing if too slow.

234. **Q:** What is a possessive quantifier?
     **A:** A quantifier that doesn’t backtrack, available in some regex engines (not Python’s `re`).

235. **Q:** How do you remove nested HTML tags with regex?
     **A:** It’s unreliable—use an HTML parser like BeautifulSoup instead.
     
236\. **Q:** How do you memory‑map a file for fast access?
**A:** Use the `mmap` module: `m = mmap.mmap(f.fileno(), length)`.

237. **Q:** How do you read a gzipped text file transparently?
     **A:** Use `import gzip; with gzip.open('file.gz','rt') as f:`.

238. **Q:** How do you stream large JSON lines (`.jsonl`) files?
     **A:** Iterate over the file object and call `json.loads()` on each line.

239. **Q:** How do you implement a priority queue?
     **A:** Use `heapq` module: push with `(priority, item)` and `heappop()`.

240. **Q:** How do you merge two sorted streams lazily?
     **A:** Use `heapq.merge(stream1, stream2)`.

241. **Q:** What is a double‑ended priority queue?
     **A:** A structure supporting both `min` and `max` extraction, implementable with two heaps.

242. **Q:** How do you implement a lock‑free queue?
     **A:** Use the `queue.SimpleQueue` in CPython 3.7+, which is thread‑safe without locks.

243. **Q:** How do you read and write files asynchronously?
     **A:** Use `aiofiles` library: `import aiofiles` and `await aiofiles.open(...)`.

244. **Q:** How can you watch a file for changes?
     **A:** Use `watchdog` library or `inotify` on Linux.

245. **Q:** How do you safely update a file in place?
     **A:** Write to a temp file and use `os.replace()` to atomically swap.

246\. **Q:** How do you broadcast arithmetic between arrays of different shapes?
**A:** NumPy automatically broadcasts dimensions when one of them is 1 or missing.

247. **Q:** How do you solve an eigenvalue problem in SciPy with sparse matrices?
     **A:** Use `scipy.sparse.linalg.eigs(A, k)` for the largest k eigenvalues.

248. **Q:** How do you perform symbolic matrix operations in SymPy?
     **A:** Create a `Matrix` with `sp.Matrix(...)` and call methods like `.inv()`, `.det()`.

249. **Q:** How do you optimize Pandas performance for large datasets?
     **A:** Use categorical dtypes, chunked processing, or `DataFrame.eval()` and `query()`.

250. **Q:** How do you create custom accessor methods in Pandas?
     **A:** Use the `@pd.api.extensions.register_series_accessor` decorator to add methods.




