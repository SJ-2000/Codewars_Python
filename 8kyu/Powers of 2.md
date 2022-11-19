# CodeWars Python Solutions

---

## Powers of 2

**Task**

Complete the function that takes a non-negative integer n as input, and returns a list of all the powers of 2 with the exponent ranging from 0 to n ( inclusive ).

Examples

```
gimme([2, 3, 1]) => 0
n = 0  ==> [1]        # [2^0]
n = 1  ==> [1, 2]     # [2^0, 2^1]
n = 2  ==> [1, 2, 4]  # [2^0, 2^1, 2^2]

```

<br>

---

### Given Code


```python
def powers_of_two(n):
    return []
```

---

### Solution


```python
def powers_of_two(n):
    res = []
    for i in range(0,n+1):
        res.append(2**i)
    return res
```


---


[See on CodeWars.com](https://www.codewars.com/kata/57a083a57cb1f31db7000028/train/python)
