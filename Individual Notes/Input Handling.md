---
Area: "[[Cyber Security]]"
tags:
  - Note
  - ApplicationAttacks
aliases:
  - improper input handling
---

# What is input handling?
- When you have a web app or website, you need to make sure what people are entering into a field is what you expect.
- All inputs should be considered malicious. Make sure you check everything and trust nobody.
- Allowing invalid input can be devastating
	- Things like [[SQL Injection]], [[Buffer Overflows]], [[Denial of Service (DoS)]], can all happen due to you not validating your fields.

# Things to keep in mind
- Phone number fields should look for phone numbers only, with a specific format. (like 10 numbers long)
- Emails should only allow for an email address and nothing more.

---
# Related Notes
```dataview
list
from [[]] and #Note 
sort file.name asc
```
