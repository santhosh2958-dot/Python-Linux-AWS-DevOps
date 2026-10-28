  
# Python Fundamentals — Part 1

## 1. What is Python?
Python is a programming language used for scripting, automation, APIs, Linux administration, AWS and DevOps.

## 2. First program
```python
print("Hello, World!")
```
`print()` displays information on the screen.

## 3. Variables
A variable is a name that refers to a value.
```python
server_name = "web-01"
server_count = 5
```

## 4. Data types
- `str`: text, e.g. `"Ubuntu"`
- `int`: whole number, e.g. `10`
- `float`: decimal, e.g. `75.5`
- `bool`: `True` or `False`
- `None`: represents no value

## 5. Input and conversion
```python
name = input("Enter your name: ")
age = int(input("Enter your age: "))
print(f"Hello {name}, next year you will be {age + 1}")
```
Remember: `input()` returns text. Convert it when you need a number.

## 6. Operators
- `+`: addition
- `-`: subtraction
- `*`: multiplication
- `/`: division
- `//`: floor division
- `%`: remainder
- `**`: exponentiation
- `==`: equality comparison
- `!=`: not equal

## 7. Conditions
```python
disk_usage = 82

if disk_usage >= 90:
    print("CRITICAL")
elif disk_usage >= 75:
    print("WARNING")
else:
    print("OK")
```

## Memory tricks
- `print()` = display.
- `input()` = receive text.
- `=` = assign.
- `==` = compare.
- `if` = make a decision.
- Indentation = shows which statements belong to a block.

## Practice
1. Print your name.
2. Create a variable for your favourite operating system.
3. Ask the user for two numbers and print their sum.
4. Check whether disk usage is above 90%.
