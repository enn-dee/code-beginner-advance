## Indentation

In Python, indentation is used to indicate the block of code that should be executed as part of a control structure, such as an if statement or a for loop. Indentation is important in Python because it is used to indicate the beginning and end of these blocks of code, rather than using curly braces like some other programming languages.
Here is an example of an if statement in Python:
```python
x = 10
if x > 5:    
     print("x is greater than 5")
else:
     print("x is not greater than 5")
```
In this example, the code in the first block (print("x is greater than 5")) will be executed if the condition x > 5 is **True**, and the code in the second block (print("x is not greater than 5")) will be executed if the condition is **False**. The indentation indicates that the code in the first block belongs to the **if** statement, and the code in the second block belongs to the **else** statement.
Here is an example of a for loop in Python:
```python
names = ["John", "Paul", "George", "Ringo"]
for name in names:    print(name)
```
In this example, the code in the block *(print(name))* will be executed once **for** each element in the names list. The indentation indicates that the code in the block belongs to the for loop.
It's important to be consistent with your indentation in Python, as the interpreter will raise an error if the indentation is not correct. It is recommended to use four spaces for each level of indentation.
I hope this helps to clarify how indentation is used in Python! Let me know if you have any questions.
## Multi-Line Statements
You can use the '\' character to continue a statement on the next line, or use parentheses to define a multi-line statement. You can also use triple quotation marks to define a multi-line string.

For example, you can use the '\' character to write a long 'print' statement on multiple lines:
```python
print("This is a very long string that needs to be \
split over multiple lines because it is too long to \
fit on one line.")
```
You can also use parentheses to define a multi-line statement:

```python
x = (1 + 2 + 3 + 4 +
     5 + 6 + 7 + 8)
```
Finally, you can use triple quotation marks to define a multi-line string:
```python
x = """This is a
multi-line
string"""
```
