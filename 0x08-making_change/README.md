# Project
## **0x08. Making Change**
---
## Table of Contents
- [Author Details](#author-details)
- [Project Description](#project-description)
- [Tasks](#tasks)
	- [0. Change comes from within](#0)
---
## Author Details
- *Dean Robin Otsyeno - deanrobin777@gmail.com*

## Project Description


## Tasks
#### 0
###### [Table of Contents](#table-of-contents)
**0. Change comes from within**

- Given a pile of coins of different values, determine the fewest number of coins needed to meet a given amount `total`.


   - Prototype: `def makeChange(coins, total)`
   - Return: fewest number of coins needed to meet `total`


     - If `total` is `0` or less, return `0`
     - If `total` cannot be met by any number of coins you have, return `-1`

   - `coins` is a list of the values of the coins in your possession
   - The value of a coin will always be an integer greater than `0`
   - You can assume you have an infinite number of each denomination of coin in the list
   - Your solution’s runtime will be evaluated in this task


```
carrie@ubuntu:~/0x08-making_change$ cat 0-main.py

#!/usr/bin/python3
"""
Main file for testing
"""

makeChange = __import__('0-making_change').makeChange

print(makeChange([1, 2, 25], 37))

print(makeChange([1256, 54, 48, 16, 102], 1453))

carrie@ubuntu:~/0x08-making_change$
```
```
carrie@ubuntu:~/0x08-making_change$ ./0-main.py
7
-1
carrie@ubuntu:~/0x08-making_change$
```

<br></br>
- Repo
    - GitHub repository: `alx-interview`
    - Directory: `0x08-making_change`
    - File: [`0-making_change.py`](./0-making_change.py)
---


<br></br>
<div align="right">
    <sub style="font-style: italic"> Dean Robin Otsyeno - deanrobin777@gmail.com</sub>
</div>
