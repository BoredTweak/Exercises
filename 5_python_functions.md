# Python Functions and Classes

Exercises intended to introduce creating functions and classes in Python. For each task create a new file and store it in a GitHub repository.

## Prep

- [Install Python](https://www.python.org/downloads/)
- [Install Visual Studio Code](https://code.visualstudio.com/download)

## Exercises

- Define a function which takes in two strings and prints to console output the result of combining them. Call that function on the start of the application.
- At the bottom of your Python application, add a conditional clause to check if the built-in `__name__` variable is `__main__`. This indicates that this particular python script was called directly and not as a by-product of other python scripts being called.
- Create a function which returns the number `2`. When your program is called directly, call that function and print the output of the function to the console.
- Create a lambda function which takes in 3 input variables and adds them together. Call that function with the inputs `1`, `2`, and `3` and print the output. Call that function with the inputs `1`, `"banana"`, and `3` and print the output. Comment out the last call to the function with  `1`, `"banana"`, and `3` after trying it. Call that function with the inputs `"1"`, `"banana"`, and `"3"` and print the output.
- Define a function which takes in `*args` as an input variable. In the function, iterate over each arg in `*args` printing it to console output. Call the function a few times on the start of the program with varying numbers of inputs.
- Define a function which takes in `*numbers` as an input variable. In the function, iterate over each arg in `*numbers` adding it to a new variable `result`. Call the function a few times on the start of the program with varying numbers of inputs and print each resulting output to the console output.
  - Note that `*` is an unpacking operator.
- Define a function with takes in `**kwargs` as an input variable. In the function, iterate over each kwarg in `kwargs` and print each kwarg to the console output. Call that function with the inputs `a=1`, `b=2`, `c=3`.
- Define a function with takes in `**kwargs` as an input variable. In the function, iterate over the values in `kwargs` and print each value to the console output. Call that function with the inputs `a=1`, `b=2`, `c=3`.
