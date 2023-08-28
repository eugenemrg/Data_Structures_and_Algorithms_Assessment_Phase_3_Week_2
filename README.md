# Data Structures and Algorithms Assessment - Phase 3 Week 2

In the same files or different scripts code out the following functions

## Stacks

Question 1: Implement a function is_balanced(expression) that takes a string 
containing parentheses, curly braces, and square brackets,and determines whether 
the expression is balanced. 

An expression is considered balanced if each opening bracket has a corresponding closing 
bracket in the correct order.  

[Question 1: Solution](/assessment1.py)

### sample input:
```
expression1 = "([]{})"
expression2 = "([)]"
print(is_balanced(expression1))  # Output: True
print(is_balanced(expression2))  # Output: False 
```

## Sequences (Lists/Tuples)

Question 2: Write a function remove_duplicates(sequence) that takes a 
sequence (list or tuple) and returns a new sequence with duplicates 
removed while maintaining the original order of elements.  

[Question 2: Solution](/assessment2.py)

### sample input:
```
input_sequence = [2, 3, 2, 4, 5, 3, 6, 7, 5]
result = remove_duplicates(input_sequence)
print(result)  # Output: [2, 3, 4, 5, 6, 7]
```

## Dictionaries

Question 3: Implement a function word_frequency(sentence) that takes 
a sentence and returns a dictionary containing the frequency of each 
word in the sentence. 

Ignore punctuation and consider words in a case-insensitive manner.  

[Question 3: Solution](/assessment3.py)

### sample input:

```
sentence = "This is a test sentence. This sentence is a test."
result = word_frequency(sentence)
print(result)
```
# Setup Requirements

- Visual Studio Code, see [here](https://code.visualstudio.com/)
- Any [supported](https://www.python.org/downloads/) OS / environments / Windows Subsystem for Linux (WSL), details [here](https://learn.microsoft.com/en-us/windows/python/web-frameworks)
- Git and Github
- Python (Recommend version 3.10+), get the latest [here](https://www.python.org/downloads/)

# Installation

Clone/Download the code from the repository and run it on any terminal with python enabled

# Language(s)
- Python

# Author

[Eugene Aduogo](https://github.com/eugenemrg)

# License
Copyright (C) 2023

Licensed under GNUv3. See [license](/LICENSE)

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.