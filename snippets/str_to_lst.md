---
title: str_to_lst
tags: string,list,math,intermediate
---

Reads an input string with positive or negative whole numbers and converts it to a list of integers.  

- `input().split()` reads and splits the string into a list where each word is a list item.
- `map(int, )` maps the element of the list and converts them into integers. Returns a map object.
- `list()` convert the map object to list for readibility.


```py
def str_to_lst(strng):
    input_string = list(map(int,strng.split()))
    return input_string 
```

```py
ls = str_to_lst("1 2 3 4) # [1, 2, 3, 4]
```
