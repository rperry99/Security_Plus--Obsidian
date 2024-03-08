---
Area: "[[Cyber Security]]"
tags:
  - Note
  - Acronym
  - ApplicationAttacks
aliases:
  - XSS
---
# What is Cross Site Scripting?
- Keep in mind [[Cascading Style Sheets (CSS)]] is something entirely different.
- Originally called cross-site because of browser security flaws where information from one website could be shared with another. 
- This is one of the most common web application development errors.
	- It takes advantage of the trust a user ahs for a site
- This can be considered [[Malware]] that uses JavaScript.

# Types of XSS Attacks
- [[Non-Persistent (Reflected) XSS Attacks]]
- [[Persistent (Stored) XSS Attacks]]

# Protecting against XSS
- Be careful when clicking untrusted links
	- Never blindly click in your email inbox. Never.
- Consider disabling JavaScript
	- Or control with an extension
	- This can limit website usability
	- This also offers limited protection.
- Keep your browser and applications up to date.
- Validate input; don't allow users to add their own scripts to an input field.

---
# Related Notes
```dataview
list
from [[]] and #Note 
sort file.name asc
```
