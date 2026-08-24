# 🔗 LeetCode 20 - Valid Parentheses

## 📌 Problem

Given a string containing only the characters `(`, `)`, `{`, `}`, `[` and `]`, determine if the input string is valid.

A string is valid when:

* Every opening bracket has a matching closing bracket.
* Brackets are closed in the correct order.
* Each closing bracket matches the correct opening bracket.

## 💡 Approach

Use a **Stack**.

1. Store every opening bracket in the stack.
2. When a closing bracket appears, check the top of the stack.
3. If it matches, remove the opening bracket.
4. If it does not match, the string is invalid.
5. At the end, the stack must be empty.

## 🧪 Example

**Input:**
`"()[]{}"`

**Output:**
`True`

### Another Example

**Input:**
`"(]"`

**Output:**
`False`

### Explanation

`(` must be closed by `)`, but the string contains `]`, so it is invalid.

## ⏱️ Complexity

* **Time Complexity:** O(n)
* **Space Complexity:** O(n)

## 🏷️ LeetCode Details

* **Problem:** Valid Parentheses
* **Problem Number:** 20
* **Difficulty:** Easy
* **Language:** Python

## 🎯 Topics

* Strings
* Stack
* Hash Map
* Parentheses Matching

## 👩‍💻 Author

**Nandhini**
