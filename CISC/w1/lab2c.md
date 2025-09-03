``` python
var1 = 10
print(hex(id(var1)))   # memory address of var1

var1 = 100
print(hex(id(var1)))   # memory address of var1 after reassignment

```



# Answer: When var1 was resized from 10 to 100, Python created a new object for 100. The old object (10) still exists but is no longer referencing var1. This is why they are two different addresses

``` python

var2 = 100
print(hex(id(var2)))   # memory address of var2

```

# Answer: Python reuses the same memory location since var one was already being used as 100, var2 points to the same memory

``` python

x = "dog"
y = "cat"

print(x + y)                             # dogcat
print("the " + x + " chases the " + y)   # the dog chases the cat
print(x * 4)                             # dogdogdogdog

```

```python
x = 50
x = x + 1
print(x)   # 51

```

```python

a. hello = "hello"       # Valid variable name.
b. _var = 100            # Valid variable name.
c. !var_1 = 200          # Invalid. "!" is not allowed in variable names.
d. print = "print me"    # Allowed, but bad practice. Overrides built-in print().
e. False = 0             # Invalid. "False" is a reserved keyword in Python.

```

# challenges: I was a little confused about the instructions for the first half of the assignment, and I think that by the end, I was able to figure out what the assignment was asking of me. 

