# 1295. Find Numbers with Even Number of Digits

## Problem

Given an array of integers, count how many numbers contain an even number of digits.

---

## Intuition

Every number has some digits.

If the total number of digits is even, increase our answer.

---

## Approach

- Traverse the array.
- Count digits of each number by dividing it by 10.
- If digit count is even, increment answer.

---

## Time Complexity

O(n × d)

where d is the number of digits.

---

## Space Complexity

O(1)