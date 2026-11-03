# Find the Runner-Up Score

**Platform:** HackerRank  
**Language:** Python 3  
**Topic:** Basic Data Types

## Problem Summary

Given a list of scores from a competition, find the second-highest distinct score (runner-up score).

If the list contains duplicate scores, consider each score only once before finding the runner-up.

## Sample Input

```text
5
2 3 6 6 5
```

## Sample Output

```text
5
```

## Explanation

The given scores are `2, 3, 6, 6, 5`.

1. Remove duplicate scores: `2, 3, 6, 5`.
2. Sort the scores in ascending order: `2, 3, 5, 6`.
3. The second-highest distinct score is `5`.

## Concepts Learned

- `input()` – reading user input
- `int()` – converting input into integers
- `map()` – converting multiple inputs
- `set()` – removing duplicate values
- `sorted()` – sorting values
- Negative indexing (`[-2]`) – accessing the second-last element
