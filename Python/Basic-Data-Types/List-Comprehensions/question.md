# List Comprehensions

**Platform:** HackerRank  
**Language:** Python 3  
**Topic:** Basic Data Types

## Problem Summary

Given three integers `x`, `y`, and `z`, representing the dimensions of a cuboid, and an integer `n`, generate all possible coordinates `[i, j, k]`.

The coordinates must satisfy:

- `0 <= i <= x`
- `0 <= j <= y`
- `0 <= k <= z`

Exclude coordinates where `i + j + k == n`.

Use list comprehension to solve the problem.

## Sample Input

```text
1
1
1
2
```

## Sample Output

```python
[[0, 0, 0], [0, 0, 1], [0, 1, 0], [1, 0, 0]]
```

## Approach

1. Read the values of `x`, `y`, `z`, and `n`.
2. Use nested `range()` functions.
3. Generate coordinates using list comprehension.
4. Use `if i + j + k != n` to exclude unwanted coordinates.

## Concepts Learned

- `input()`
- `range()`
- List comprehension
- Nested loops
- Conditional statements (`if`)
- Not equal operator (`!=`)
