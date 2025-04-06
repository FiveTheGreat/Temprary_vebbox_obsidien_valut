#### **Multiple Choice Questions (MCQs)**

##### **Data Types and Casting**
1. What is the output of `type(5.0)`?  
   - A) `int`  
   - B) `float`  
   - C) `str`  
   - D) `bool`  

2. Which of the following is a valid way to cast an integer `5` to a string?  
   - A) `string(5)`  
   - B) `str(5)`  
   - C) `int("5")`  
   - D) `toString(5)`  

3. Which of the following data types is immutable?  
   - A) List  
   - B) Dictionary  
   - C) Tuple  
   - D) Set  

4. What is the result of `int(3.8)`?  
   - A) `3`  
   - B) `3.8`  
   - C) `4`  
   - D) Error  

5. What will `type('5' + 5)` result in?  
   - A) `int`  
   - B) `float`  
   - C) `str`  
   - D) Error  

##### **If, Elif, Else**
6. What will the following code output?  
   ```python
   x = 10
   if x > 5:
       print("A")
   elif x < 15:
       print("B")
   else:
       print("C")
   ```
   - A) `A`  
   - B) `B`  
   - C) `C`  
   - D) `A B`  

7. What keyword is used to check additional conditions after `if` in Python?  
   - A) `else`  
   - B) `elif`  
   - C) `elseif`  
   - D) `elseif else`  

8. What will the following code output?  
   ```python
   x = 10
   if x % 2 == 0:
       print("Even")
   else:
       print("Odd")
   ```
   - A) `Even`  
   - B) `Odd`  
   - C) `10`  
   - D) Error  

9. Which of these is not a valid comparison operator in Python?  
   - A) `==`  
   - B) `!=`  
   - C) `<=>`  
   - D) `>=`  

10. What will this code output?  
    ```python
    age = 18
    if age >= 18:
        print("Adult")
    else:
        print("Minor")
    ```
    - A) `Adult`  
    - B) `Minor`  
    - C) Error  
    - D) `18`  

##### **Functions**
11. Which keyword is used to define a function in Python?  
    - A) `function`  
    - B) `def`  
    - C) `lambda`  
    - D) `define`  

12. What will this code output?  
    ```python
    def greet(name):
        return "Hello, " + name
    print(greet("Alice"))
    ```
    - A) `Hello Alice`  
    - B) `Hello, Alice`  
    - C) `Hello name`  
    - D) Error  

13. What is the default return type of a function that does not return any value?  
    - A) `None`  
    - B) `0`  
    - C) `False`  
    - D) Error  

14. Can a function call itself in Python?  
    - A) Yes  
    - B) No  

15. Which statement is correct about functions in Python?  
    - A) Functions cannot have default arguments.  
    - B) Functions cannot return multiple values.  
    - C) Functions can be defined inside another function.  
    - D) Functions cannot be assigned to variables.  

##### **Lambda Functions and List Comprehensions**
16. What will this code output?  
    ```python
    add = lambda x, y: x + y
    print(add(3, 5))
    ```
    - A) `8`  
    - B) `35`  
    - C) `(3, 5)`  
    - D) Error  

17. Lambda functions are also known as:  
    - A) Anonymous functions  
    - B) Named functions  
    - C) Recursive functions  
    - D) Nested functions  

18. What will this code output?  
    ```python
    nums = [1, 2, 3, 4]
    squares = [x ** 2 for x in nums]
    print(squares)
    ```
    - A) `[1, 4, 9, 16]`  
    - B) `[1, 2, 3, 4]`  
    - C) `[2, 4, 6, 8]`  
    - D) Error  

19. Which of the following is a valid list comprehension?  
    - A) `[x for x in range(5)]`  
    - B) `[for x in range(5)]`  
    - C) `{x for x in range(5)}`  
    - D) `x for x in range(5)`  

20. What is the output of the following code?  
    ```python
    lst = [x for x in range(10) if x % 2 == 0]
    print(lst)
    ```
    - A) `[2, 4, 6, 8, 10]`  
    - B) `[0, 2, 4, 6, 8]`  
    - C) `[]`  
    - D) Error  

##### **Loops**
21. What will the following code output?  
    ```python
    for i in range(5):
        print(i, end=" ")
    ```
    - A) `1 2 3 4 5`  
    - B) `0 1 2 3 4`  
    - C) `5 4 3 2 1`  
    - D) Error  

22. Which loop is preferred when the number of iterations is known beforehand?  
    - A) `for`  
    - B) `while`  

23. What will break a loop in Python?  
    - A) `stop`  
    - B) `break`  
    - C) `exit`  
    - D) `halt`  

24. What does `continue` do in a loop?  
    - A) Stops the loop  
    - B) Skips the current iteration  
    - C) Exits the program  
    - D) Repeats the current iteration  

25. What will the following code output?  
    ```python
    count = 0
    while count < 3:
        print("Hello")
        count += 1
    ```
    - A) `Hello Hello Hello`  
    - B) `Hello\nHello\nHello`  
    - C) `Hello\nHello`  
    - D) Error  

---

### **Programming Questions**

1. Write a program to check if a given number is even or odd.  
2. Implement a function that returns the factorial of a number.  
3. Write a lambda function to multiply two numbers and test it.  
4. Create a list comprehension to filter all even numbers from a list.  
5. Write a Python function to find the largest of three numbers.  
6. Implement a program that counts the vowels in a string.  
7. Write a program to calculate the sum of all integers in a list using a `for` loop.  
8. Create a Python script that uses `if-elif-else` to classify a number as positive, negative, or zero.  
9. Write a Python program to print the Fibonacci series up to `n` terms using a loop.  
10. Write a Python function to check if a number is a prime number.  
11. Implement a Python program to reverse a string using a loop.  
12. Write a list comprehension to create a list of squares for numbers from 1 to 20 that are divisible by 3.  

--- 

Good luck!
