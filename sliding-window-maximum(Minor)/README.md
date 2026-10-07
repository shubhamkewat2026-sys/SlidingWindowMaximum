# Sliding Window Maximum

An efficient solution to the **Sliding Window Maximum** problem using a **Deque (Double-Ended Queue)**.

## Problem

Given an integer array and a window size `k`, find the maximum element in every sliding window of size `k`.

### Example

```text
Input:
nums = [1, 3, -1, -3, 5, 3, 6, 7]
k = 3

Output:
[3, 3, 5, 5, 6, 7]
```

## Approach

We use a **Deque** to maintain indices of elements in decreasing order of their values.

* Remove elements that are outside the current window.
* Remove smaller elements from the back of the deque.
* The element at the front is always the maximum of the current window.

## Complexity

* **Time:** `O(n)`
* **Space:** `O(k)`

## Technologies

* Java
* Data Structures & Algorithms
* Deque
