# Remove Duplicates from Sorted Array

This repository contains a Python solution to the classic algorithmic problem:  
**Remove duplicates from a sorted array in-place.**

## Problem Statement

Given an integer array `nums` sorted in non-decreasing order, remove the duplicates **in-place** such that each unique element appears only once.  
The relative order of the elements should be kept the same.  

Return the number of unique elements in `nums`.

### Requirements:
- Do **not** allocate extra space for another array.
- Modify the input array in-place using O(1) extra memory.
- Return the number `k` — count of unique elements.

---

## Example

### Input:
nums = [0,0,1,1,1,2,2,3,3,4]

### Output:
k = 5
nums[:k] = [0, 1, 2, 3, 4]
