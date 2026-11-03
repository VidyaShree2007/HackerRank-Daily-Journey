# Nested Lists

**Platform:** HackerRank  
**Language:** Python 3  
**Topic:** Basic Data Types

## Problem Summary

Given the names and grades of students, store the information in a nested list.

Find the second-lowest distinct grade and print the names of all students who received that grade in alphabetical order.

Print each name on a separate line.

## Sample Input

```text
5
Harry
37.21
Berry
37.21
Tina
37.2
Akriti
41
Harsh
39
```

## Sample Output

```text
Berry
Harry
```

## Explanation

1. Store each student's name and grade in a nested list.
2. Extract all grades and remove duplicates using `set()`.
3. Sort the grades in ascending order.
4. Find the second-lowest grade.
5. Select the students who received that grade.
6. Sort their names alphabetically and print them.

## Concepts Learned

- Nested lists
- `append()`
- `float()`
- `set()`
- `sorted()`
- List and generator comprehensions
- Conditional statements
- Alphabetical sorting
