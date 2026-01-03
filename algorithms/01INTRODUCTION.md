# INTRODUCTION

## DEFINITION


## ALGORITHMIC EFFICIENCY

* Same task can be achieved by two different algorithms. It is obvious to prefer the one which takes less time and less storage.

* Hence, to compare which one is better we need parameters to compare time the algortihms take and the space it occupies.


### DIRECT CALCULATION


### COMPLEXITY


#### TIME COMPLEXITY

1. **DEFINITION**

* Time Complexity is a theoretical measure of how the execution time of an algorithm grows with input size (n), expressed as a function of n, rather than actual clock time.

2. REMARKS

* It tells us how fast an algorithm scales, not how fast it runs on a particular machine.

3. TYPES

    1. Best Case Complexity: Tells minimum time an algorithm can take, denoted by $\sigma(n)$
    2. Average Case Complexity: Tells avergae time an algorithm will


4. **CALCULATION**
    * ASSUMPTIONS:
        * ***EVERY LINE OF CODE TAKES 1UNIT FOR EXECUTION***
        * `n` is the LENGTH of input.
        * 

    * STEPS:
        * Obtain equation for algorithm:
            * Assignments:  $1$
            * Single For Loops: $n$
            * For Loop Nested k-times: $n^k$
            * While Loop where value of $n$ gets divided by $k$: $log_{k}n$ = $log(n)$
        Non-loop expressions with single length input: $O(1)$ .

#### SPACE COMPLEXITY


#### COMPARISON

If `n` is the size of input, lesser the time complexity, better the algorithm:

$O(n) = 1 < log(log(n))  <$


