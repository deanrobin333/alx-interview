# Project
## **0x04. UTF-8 Validation**
---
## Table of Contents
- [Author Details](#author-details)
- [Project Description](#project-description)
- [Tasks](#tasks)
	- [0. UTF-8 Validation](#0)
---
## Author Details
- *Dean Robin Otsyeno - deanrobin777@gmail.com*

## Project Description


## Tasks
#### 0
###### [Table of Contents](#table-of-contents)
**0. UTF-8 Validation**

- Write a method that determines if a given data set represents a valid UTF-8 encoding.


   - Prototype: `def validUTF8(data)`
   - Return: `True` if data is a valid UTF-8 encoding, else return `False`
   - A character in UTF-8 can be 1 to 4 bytes long
   - The data set can contain multiple characters
   - The data will be represented by a list of integers
   - Each integer represents 1 byte of data, therefore you only need to handle the 8 least significant bits of each integer


```
carrie@ubuntu:~/0x04-utf8_validation$ cat 0-main.py

#!/usr/bin/python3
"""
Main file for testing
"""

validUTF8 = __import__('0-validate_utf8').validUTF8

data = [65]
print(validUTF8(data))

data = [80, 121, 116, 104, 111, 110, 32, 105, 115, 32, 99, 111, 111, 108, 33]
print(validUTF8(data))

data = [229, 65, 127, 256]
print(validUTF8(data))

carrie@ubuntu:~/0x04-utf8_validation$
```
```
carrie@ubuntu:~/0x04-utf8_validation$ ./0-main.py

True
True
False
carrie@ubuntu:~/0x04-utf8_validation$
```

<br></br>
- Repo
    - GitHub repository: `alx-interview`
    - Directory: `0x04-utf8_validation`
    - File: [`0-validate_utf8.py`](./0-validate_utf8.py)
---


<br></br>
<div align="right">
    <sub style="font-style: italic"> Dean Robin Otsyeno - deanrobin777@gmail.com</sub>
</div>
