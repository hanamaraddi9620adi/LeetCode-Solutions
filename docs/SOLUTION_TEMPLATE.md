# <Problem Number>. <Problem Title>

> 🔗 **Link:** https://leetcode.com/problems/<slug>/
> 🏷️ **Topics:** Arrays, Hashing
> 📊 **Difficulty:** 🟢 Easy / 🟡 Medium / 🔴 Hard

## 🧩 Problem Summary

Two or three lines, in your own words. If you can't summarize it, you don't understand it yet.

## 💡 Approach

1. **Brute force:** what's the obvious way, and what's its complexity?
2. **Key insight:** the one observation that unlocks a better solution.
3. **Optimized approach:** step-by-step description of the final algorithm.

## ⏱️ Complexity

| | Complexity | Why |
|---|---|---|
| Time | O(n) | single pass over the array |
| Space | O(1) | only counters used |

## ⚠️ Edge Cases

- Empty input / single element
- Duplicates, negatives, overflow (`int` vs `long long`)

## 📚 What I Learned

One or two lines. This is what makes the repo *yours* and not a solutions dump.

---

## Code header convention (top of every `solution.c` / `solution.cpp`)

```c
/**
 * LeetCode 1295 — Find Numbers with Even Number of Digits
 * Difficulty : Easy | Topic: Arrays, Math
 * Approach   : Count digits of each number by repeated division by 10.
 * Time       : O(n · d)  (d = digits per number)
 * Space      : O(1)
 * Author     : hanamaraddi9620adi | Date: 2026-07-23
 */
```
