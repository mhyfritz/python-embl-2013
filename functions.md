# Functions in Python

A *function* (sometimes also called *subroutine*) is canned code that you
can reuse. It avoids copy and pasting code (and subsequently updating code in multiple places),
helps to structure your program and improves readability.

Here's the general recipe how to define a function in Python:

```
def <function_name>([parameter_list]):
    <function_body>
```

In plain English:
* a function definition starts with the keyword `def`
* this is followed by the function name, parentheses and a colon
* optionally there can be a parameter list inside the parentheses (more on that later)
* finally, there has to be a *function body*, i.e. some statements that get
  executed when the function is called

  As an example, here's a simple function named `greet` that prints *Hi!*
  when it gets called:

```python
def greet():
    print "Hi!"
```

TBC
