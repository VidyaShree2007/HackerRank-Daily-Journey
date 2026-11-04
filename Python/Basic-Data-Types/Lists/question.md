# Lists

**Platform:** HackerRank  
**Language:** Python 3  
**Topic:** Basic Data Types

## Problem Summary

Start with an empty list and perform a given number of commands.

The commands allow you to insert, print, remove, append, sort, pop, and reverse elements in the list.

Read each command and execute the corresponding operation in the given order. Whenever the command is `print`, display the current list.

## Commands

| Command | Description |
|---|---|
| `insert i e` | Insert integer `e` at index `i` |
| `print` | Display the list |
| `remove e` | Remove the first occurrence of `e` |
| `append e` | Add integer `e` at the end |
| `sort` | Sort the list in ascending order |
| `pop` | Remove the last element |
| `reverse` | Reverse the list |

## Sample Input

```text
12
insert 0 5
insert 1 10
insert 0 6
print
remove 6
append 9
append 1
sort
print
pop
reverse
print
```

## Sample Output

```text
[6, 5, 10]
[1, 5, 9, 10]
[9, 5, 1]
```

## Concepts Learned

- Creating and modifying lists
- `insert()`
- `append()`
- `remove()`
- `sort()`
- `pop()`
- `reverse()`
- `input()` and `split()`
- `if`, `elif`, and loops
- Type conversion using `int()`
