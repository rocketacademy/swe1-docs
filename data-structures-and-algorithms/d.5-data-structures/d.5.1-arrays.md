# D.5.1: Arrays

## Introduction

Many of us will be familiar with arrays since we started using them in Coding Basics. This module will focus on Python-specific array syntax and array-specific practice problems.

## Tips

### Useful Python List Syntax

1. Basic Python list methods: [https://www.w3schools.com/python/python\_arrays.asp](https://www.w3schools.com/python/python_arrays.asp)
2. Python list slice syntax: [https://stackoverflow.com/a/509295](https://stackoverflow.com/a/509295)

### Use Iteration Instead of Recursion to Loop over Arrays

Although we just learned recursion and many of the Learn Python recursion problems used recursion to iterate over strings or arrays, generally we prefer iteration where possible, because recursion utilises more computer memory.

## Introduction to Leetcode

Leetcode problems are encapsulated in classes. We will learn more about classes in [D.6: Object-Oriented Programming](../d.6-intro-to-object-oriented-programming.md), but without going into too much detail here, the following are what we need to know to solve and submit problems in Leetcode.

1. Every method inside a Python class requires `self` as the 1st parameter in the method definition, so that the method has access to other attributes and methods within the class instance via `self`.
2. To call Python class methods \(i.e. methods inside the class\), we will need to prefix the method name with `self.`, for example `self.myMethodName()`. There is no need to pass `self` as the 1st parameter to class methods, even though `self` is the 1st param in the method definition.
3. Python 3 provides optional syntax to specify variable types. Leetcode problems specify variable types in function parameters to help us understand the inputs and outputs of the function we need to implement.
4. There is no need for us to call the function we define, for example `validMountainArray`. Leetcode will call the function, we just need to implement it.

```python
class Solution:
    def validMountainArray(self, arr: List[int]) -> bool:
```

## Exercises

Once you've attempted each problem, find solutions in either the Solution or Discuss tabs on that problem's page.

### Pre-Class

1. [https://leetcode.com/problems/running-sum-of-1d-array/](https://leetcode.com/problems/running-sum-of-1d-array/)
2. [https://leetcode.com/problems/richest-customer-wealth/](https://leetcode.com/problems/richest-customer-wealth/)

### Part 1

1. [https://leetcode.com/problems/valid-mountain-array](https://leetcode.com/problems/valid-mountain-array)
2. [https://leetcode.com/problems/sort-array-by-parity/](https://leetcode.com/problems/sort-array-by-parity/)
3. [https://leetcode.com/problems/shuffle-the-array/](https://leetcode.com/problems/shuffle-the-array/)
4. [https://leetcode.com/problems/intersection-of-two-arrays-ii/](https://leetcode.com/problems/intersection-of-two-arrays-ii/)

### Part 2

1. [https://leetcode.com/problems/count-items-matching-a-rule/](https://leetcode.com/problems/count-items-matching-a-rule/)
2. [https://leetcode.com/problems/kids-with-the-greatest-number-of-candies/](https://leetcode.com/problems/kids-with-the-greatest-number-of-candies/)
3. [https://leetcode.com/problems/number-of-good-pairs/](https://leetcode.com/problems/number-of-good-pairs/)
4. [https://leetcode.com/problems/string-matching-in-an-array/](https://leetcode.com/problems/string-matching-in-an-array/)

### More Comfortable

1. [https://leetcode.com/problems/jewels-and-stones/](https://leetcode.com/problems/jewels-and-stones/)
   1. Strings can be iterated over like lists in Python.
2. [https://leetcode.com/problems/squares-of-a-sorted-array/](https://leetcode.com/problems/squares-of-a-sorted-array/)
3. [https://leetcode.com/problems/relative-sort-array/](https://leetcode.com/problems/relative-sort-array/)
4. [https://leetcode.com/problems/sort-array-by-parity-ii](https://leetcode.com/problems/sort-array-by-parity-ii/)
5. [https://leetcode.com/problems/how-many-numbers-are-smaller-than-the-current-number/](https://leetcode.com/problems/how-many-numbers-are-smaller-than-the-current-number/)

