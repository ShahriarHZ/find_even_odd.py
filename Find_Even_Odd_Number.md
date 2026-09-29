# Find Even or Odd Number

## Problem
Write a Python program to determine whether a given number is even or odd.

## Algorithm
1. Start.
2. Take an integer `n` as input.
3. Check whether `n % 2 == 0`.
4. If the remainder is 0, print `Even`.
5. Otherwise, print `Odd`.
6. Stop.

## Example

For `n = 10`:

```text
10 % 2 = 0
```

Therefore, `10` is Even.

For `n = 7`:

```text
7 % 2 = 1
```

Therefore, `7` is Odd.

## Time Complexity

**O(1) — Constant Time**

The program performs a fixed number of operations regardless of the input value.

## Python Code

```python
n = int(input("Enter a number: "))

if n % 2 == 0:
    print("Even")
else:
    print("Odd")
```

## Sample Output

```text
Enter a number: 15
Odd
```
