# Palindrome

A **palindrome** is something that can be read **the same way forward and backward**.

---

## General idea
If you reverse the sequence and it remains unchanged → it is a palindrome.

---

## Palindromes in **strings**
A string is a palindrome when its sequence of characters is identical after being reversed.

### Examples
- `racecar` ✅  
- `level` ✅  
- `hello` ❌  

In many contexts, palindrome checks ignore:
- uppercase vs. lowercase letters  
- spaces and punctuation  

Classic example:

"A man, a plan, a canal: Panama"

After removing spaces, punctuation, and normalizing case:

amanaplanacanalpanama


Result: ✅ palindrome

---

## Palindromes in **numbers**
A number is a palindrome if the sequence of its digits reads the same backward.

### Examples
- `121` ✅  
- `1331` ✅  
- `123` ❌  

Here, the number is treated as a **sequence of digits**, not as a mathematical value.

---

## Formal definition
Given a sequence  
\( S = s_1, s_2, ..., s_n \)

The sequence is a palindrome if:

\[
s_i = s_{n - i + 1} \quad \text{for all } i
\]

In simple terms:  
the first element equals the last, the second equals the second-to-last, and so on.

---

Palindromes commonly appear in:
- string manipulation problems  
- algorithm challenges  
- coding interviews  
- pattern recognition tasks