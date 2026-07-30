### These are Python Comparison (Relational) Operators. They compare two values and return either True or False.

| Operator | Meaning                  | Example    | Output |
| -------- | ------------------------ | ---------- | ------ |
| `==`     | Equal to                 | `10 == 10` | `True` |
| `!=`     | Not equal to             | `10 != 5`  | `True` |
| `>`      | Greater than             | `10 > 5`   | `True` |
| `<`      | Less than                | `5 < 10`   | `True` |
| `>=`     | Greater than or equal to | `10 >= 10` | `True` |
| `<=`     | Less than or equal to    | `5 <= 10`  | `True` |

## Python Program

```python
a = 10
b = 5

print("a == b :", a == b)
print("a != b :", a != b)
print("a > b  :", a > b)
print("a < b  :", a < b)
print("a >= b :", a >= b)
print("a <= b :", a <= b)
```
 
 ## Output
```text
a == b : False
a != b : True
a > b  : True
a < b  : False
a >= b : True
a <= b : False
```

## Example 2
```python
x = 20
y = 20

print(x == y)
print(x != y)
print(x > y)
print(x < y)
print(x >= y)
print(x <= y)
```
## Output
```text
True
False
False
False
True
True
```

## Explanation
* `==` → Checks if both values are equal.
* `!=` → Checks if both values are different.
* `>` → Checks if the left value is greater than the right value.
* `<` → Checks if the left value is smaller than the right value.
* `>= `→ Checks if the left value is greater than or equal to the right value.
* `<=` → Checks if the left value is smaller than or equal to the right value.

These operators are commonly used with if, elif, while, and other decision-making statements in Python.
