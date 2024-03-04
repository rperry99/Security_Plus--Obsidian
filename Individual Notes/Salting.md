---
Area: "[[Cyber Security]]"
tags:
  - Note
aliases:
  - salt
---
# What is it?
- When [[Hashing]] a password, its a little bit of random data that get's added to a password.
- Every user gets their own random salt, and it's commonly stored with the password. 
- Salting will render [[Rainbow Tables]] useless as there's additional random data added to the original password.
- It slows things down with the brute force process, but won't completely stop the reverse engineering.
- What this means, is that each user will get a different hash, even if they use the same password.


---
# Related Notes
```dataview
list
from [[]] and #Note 
sort file.name asc
```
