---
Area: "[[Cyber Security]]"
tags:
  - Note
  - NetworkAttacks
aliases:
---
# What is it?
- An arbitrary number that is only used once in [[Cryptography]].
- "For the nonce" => For the time being.
- Its a random or pseudo-random number, something that can't be reasonably guessed.
	- Can also be a counter.
- A nonce is used during the login process.
	- Server gives you a nonce
	- Calculate your password hash using the nonce
	- Each password hash sent to the host will be different, so a [[Replay Attacks|replay]] won't work.

# Types of Nonces
- [[Initialization Vector (IV)]]

# Salt
- A nonce is commonly used in password randomization, adding [[Salting|salt]].
	- It makes the password hash unpredictable.
- Password storage should always be salted, and each user gets a different salt.
- If the password database is breached, you can't correlate any passwords, even users with the same password will have different hashes stored.


---
# Related Notes
```dataview
list
from [[]] and #Note 
sort file.name asc
```
