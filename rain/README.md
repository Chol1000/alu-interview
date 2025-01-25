# Rainwater Retention Calculator

## Project Description
This project involves calculating the amount of water that can be trapped between walls after it rains. The walls are represented by a list of non-negative integers where each integer indicates the height of a wall, and the width is always 1. The task is to determine how much water would be retained between the walls.

## Requirements

### General
- **Allowed editors**: vi, vim, emacs
- **Interpreter/Compiler**: Python 3.4.3 (Ubuntu 14.04 LTS)
- **File Requirements**:
  - All files should end with a new line.
  - The first line of every Python file should be `#!/usr/bin/python3`.
  - Files must be executable.
- **Coding Style**: 
  - Code should comply with PEP 8 style (version 1.7.x).
- **Module Restrictions**: 
  - No external modules can be imported.
- **Documentation**: 
  - All modules and functions must be documented.

### Task
**0. Rain (Mandatory)**
- Given a list of non-negative integers representing the heights of walls, calculate how many square units of water will be retained after it rains.
- The ends of the list are not walls (i.e., before index 0 and after the last index) and will not retain water.
- If the list is empty, return 0.

#### Prototype:
```python
def rain(walls):

