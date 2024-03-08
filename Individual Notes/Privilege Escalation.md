---
Area: "[[Cyber Security]]"
tags:
  - Note
  - AttackTypes
aliases:
---
# What is it?
- An attacker can gain higher-level access to a system by exploiting a vulnerability
	- Might be a bug or a design flaw.
- Higher level access means more capabilities
	- Commonly they go for the highest level access possible.
- These are high priority vulnerability patches
	- You want to fix these as fast as possible.
	- You don't want any user to have admin rights.

# Horizontal Privilege Escalation
- It's possible someone doesn't want to go up, but they can go left/right as well. 
- Maybe User A's access is slightly different than User B's, and they can use this to also move up and horizontal.

# Mitigating Privilege Escalation
- Patch it quickly
- Update [[Anti-Virus (AV)|anti-virus]] and [[Anti-Malware]] to block all known vulnerabilities.
- [[Data Execution Prevention]]
	- Only data in executable areas can run
- [[Address Space Layout Randomization]] can prevent a buffer overrun at a known memory address.


---
# Related Notes
```dataview
list
from [[]] and #Note 
sort file.name asc
```
