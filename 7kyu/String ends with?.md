# CodeWars Python Solutions

---

## String ends with?

**Task**

Complete the solution so that it returns true if the first argument(string) passed in ends with the 2nd argument (also a string).

Examples:
```
gimme
solution('abc', 'bc') # returns true
solution('abc', 'd') # returns false
```
<br>

---

### Given Code


```python
def solution(string, ending):
    # your code here...
    pass
```

---

### Solution


```python
def solution(string, ending):
    # your code here...
    if string.endswith(ending):
        return True
    return False
```


---


[See on CodeWars.com](https://www.codewars.com/kata/51f2d1cafc9c0f745c00037d/train/python)
