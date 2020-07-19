#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n) = linear run time. The loop's run time increases at a constant rate as input size grows.


b) O(n log n) = linearithmic run time. The outer loop is linear O(n). The inner loop is O(log n) because iterations diminish by half (j *= 2) with each step.


c) O(n) = linear run time. This is a recursive algorithm with one call to itself. Run time increases at a constant rate as input size grows.

## Exercise II

Set up binary search algorithm: runtime is O(log n).

- Set min = 0 and max = n
- If min = max heights, return this height (f) as the heighest floor.
- Set f = midpoint of min and max heights
- Run drop_egg function
    - If egg breaks: reduce max height to f-1
    - Else: raise min height to f+1

