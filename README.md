# Binary Search in Java

This project demonstrates a basic implementation of the **Binary Search** algorithm in Java. Binary Search is an efficient algorithm for finding an item from a sorted list of elements, running in O(log n) time complexity.

## 📂 File Structure

- `Binary.java` – Contains the implementation of binary search and a sample usage in the `main` method.

## 🔍 How It Works

1. The array must be sorted in ascending order.
2. The algorithm repeatedly divides the search interval in half.
3. If the value of the search key is less than the item in the middle, it narrows the interval to the lower half.
4. Otherwise, it narrows it to the upper half.
5. The process continues until the value is found or the interval is empty.

## 🧠Algorithm Explanation

int mid = (start + end) / 2;

The middle index is calculated in each iteration.

If the key is found at mid, the index is returned.

If the key is greater, search continues on the right half.

If the key is smaller, search continues on the left half.

If the loop ends without finding the key, -1 is returned.


## 📎 Notes
The array must be sorted for binary search to work.

This is a simple integer-based implementation, but it can be adapted for other types.
