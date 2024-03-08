---
Area: "[[Cyber Security]]"
tags:
  - Note
  - ApplicationAttacks
aliases:
---
# What is it?
- This is overwriting a buffer of memory, so that it spills over into other memory areas.
- Developers need to perform bounds checking
- This is not a simple exploit for an attacker to take advantage of
	- It takes time to avoid crashing things, and to make it do what you want.
- A really useful buffer overflow is repeatable, which means that a system can be compromised.

# An Example 
![[Pasted image 20240306172410.png]]
- The word "Excessive" was put into variable A
- Because there wasn't enough room for the last "e" in excessive, it gets overflowed into variable B
- That changes the value of B, which can open the computer for many different kinds of attacks.

---
# Related Notes
```dataview
list
from [[]] and #Note 
sort file.name asc
```
