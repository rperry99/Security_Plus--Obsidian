---
Area: "[[Cyber Security]]"
tags:
  - Note
  - ApplicationAttacks
aliases:
  - improper error handling
---
# What is Error Handling?
- This is what your app / website does when it encounters an error.
	- Does it show a message?
	- Does it open a debugger?

# Things to look for with your error handling
- Messages should be just informational enough
	- Avoid too much detail
	- Network Information, memory dump, [[Stack Traces]], and database dumps should be avoided.
	- IF errors show too much information, then an attacker can use those details to learn more about that system.


---
# Related Notes
```dataview
list
from [[]] and #Note 
sort file.name asc
```
