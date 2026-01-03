# dsa




## ALGORITHMS

* It is good to initialize default values first hand before loop. For example in Second Largest Positive Integer problem, we do `slargest = -1` before second pass. 



### Array

#### Standard Algorithms


#### Problems

* The most common brute-force method is to sort the array ($n log(n)$) and then do the needful.

* In an array of non-negative integers, find:
    * Largest Integer
    * Second Largest Integer
        * Brute ($O(n)$): Sort and traverse from second last to first until not equals last.
        * Better ($O(2n)$): Double Pass
        * Optimal: 